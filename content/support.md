+++
author = "Aravind R S"
date = 2016-07-22T13:35:52Z
description = ""
draft = true
slug = "support"
title = "Support"

+++


<p class="confirm" style="font-weight: bold; display: none;">Thank you for supporting the Internet Freedom Foundation’s work for an open web.</p>

IFF was intially set up by a group of volunteers that worked on the SaveTheInternet campaign. Community building and working with volunteers is in our DNA. Could you support the team by making a donation or volunteering your time and expertise? 

Please fill the form below and we’ll be in touch with you! 

<form id='support' method="post" action="/lists/subscribe" accept-charset="utf-8">

  <p><label for="name">Your name</label><input type="text" id="name" name="name" required></p>
  <p><label for="email">Your email address</label><input type="email" id="email" name="email" required></p>
  <p><label for="Phone">Your phone number</label><input type="tel" id="Phone" name="Phone" required placeholder="+91"></p>

  <p><label><input type="checkbox" id="volunteer-toggle" data-toggle="volunteer"/>I’d like to volunteer my time and skills</label></p>

  <div class="conditional if-volunteer" style="padding-left: 1em;">
    <p class="volunteer-required">Please select the specific area you can help with.</p>
    <p><label>
      <input type="radio" name="area" value="communication">
      <b>Communication</b>: Writing articles for the public
    </label></p>
    <p><label>
      <input type="radio" name="area" value="policy">
      <b>Policy, Research and Legal</b>: Writing legal and policy
      briefs
    </label></p>
    <p><label>
      <input type="radio" name="area" value="technology">
      <b>Technology</b>: Building websites and apps
    </label></p>
    <p><label>
      <input type="radio" name="area" value="design">
      <b>Design</b>: Strengthening IFF’s visual identity
    </label></p>
  </div>

  <p><label><input type="checkbox" id="donate-toggle" data-toggle="donate"/>I’d like to make a donation</label></p>

  <div class="conditional if-donate" style="padding-left: 1em;">
    <p>
    <label><input type="radio" name="amount" value="2500">₹1,000</label>
    <label><input type="radio" name="amount" value="5000">₹2,500</label>
    <label><input type="radio" name="amount" value="10000" checked>₹10,000</label>
    <label><input type="radio" name="amount" value="15000">₹15,000</label>
    <label><input type="radio" name="amount" value="other" data-toggle="otheramount">Other…</label>
    </p>
    <p class="conditional if-otheramount"><input id="otheramount" type="number" min="1000" max="100000" step="100" value="50000" placeholder="Other amount"></p>
    <p>Please review our <a href="https://internetfreedom.in/donation-terms">donation terms and conditions</a>. Currently, we only accept donations from Indian citizens, through an Indian bank or card.</p>
  </div>

  <input type="hidden" name="Volunteer" />
  <input type="hidden" name="Donate" />
  <input type="hidden" name="PaymentId" />
  <input type="hidden" name="list" value="rvjwP8BiNCBeHzx6LUg5mQ" />
  <input type="submit" value="Submit">
</form>

If you have any questions, please email [volunteer@internetfreedom.in](mailto:volunteer@internetfreedom.in) or [donate@internetfreedom.in](mailto:donate@internetfreedom.in).

We also have a small number of full-time and internship positions. If you are interested, please email email [join@internetfreedom.in](mailto:join@internetfreedom.in).

<script src="https://checkout.razorpay.com/v1/checkout.js"></script>

<script>
(function () {
  var $ = document.querySelector.bind(document),
      $$ = document.querySelectorAll.bind(document);

  function openRazorpay(amount) {
    function success(response) {
      console.log("Success", response);
      $('input[name=PaymentId]').value = response.razorpay_payment_id;
      $('form#support').submit();
    }

    new Razorpay({
      key: 'rzp_live_IJniBxSyXf1vIG',
      amount: amount * 100,
      name: 'Donate',
      description: 'Help defend Internet Freedom',
      image: '/content/images/2016/09/iff-icon-125.png',
      handler: success,
      prefill: {
        name: $('#name').value,
        email: $('#email').value,
        contact: $('#Phone').value
      },
      theme: { color: '#aa6644', image_padding: false }
    }).open();
  }

  document.addEventListener('DOMContentLoaded', function () {
    var match = location.search && location.search.match(/\bemail=([^&]*)/),
        email = match && match[1] && decodeURIComponent(match[1]);

    if(email) {
      $('input[name=email]').value = email;
      $('.confirm').style.display = 'block';
    }

    $('form#support').addEventListener('submit', function (event) {
      var donate, volunteer;

      if($('input[data-toggle=donate]').checked) {
        donate = Array.prototype.filter.call(
          $$('input[name=amount]'),
          function (item) { return item.checked; }
        )[0].value;

        if(donate == 'other') {
          donate = $('#otheramount').value;
        }
      } else {
        donate = 'no';
      }

      if($('input[data-toggle=volunteer]').checked) {
        volunteer = Array.prototype.filter.call(
          $$('input[name=area]'),
          function (item) { return item.checked; }
        )[0];

        if(!volunteer) {
          event.preventDefault();
          $('.volunteer-required').style.color = '#f00';
          $('.volunteer-required').style.fontWeight = 'bold';
          return;
        }

        volunteer = volunteer.value;
      } else {
        volunteer = 'no';
      }

      $('input[name=Donate]').value = donate;
      $('input[name=Volunteer]').value = volunteer;

      if(donate != 'no' && !$('input[name=PaymentId]').value) {
        event.preventDefault();
        openRazorpay(donate);
        return false;
      }
    });
  });
}());
</script>

