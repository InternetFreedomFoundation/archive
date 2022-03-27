+++
author = 'Rohin Garg'
date = 2021-01-25T05:51:37Z
description = ''
draft = false
slug = 'protect-trans-rights-now'
summary = "Last year, we had received a complaint that the National Portal for Transgender Persons contained several vulnerabilities that could be exploited to access the sensitive personal data contained within. While some of these issues were addressed, certain concerns about the portal's security remain."
title = 'Protect Trans Rights Now! Portal Leakages Must Be Addressed.'

+++


{{< figure src="https://internetfreedom.in/content/images/2021/01/PROTECT-TRANS-RIGHTS-NOW--5.png" >}}

<div style="text-align:center;">
    <a href="https://internetfreedom.in/donate/" class="button">Donate to help sustain our work</a>
</div>

## Tl;dr

Last year, we had received a complaint that the National Portal for Transgender Persons contained several vulnerabilities that could be exploited to access the sensitive personal data contained within the portal. While some of these issues were addressed, certain concerns about the security of the portal still remain.

### The purpose of the portal

On the 25th of November 2020, The Social Justice and Empowerment Ministry launched a national portal for transgender persons to apply for certificates and identity cards. Through the portal – [transgender.dosje.gov.in](http://transgender.dosje.gov.in/) – transgender persons could apply for certificates and identity cards digitally without having to visit any government office and could also monitor the status of their application through the portal itself.

### Security issues emerge

Last year, we were CC'd on an email to the NIC, informing them about certain vulnerabilities in the portal’s architecture. The table below contains a list of the issues and their status.

| Description of Issue                                         | Status                                                                     |
|--------------------------------------------------------------|----------------------------------------------------------------------------|
| Sensitive data can be accessed by changing URL               | Addressed, but could still potentially be accessed                         |
| All hitherto submitted forms can be accessed by changing URL | Addressed, reverse engineering the hash function to gain access once again |
| Unsecure website, does not have HTTPS or SSL certificate     | Still present                                                              |
| Lack of security controls for registration                   | Still present                                                              |



Thus, while some of these issues have been addressed, certain vulnerabilities persist:

* **SSL vulnerabilities:** The portal is not SSL secured which means that all data in the website is not secured and the data can be accessed by hackers. SSL certificate helps to encrypt the data while passing it between web servers and websites. In general sense, the data is locked and can only be unlocked by the intended recipient so that all the sensitive information may be protected. Hence, this is absolutely necessary for a portal that handles information that can be categorised as extremely sensitive in nature. As the portal does not use SSL, there is high possibilities of leakage of personal data of the users of the portal. This makes the portal not secure for handling any information that is of a sensitive nature. This information can be misused and be used for identity theft or even for targeting the already vulnerable transgender individuals.
* **Lack of security controls:** It is very easy to register onto the site by using a fake email id and phone number, and there isn’t any verification done (such as an email verification) to check whether candidates registered are actually legitimate or not. And so, any individual with the help of fake email IDs and phone numbers can create an account in the portal. By creating an account, one can learn the database architecture of the portal and analyse the weaknesses and vulnerabilities, and attack them, thereby enabling them to access data that is available on the portal. If registration continues to happen so easily without strict verification, the personal and sensitive data of all the users registered to the portal are at all times vulnerable to attacks from hackers. Rather than forcing any linking of government IDs in the sign-up process we recommend an inclusionary registration process that is designed in consultation with cyber security professionals.

### Urgent need for privacy

The judgement of the Supreme Court in _National Legal Services Authority v. Union of India_ granted transgender persons legal recognition as the ‘third gender’, and thus affirmed their fundamental rights as guaranteed under the constitution of India. Additionally, the Supreme Court’s judgement in _Justice K. S. Puttaswamy (Retd.) vs Union Of India And Ors._ affirmed the Right to Privacy as fundamental. Given the constitutional recognition of transgender persons, the _Puttaswamy Judgement_, when read along with Articles 14 (Equality before law), 19 (Protection of certain rights regarding freedom of speech), and 21 (Protection of life and personal liberty), thus implies a strong privacy doctrine for the information of transgender individuals as a constitutional obligation, and so the deprivation of the same due to leakages effectvively amounts to a deprivation of fundamental rights.

Furthermore, given prevalent societal mores and norms, the safety of the data of transgender persons is paramount. Much has already been written about [gender and surveillance](https://genderingsurveillance.internetdemocracy.in/theory/), with transgender people facing extremely high levels of both digital and physical threats. These threats, together with deeply ingrained biases and misbeliefs, have already lead to both [focused surveillance](https://scroll.in/article/963693/indias-surveillance-technology-is-policing-the-data-and-bodies-of-its-most-vulnerable-citizens) and physical injury ([or even death](https://www.youthkiawaaz.com/2020/02/violence-against-transgender-persons-the-truth-we-dont-want-to-talk-about-but-we-must/)).

### Recommendations

1. If the issues listed above are not immediately dealt with and resolved, it could lead to data theft which could further lead to financial fraud and identity theft for the users of the portal. Furthermore, applying for certificates through the portal may be a less taxing experience than doing so by physically going to a government office, and so the importance of this portal is clear. Thus, we request swift redressal of the above enlisted issues.
2. Cyber security is a complex process that requires dynamic activities to neutralise emerging threats. To ensure that such issues do not reoccur with the portal, a technical audit of the portal must be conducted. The National Informatics Centre has 33 Empanelled Information Security Auditing Organisations, many of which have conducted significant audits for government agencies such as the NIC, NPCI, and the SBI. Such organisations are technically capable of being tasked with auditing the portal.

If you are unable to discern any other fragilities in the portal's security architecture, please do let us know.

_This representation was drafted with the help of [Rohan Mathew](https://internetfreedom.in/p/707556e3-a187-4433-a86d-a7dc1d9f1a20/rohanmath3w21@gmail.com), a legal and policy intern at IFF._

### Important Documents

1. IFF's Representation to the NIC regarding vulnerabilities in the National Portal for Transgender Persons (**[link](https://drive.google.com/file/d/1UBub9xvQgtsLhhLqABiIfyfy7R1v5uO1/view)**)

