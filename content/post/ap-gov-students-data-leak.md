+++
author = 'Tejasi Panjiar'
categories = ['Data Breach', 'Privacy', 'CERT-In', 'SaveOurPrivacy']
date = 2022-02-04T14:02:56Z
description = ''
draft = false
slug = 'ap-gov-students-data-leak'
tags = ['Data Breach', 'Privacy', 'CERT-In', 'SaveOurPrivacy']
title = 'Student data exposed on Andhra Pradesh Government Examination website!'

+++


{{< gallery >}}
{{< galleryImg  src="https://internetfreedom.in/content/images/2022/02/Andhra-Students-Data-leak---3-.png" width="1600" height="900" >}}{{< /gallery >}}

>>>> <form><script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_HLkgeWGQLMuddp" async> </script> </form>

**tl;dr**

Sai Sravan Prabhala, a cyber-security researcher, informed us of a critical vulnerability exposing the sensitive personal information of minors. This existed on the website of the Directorate of Government Examinations, Government of Andhra Pradesh’s for the 2021 examinations. While this functionality itself has been removed, to prevent it from occurring again assisted by Sai, we have written to them and CERT-In.



**Background**

On 22nd December 2021, cyber-security researcher Sai Sravan Prabhala reached out to us, to bring to our notice a vulnerability in the Andhra Pradesh Directorate of Government Examination website which put the sensitive personal information of minors at risk of misuse. The Directorate of Government Examinations is an independent department functioning under the ministry of secondary education, Government of Andhra Pradesh. The department is responsible for conducting the SSC/OSSC Public Examinations, along with other minor examinations.

With the assistance of Mr. Prabhala, we discovered that the website of the Directorate of Government Examinations, Government Andhra Pradesh, which can be accessed at: [https://www.bse.ap.gov.in/](https://www.bse.ap.gov.in/), suffered from a vulnerability that enabled any person to access and also edit the sensitive personal data of minors including their caste location, religious affiliation, and their disability status. Their phone number and identification marks as per school records could also be edited and accessed on the said website.

The vulnerability could be discovered by clicking on the link: “[_SSC Public Examinations - 2021 - Edit Online Application_](https://www.bse.ap.gov.in/aponlineadm/Account/Login.aspx)”. This led to a login page, which could be accessed by entering the school number in both the “User ID” and “Password fields”. The school number could be obtained by clicking on the “[_SSC Public Examinations 2020 and 2021 Results_](https://www.bse.ap.gov.in/SscResult.htm)” link and then going to the “[_Individual Student Wise Results of SSC Public Examinations 2021_](https://www.bse.ap.gov.in/sscresult21/APSSCRESULTWITHOUTHTNO21.aspx)” page where a drop-down menu in the “school” field revealed a list of schools along with their school numbers. A more detailed list of steps along with screenshots explaining how the vulnerability is discovered can be found in our [representation](https://drive.google.com/file/d/1nxBjeNTcbtfFh6t9Rp254pw1h8JwrGTM/view?usp=sharing) dated 02.02.2022.

Following the above-mentioned steps led to a page that revealed the sensitive personal information of the students, which could also be edited by anyone.

{{< figure src="https://lh3.googleusercontent.com/xMGPxQA_KqAiiNnRzdSeDAgKDjrcIy4-nSAXGJ_H8bCuEzDaEpvkb5LzUgHC-l08MP_kmT0IhPnnzS6AjzktCme2Ri0j7uTGy0EvnwdbfeFcKrcYt2VI2GOTLFiJH0NAW3sKMJbf" >}}



{{< figure src="https://lh3.googleusercontent.com/i1xoS_eFVD21ibocUMZiD-HEfF-yc_JeRq-wchng3z4-12Xa9okj8G-g2fZZ91R0W1RaNbbq4A_K3LMJg5IOZrZVm4r3feDMnXdSdNHdvQ7VKRORbVbq6nPYA3POT0tdwXN_pdcO" >}}



We were first apprised of the vulnerability on 22nd December 2021, thereafter, on 23rd January 2022, we noticed that the vulnerability has been removed from the website. In the meantime, the vulnerability was active and it enabled anyone to access and edit sensitive personal information of minors.



**Legal Consequences of the Vulnerability**

This vulnerability violates the students’ fundamental right to privacy, as upheld by the Supreme Court in _K.S. Puttaswamy v. Union of India_ (2019) 1 SCC 1. Significantly, the decision [highlighted](https://main.sci.gov.in/supremecourt/2012/35071/35071_2012_Judgement_24-Aug-2017.pdf#page=530) the need to secure children’s right to privacy, bearing in mind that minors lack the legal capacity to give consent. Additionally, the Government of India has ratified the [United Nations Convention on the Rights of the Child](http://164.100.86.208/NCPCR.pdf#page=9) (UNCRC). As a result, India endeavours to protect children from all forms of exploitation and arbitrary or unlawful interference with their privacy. Hence, if necessary measures are not taken to protect the personal information of children, it would stand in violation of the _Puttaswamy_ decision, and the UNCRC.

The information exposed by the above-mentioned vulnerability – such as “_caste or tribe_” and ”_religious affiliation_” – has been categorised as “_sensitive personal data”_ under the proposed [Personal Data Protection bill, 2019](http://164.100.47.4/BillsTexts/LSBillTexts/Asintroduced/373_2019_LS_Eng.pdf#page=9) (“2019 bill”) as well as the [Draft Data Protection bill 2021](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Data%20Protection%20Bill,%202019/17_Joint_Committee_on_the_Personal_Data_Protection_Bill_2019_1.pdf#page=481) (“2021 bill”), for which the Data Protection Authority is empowered to specify additional regulations, safeguards or restrictions. [Clause 24](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Data%20Protection%20Bill,%202019/17_Joint_Committee_on_the_Personal_Data_Protection_Bill_2019_1.pdf#page=496) of the bill requires data fiduciaries to implement necessary security safeguards including “ _steps necessary to prevent misuse, unauthorised access to, modification, disclosure or destruction of personal data_”. Neglecting to do so can result in a [penalty](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Data%20Protection%20Bill,%202019/17_Joint_Committee_on_the_Personal_Data_Protection_Bill_2019_1.pdf#page=519) not exceeding five crore rupees or two percent of the fiduciaries worldwide turnover of the preceding financial year, whichever is higher. Further, the vulnerability causes significant “_harm_” - as defined under [Clause 3(23)](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Data%20Protection%20Bill,%202019/17_Joint_Committee_on_the_Personal_Data_Protection_Bill_2019_1.pdf#page=478) of the Draft Data Protection bill, 2021 -  to those affected as anyone can edit their personal details which can lead to “_loss, distortion or theft of identity_”, “_humiliation_”, and “_observation or surveillance that is not reasonably expected_”.

Currently, in the absence of an overarching data protection legislation, according to [Section 72A](https://indiankanoon.org/doc/69360334/) of the Act, the websites, school managements, and individuals involved in the mass student data breach can be imprisoned for a term of up to three years or/and can be fined up to five lakh rupees.



**Children’s Right to Privacy hangs in the balance**

This is not the first time children’s privacy has been put at risk. Previously, [Ukhrul Times](https://ukhrultimes.com/nagaland-bihar-haryana-students-personal-database-on-sale-on-amazon-serious-data-breach/), [Nagaland Express](https://nagalandexpress.com/nagaland/nagaland-students-database-available-for-sale-in-amazon-parents-raise-concern/), and [India Times](https://www.indiatimes.com/technology/news/indian-students-data-selling-online-scam-543039.html) broke the news of a pan-India personal data breach of Class X and Class XII students in which their names, father’s names, physical addresses, institution names, and even contact details including phone numbers and email addresses were found in various databases which were being sold on the internet, including on Amazon. Pursuant to this, we [wrote](https://internetfreedom.in/securing-examination-data-no-childs-play-untitled/) to twenty-eight State Commissions for the Protection of Child Rights and four Union Territory Commissions for the Protection of Child Rights to raise our grievances. We urged the Commissions to initiate an inquiry on the infringing websites and the e-commerce platform (Amazon) and to also forward the case to the Magistrate having the jurisdiction to hear the complaint. The Commissions were also advised to frame and implement remedial measures and guidelines to prevent the leakage of students’ personal data henceforth.

The commercialisation of [students’ personal information](https://timesofindia.indiatimes.com/blogs/voices/need-for-data-protection-framework-for-edtech-sector/) can be attributed to the exponential growth of ed-tech and remote education amidst the COVID-19 pandemic. Presently, the IT Act and the Rules framed thereunder do not provide for any special regulation for the collection and processing of children’s data. Better practices exist that ought to be implemented. Globally, the EU’s GDPR [specifies](https://gdpr-info.eu/art-8-gdpr/) that children’s data can only be collected and processed with parental consent. In the US, the [Children's Online Privacy Protection Act of 1998](https://www.ftc.gov/enforcement/rules/rulemaking-regulatory-reform-proceedings/childrens-online-privacy-protection-rule) regulates the collection of personal information from children under 13 years of age including children outside the US.

The [2019](http://164.100.47.4/BillsTexts/LSBillTexts/Asintroduced/373_2019_LS_Eng.pdf) and [2021](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Dat) Data Protection Bill, in [Chapter IV](http://164.100.47.193/lsscommittee/Joint%20Committee%20on%20the%20Personal%20Data%20Protection%20Bill,%202019/17_Joint_Committee_on_the_Personal_Data_Protection_Bill_2019_1.pdf#page=489), lay down provisions to protect the personal data of children. The proposed Data Protection Authority is empowered to create regulations to specify the manner in which the age of children is verified and the consent of parents or guardians is obtained before processing the personal data of children. It is also empowered to classify fiduciaries that operate websites directed at children or process large volumes of personal data of children as guardian data fiduciaries which shall be barred from profiling, tracking, monitoring, targeted advertising, or undertaking any processing of personal data that causes significant harm to the child.



**Conclusion**

In our representation, we urged the Directorate of Government Examinations to ensure that the vulnerability does not arise in the future and implement policies for public reporting of data breaches or vulnerabilities. We further suggested that such policy can be modeled after the Indian Computer Emergency Response Team’s (CERT-IN) ‘[Responsible Vulnerability Disclosure and Coordination Policy](https://www.cert-in.org.in/RVDCP.jsp)’, which is [far from perfect](https://internetfreedom.in/over-to-you-meity/) but is a step in the right direction. A Bug Bounty programme may also be implemented to recognise and incentivise researchers to report vulnerabilities.

Children’s privacy, however, will continue to hang in the balance unless a consent-based privacy framework as noted above is implemented.

_We acknowledge and thank Mr. Sai Sravan Prabhala for his assistance. He can be reached at:_ [_saiprabhala96@gmail.com_](mailto:saiprabhala96@gmail.com)_._



**Important Links**

1. IFF’s representation to the Directorate of Government Examinations, Andhra Pradesh dated 2nd February 2022 ([link](https://drive.google.com/file/d/1nxBjeNTcbtfFh6t9Rp254pw1h8JwrGTM/view?usp=sharing)).
2. Securing Examination Data: No Child’s Play dated 26th July 2021 ([link](https://internetfreedom.in/securing-examination-data-no-childs-play-untitled/)).#PrivacyOfThePeople - Why Student Data should be Students’ Data dated 22nd July 2021 ([link](https://internetfreedom.in/why-student-data-should-be-students-data/)).

_Note: This blogpost was drafted by IFF intern Simrandeep Singh and reviewed by Tejasi Panjiar, Capstone Fellow hosted at IFF._

> > > <form><script src="https://cdn.razorpay.com/static/widget/subscription-button.js" data-subscription_button_id="pl_HLk5qU1K35hmPH" data-button_theme="brand-color" async> </script> </form>



