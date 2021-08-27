+++
author = "Rohin Garg"
categories = ["Net Neutrality", "BSNL"]
date = 2021-08-09T09:06:54Z
description = ""
draft = false
image = "https://internetfreedom.in/content/images/2021/08/BSNL-code-1.png"
slug = "taking-a-closer-look-at-bsnls-code-injections-savetheinternet-2"
summary = "We wrote to BSNL about the code injections that continue to persist on their network. In our representation, we highlighted the inadequacy of their past responses to our earlier representations and RTIs, and outlined some key questions that need to be addressed by BSNL."
tags = ["Net Neutrality", "BSNL"]
title = "BSNL is injecting code on to your browsers, and here's what it does. #SaveTheInternet"

+++


{{< gallery >}}
{{< galleryImg  src="https://internetfreedom.in/content/images/2021/08/BSNL-code.png" width="1600" height="900" >}}{{< /gallery >}}

>>>> <form><script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_HLkgeWGQLMuddp" async> </script> </form>

### **Tl;dr**

We wrote to BSNL about the code injections that continue to persist on their network. In our representation, we highlighted the inadequacy of their past responses to our earlier representations and RTIs, and outlined some key questions that need to be addressed by BSNL.

### **Background**

In May 2019, we had sent a [representation to BSNL regarding the code injections](https://internetfreedom.in/venom-venom-venom-bsnl-engaging-in-code-injections/), explaining how these code injections were illegal under several legal frameworks such as the Information Technology Act, 2000 and Cellular Media Telephone Services Agreement signed by BSNL. Having received no response, we went ahead with our a [three-pronged action approach](https://internetfreedom.in/weve-been-left-on-read/), which included:

1. Filing an RTI with BSNL
2. Filing an RTI with and writing a complaint to the Department of Telecommunications (DoT)
3. Filing an incident report with CERT-IN

Subsequently, while we did not receive a response from the DoT and CERT-In to our complaints, [we received responses to the RTIs](https://internetfreedom.in/bsnls-code-of-misconduct/) filed with BSNL and the DoT. While BSNL acknowledged the existence of these injections, they claimed that there was no malware in the code.

We then [received further replies to our RTIs,](https://internetfreedom.in/bsnls-claim-we-have-dnd-mechanisms/) in which BSNL stated that:

* Providing  information on BSNLs engagement in the insertion of browser injections or code injections would violate 'commercial confidence' and harm BSNL's competitive position.
* They rely on such activities to communicate with customers on available offers and useful information like Parental Control Guidelines.
* If they receive complaints via mails, they enable their 'DND' mechanism after confirming and collecting User Ids.

Additionally, we had [filed an incident report with CERT-IN](https://drive.google.com/file/d/11FXCBEPN7c8orj5O6B8uMHDQUak3k7Tp/view) to which we had received no response. However, an [RTI reply confirmed that CERT-IN had written to BSNL](https://drive.google.com/file/d/1OCt_kdH60f3qCqEEiJI3JtxDTjly7D1Q/view), indicating that at the very least some action had been initiated.

Sadly, despite all this huffing and puffing, code injections continue to happen. Thus, based on the large number of complaints we have received, we decided to take a look at the technical aspects of this issue, and inspect the code that is being generated.

### A closer look at the code

We were able to analyse some of the code that is being injected. Consider the extract below (a larger extract can be found [here](https://drive.google.com/file/d/10JmPSJvmsYaubHVtrwUiC0ytDicRHBjk/view?usp=sharing)).

{{< figure src="https://internetfreedom.in/content/images/2021/08/BSNL-code.jpg" >}}

The script seems to indicate that a host of information is being shared, presumably with a third party advertiser, including not only details about the website being visited, but also information that could potentially identify the user. For example, the user’s IP address is being shared, while the variable subscriberId would indicate that some sort of alphanumeric identifier (that would presumably be unique to a user) is also being shared. Now, generally, when user data is shared with advertisers, it is done so in an aggregated manner that does not allow the advertiser to directly see who these users are. However, on the basis of the code above, it would seem like BSNL is sharing non-aggregated browsing data directly!

Furthermore, based on our conversations with security researchers and users, we have identified some other details about these code injections:

* **Session based injection:** Broadly, these injections seem to happen at the beginning of each session (basically, they repeat after approximately an hour or so). Moreover, this frequency does not seem to change even if you switch browsers. For example, suppose you start a browsing session at 7 PM on Mozilla and encounter the injected adware. Next, at 7:50 PM, you switch to Chrome. Then the next ad you will see will appear at 8 PM (not at 7:50 PM at the start of the session). This means that it is likely that some sort of cookie is being stored locally on your computer.
* **Code on BSNL server:** As we have confirmed, this is not a bug, it's a feature - the code that is being injected is indeed hosted on BSNL servers! One of the researchers we spoke to even mentioned that some of the ads being served have previously been identified as malware.
* **Adware made to look like an error page:** One of the people we spoke to mentioned that when they clicked on one of the websites from which the ad seems to originate, they were led to a page which prima facie looked like a error page (à la “this web page is not available”) but was in fact a page that was only designed to look like one i.e. someone purposely designed the web page in that manner.

**Our Recommendations**

BSNL’s code injections have been an issue from [as long ago as 2015](https://broadbandforum.co/threads/bsnl-is-inserting-ads-in-websites-sending-their-users-to-malware-sites-through-malware-code-injection.169151/) (if not even before), and yet even today they continue to happen. Thus, we have the following suggestions for BSNL:

1. **End the tyranny of defaults:** In the event that BSNL is going to continue with such egregious impingements upon the rights of users, such ‘advertising services’ (if they can be called that), must be made opt-in i.e. users must provide explicit consent for such services.
2. ******Clarity in implementation:** **** BSNL needs to come out with a clear response as to how the decision to implement these services was arrived upon. Details about any agreements signed for such purposes also need to be provided. Furthermore, we have asked BSNL to provide clarity on what percentage of their annual revenue is being derived from these services.
3. ****Transparency on security:**** Given the potential threat of malvertising, through malicious code being injected through seemingly harmless ads, BSNL needs to provide a clear outline of all the security practices they are following to ensure that compromised code is not being injected into users’ browsers.

_This is an issue that we have been tracking for some time, and we understand the pain of BSNL users. Thus, in the near future, we will be ramping up our efforts to hold BSNL accountable, including  releasing a model complaint that users can send to BSNL and the Department of Telecommunications. Stay tuned!_

_To report an instacne of code injections by BSNL, please see [here](https://blocksurvey.io/survey/1PfQfn62JSDjjyK4nuHoY5t21wKeuocLLm/a9e25aa3-758d-457f-b8b4-24dcb07b2c23)._

**Important Documents**

1. The Personal Data Protection Bill, 2019 __ as introduced by the Minister for Electronics and Information Technology, Mr. Ravi Shankar Prasad ([**link**](http://164.100.47.4/BillsTexts/LSBillTexts/Asintroduced/373_2019_LS_Eng.pdf))
2. Blogpost dated 17th May, 2019 titled “Venom, venom, venom. BSNL engaging in code injections” (**[link](https://internetfreedom.in/venom-venom-venom-bsnl-engaging-in-code-injections/)**)
3. Blogpost dated 29th July, 2019 titled “We've been left on read : Lack of response from BSNL and DOT on Net Neutrality violations. #SaveTheInternet” (**[link](https://internetfreedom.in/weve-been-left-on-read/)**)
4. Blogpost dated 11th October, 2019 titled “BSNL's claim: "We have DND Mechanisms".” (**[link](https://internetfreedom.in/bsnls-claim-we-have-dnd-mechanisms/)**)

> > > <form><script src="https://cdn.razorpay.com/static/widget/subscription-button.js" data-subscription_button_id="pl_HLk5qU1K35hmPH" data-button_theme="brand-color" async> </script> </form>









