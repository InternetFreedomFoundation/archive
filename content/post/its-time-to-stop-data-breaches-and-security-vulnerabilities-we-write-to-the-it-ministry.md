+++
author = 'Apar Gupta'
categories = ['Data Protection', 'SaveOurPrivacy', 'Breaches']
date = 2020-06-02T23:35:11Z
description = ''
draft = false
image = 'https://internetfreedom.in/content/images/2020/06/Aarogya-Setu-A-path-to-health-or-jail--1--1.png'
slug = 'its-time-to-stop-data-breaches-and-security-vulnerabilities-we-write-to-the-it-ministry'
summary = 'Till we fix the regulatory and cyber security plumbing of our digital, public infrastructure the data leaks and cyber security vulnerabilities will continue'
tags = ['Data Protection', 'SaveOurPrivacy', 'Breaches']
title = "It's time to stop data breaches and security vulnerabilities. We write to the IT Ministry. #SaveOurPrivacy"

+++


{{< figure src="https://internetfreedom.in/content/images/2020/06/Aarogya-Setu-A-path-to-health-or-jail--1-.png" >}}

<div style="text-align:center;">
    <a href="https://internetfreedom.in/become-an-iff-member-today/" class="button">We need 50!</a>
</div>

### Tl;dr

As per [a report](https://www.vpnmentor.com/blog/report-csc-bhim-leak/) published by the website, “vpnMentor” a website that provided for on-boarding services for BHIM (a UPI payment app like Google Pay) contained a security vulnerability. This reportedly impacted millions of Indians for more than two years and exposed several, incredibly sensitive pieces of information including Aadhaar Cards and Caste certificates. While this immediately met with blanket denials from Government officials, we are urging for recommendations that will help improve our digital public infrastructure by encouraging cyber security researchers in India.

### A massive security vulnerability impacting millions of India

Two days back vpnMentor [reported](https://www.vpnmentor.com/blog/report-csc-bhim-leak/) a massive cyber security vulnerability impacting  sensitive financial and personal data impacting millions of Indians. Those impacted are from semi-urban and rural backgrounds leaving them particularly vulnerable and practically incapable to take effective steps to safeguard themselves.

The vulnerability impacted the website http://cscbhim.in/ which is operated by CSC e-Governance Services India Limited (CSC). CSC is a special purpose vehicle set up by the Ministry of Electronics & IT (MEITY). The principal role of CSC has been to promote and on-board millions of Indians particularly farmers and semi-urban and rural businesses (Village Level Entrepreneurs or VLEs) towards Bharat Interface for Money (BHIM) to ostensibly promote financial inclusion through electronic payments.

The details of this vulnerability are truly shocking and reveal the following.

* ******Nature of the security lapse:****** The issue as explained is as follows, “_In this case, the data was stored on an unsecured Amazon Web Services (AWS) S3 bucket. S3 buckets are a popular form of cloud storage across the world but require developers to set up the security protocols on their accounts. The exposed S3 bucket was labeled “csc-bhim”, and our team was quickly able to identify the developers behind the website “www.cscbhim.in” as the owners of the data._” A further lapse indicated was, “_The S3 bucket also contained an Android application package (APK), a file format used by Android’s operating system for the distribution and installation of apps. AWS Key pairs are the equivalent of admin user/password in Amazon’s infrastructure, potentially giving the holder of the key access to all data, the ability to start and stop servers, access the S3 bucket’s controls, and more._”
* **Details of the personal data:** The vulnerability impacted approximately 7.26 million records collected over the month of February 2019. Such records contained the details of scans of Aadhaar cards, scans of caste certificates, photos used as proof of residence, professional certificates and degrees, screenshots taken within financial and banking apps as proof of fund transfers along with Permanent Account Number (PAN) card details. To ensure authenticity, the researchers at vpnMentor have uploaded redacted screenshots of these records.
* **Impact of the security lapse:** Such a vulnerability would have impacted millions of ordinary Indians who were on boarded onto these services. In practical terms this has left them susceptible to identity theft, fraud and viral attacks. It may even lead to cases of extortion and phishing for sensitive information. Further levels of vulnerability would be high considering the target populations of CSC belong to semi-urban and rural backgrounds. Shockingly, as the researchers state, the exposed records included those of minors. These risks are escalated due to a lack of proper training, relative lack of user knowledge and further absence of meaningful consent during the onboarding process. As the researchers put it, “_The exposure of BHIM user data is akin to a hacker gaining access to the entire data infrastructure of a bank, along with millions of its users’ account information._**”**

**Can we go beyond bald denials and towards securing public, digital systems?**

{{< figure src="https://internetfreedom.in/content/images/2020/06/Screenshot-2020-06-03-at-3.45.57-AM.png" caption=`"Credit : <a href="https://braindedindia.wordpress.com/about/">Braided Times</a>"` >}}

Some issues emerge from this cyber security incident on which we make specific recommendations:

* **Admission and remedy by CSC:** We were distressed by the official responses which rather than examining the nature of the claims in a meaningful manner, resorted to immediate denials. For instance as reported by MINT in it’s [report dated June 1, 2020](https://www.livemint.com/technology/apps/records-of-bhim-users-allegedly-exposed-but-not-compromised-npci-denies-any-lapse-11591029987582.html), Shri Dinesh Tyagi, CEO of CSC has stated that, “_The claim is incorrect because we never captured Aadhaar data in the entire process_,". Further, the National Payment Corporation of India, stated by a [“Media Statement” dated June 1, 2020](https://www.npci.org.in/sites/default/files/Media-statement-by-NPCI.pdf) on its website that, “_We would like to clarify that there has been no data compromise at BHIM App and request everyone to not fall prey to such speculations._” While we do acknowledge that the security vulnerability does not impact BHIM by itself, it is plainly evident that the vulnerability impacted documents gathered through a referral partner (i.e. CSC) containing sensitive personal information. At the very least this requires a departmental inquiry.
* **Timelines and breach notification by CERT-In:** As per the article CERT-In was first contacted on April 28, 2020 and date of action was May 22, 2020. This is almost a delay of close to two months in ensuring the proper configuration of a AWS S3 bucket of  a seemingly standard configuration. We urge that the reason for it may be examined internally in order to hasten timelines for action and remedy as each moment of vulnerability can be exploited by malicious actors to the vulnerability of lakhs of ordinary Indians. Ideally, on the discovery and closure of the vulnerability a public statement should also follow by CERT-In in addition to a specific notification to each effected person on how it may impact them and what steps they should take to mitigate harm.

### Promote, not only protect our security researchers!

In this context, the directions by the Hon’ble Supreme Court in its decision in Binoy Viswam v. Union of India [2017 _SCC_ OnLine _SC_ 647 at Para 126(iii)] serve as a reminder of the positive obligation to maintain data security when it stated that:

> _“It is also necessary to highlight that a large section of citizens feel concerned about possible data leak….It is important that the aforesaid apprehensions are assuaged by taking proper measures so that confidence is instilled among the public at large that there is no chance of unauthorised leakage of data whether it is done by tightening the operations of the contractors who are given the job of enrollment, they being private persons or by prescribing severe penalties to those who are found guilty of leaking the details….”_

Our broader recommendation is for a comprehensive and focussed push towards improving cyber security by encouraging Indian security researchers. We have anecdotally found that India's elite cybersecurity talent service foreign clients that conduct their work domestically, or towards improving digital, public systems.

A large part of this has to also do with the absence of legal clarity and an absence of a centralised system for bug identification and bounties. Promoting such a system would create the right incentives for growing home-grown talent. Several granular recommendations by us on this subject are contained in our submissions on the [Personal Data Protection Bill](https://internetfreedom.in/essential-features-of-a-rights-respecting-data-protection-law/) as well as the [National Cyber Security Policy](https://internetfreedom.in/security-researchers-need-legislative-protection-from-vexatious-lawsuits/).

### Important Links

1. Representation to the Minister for Electronics and IT dated 03.06.2020 ([link](https://drive.google.com/file/d/1allW8jPt6cb_H6JCZZ4o2AXF-QMNYm3t/view?usp=sharing))
2. Security researchers need legislative protection for responsible disclosure ([link](https://internetfreedom.in/security-researchers-need-legislative-protection-from-vexatious-lawsuits/))
3. Educate and advocate for better privacy protection before the Data Protection JPC ([link](https://internetfreedom.in/educate-and-advocate-for-better-data-protection-saveourprivacy-ins-analysis-of-the-pdp-bill-2019/))
4. Essential Features of a Rights Respecting Data Protection Law #SaveOurPrivacy ([link](https://internetfreedom.in/essential-features-of-a-rights-respecting-data-protection-law/))

<div style="text-align:center;">
    <a href="https://forum.internetfreedom.in/" class="button">Join the Internet Freedom Forum</a>
</div>



