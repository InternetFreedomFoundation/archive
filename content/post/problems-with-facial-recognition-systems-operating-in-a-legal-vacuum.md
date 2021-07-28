+++
author = "Devdutta Mukhopadhyay"
categories = ["Privacy", "Surveillance", "Project Panoptic"]
date = 2020-02-20T12:32:04Z
description = ""
draft = false
image = "https://internetfreedom.in/content/images/2020/02/Copy-of-Facial-Recognition-Twitter-3.png"
slug = "problems-with-facial-recognition-systems-operating-in-a-legal-vacuum"
summary = "While the obvious problem with introduction of facial recognition in India is that a faulty system with a high error rate may be implemented, the implementation of an accurate FRT system also raises serious privacy concerns."
tags = ["Privacy", "Surveillance", "Project Panoptic"]
title = "Problems with Facial Recognition Technology Operating in a Legal Vacuum"

+++


{{< figure src="https://internetfreedom.in/content/images/2020/02/Copy-of-Facial-Recognition-Twitter-3-1.png" >}}

### Tl;dr

Facial Recognition Technology (FRT) is being introduced in India without paying heed to the problems which may arise from its implementation. While the obvious problem is that a faulty system with a high error rate may be implemented, the implementation of an accurate FRT system also raises serious privacy concerns.

### Facial Recognition Technology: Process and Function

To understand the problems associated with FRT implementation, we first need to understand how FRT works. As Smriti Parsheera explains in her [recent paper](http://datagovernance.org/report/adoption-and-regulation-of-facial-recognition-technologies-in-india), the process can be summarised in the following steps:

1. Detection of face in an image and/or video. For instance, phone cameras apply this feature when they auto-focus on a face while capturing a photo.
2. Extraction of particular features from the detected image.
3. Recognition which results in either identification or verification of an individual.

Identification happens when FRT is used to identify an individual from a pool of many people. This kind of 1: many FRT based identification is typically used for security and surveillance purposes. Verification, on the other hand, occurs when an image is compared to another image from an existing database in order to verify that the individual is who he/she claims to be, i.e., authentication of identity on a 1:1 basis.

### Implementation of a Faulty FRT System

Claims relating to accuracy of FRT systems are routinely exaggerated and the real numbers leave much to be desired. For instance, in 2018, Delhi Police [reported](https://theprint.in/opinion/indian-govt-approach-to-facial-recognition-flawed-driven-by-faulty-assumptions/327036/) that its FRT system had an accuracy rate of 2% which fell to 1% in 2019 with the system even failing to accurately distinguish between girls and boys.

The implementation of such faulty FRT systems would lead to high rates of false positives and false negatives in this recognition process.

1. A _false positive_ occurs when FRT gives an incorrect positive result wherein the system misidentifies an individual as someone he/she is not. This may lead to discrimination and strengthening of existing biases. For instance, [ACLU](https://www.aclu.org/blog/privacy-technology/surveillance-technologies/amazons-face-recognition-falsely-matched-28) found that Amazon’s facial recognition software “Rekognition” incorrectly matched 28 members of the US Congress with people who had been arrested for committing a crime. Of those members who were incorrectly matched, 40% were people of color which is a disproportionate number since people of color make up only 20% of the US Congress.
2. A _false negative_ occurs when the FRT gives an incorrect negative result wherein the system is unable to recognize an individual or authenticate his/her identity. This may lead to arbitrary exclusion of an individual from government schemes and benefits. Failure of biometric based authentication under Aadhaar has led to many people being excluded from receiving essential government services and even led to starvation deaths. Such problems will be further aggravated by an inaccurate FRT system.

In India, FRT systems are being developed and deployed by government and private entities without any technical standards in place which may lead faulty systems being implemented (Read more about these FRT projects [here](https://internetfreedom.in/facial-recognition-in-india-part-i/)). Once in place, it would be very difficult for them to be reconciled with future technical standards and  damage like discrimination and exclusion would be impossible to undo.

### Implementation of an Accurate FRT System

While there have been [claims](https://swr.indianrailways.gov.in/view_detail.jsp?lang=0&dcd=3370&id=0,4,268) of a fully accurate FRT system, none of these claims have been corroborated by independent review and audit. The National Institute of Standards and Technology (NIST) has extensively tested FRT systems for [1:1 verification](https://www.nist.gov/system/files/documents/2019/11/20/frvt_report_2019_11_19_0.pdf) and [1:many identification](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8271.pdf) and how accuracy of these systems [vary across demographic groups](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf)**.** These independent studies have concluded that currently, no FRT system has 100% accuracy.

An accurate FRT system would _hypothetically_ have a 100% success rate in 1:1 verification and/or 1:many identification. However, it will come with its own ominous connotations, the most problematic of which may be state led mass surveillance and difficulty for outside actors to counter-challenge government decisions.

1. _**Lack of Informed Consent**_Probe images for FRT systems are often collected by the police through CCTV cameras installed in public spaces. Individuals in a CCTV surveilled area may be aware that they are under surveillance but the assumption is that this surveillance is temporary. Use of CCTV in conjunction with FRT would mean their images will be stored for a longer period of time, if not permanently. This data will also be used to extract particular data points such as the facial features and other biometrics which the individual has not consented to sharing when entering a CCTV surveilled zone and these data points can be used to track future movements of the person. Therefore, integration of FRT with a network of CCTV cameras would make real time surveillance extremely easy.Even if individuals do consent to their images being processed by an FRT system, is this consent informed? For example, the Digi Yatra Program introduced in various airports is touted to be a voluntary initiative and has a [policy](https://www.civilaviation.gov.in/sites/default/files/Digi%20Yatra%20Policy%2009%20Aug%2018.pdf) which assures passengers that “personal data shall be obtained only for the specified lawful purpose, and shall not be further processed in any manner other than for that purpose or those purposes.” However, the same policy also contains an exception which allows sharing of passenger data with “any Security Agency, Bureau of Immigration(BOI) or other Govt. Agency” based on existing protocols. Individuals who have consented to having their information processed under Digi Yatra may often be unaware of this exception.
2. _**Lack of legislation containing mandatory safeguards**_Deployment of FRT at national and state levels without adequate legal safeguards is deeply troubling. Specific laws with regard to FRT and personal data protection do not currently exist in India. While a flawed Personal Data Protection Bill has been introduced in the Parliament (read more [here](https://internetfreedom.in/its-the-final-countdown-kinda-saveourprivacy/)), there is uncertainty about when it will be enacted and implemented and how effective it will be in protecting the personal data of individuals. Under the current version of the Bill, wide exceptions have been provided to the Government for surveillance related activities. A strong data protection legislation is needed to hold these FRT systems accountable in terms of collection, storage and usage of data including sharing of data across government agencies and with third parties. 
3. _**Violation of Fundamental Rights**_ The implementation of an accurate FRT system would also violate fundamental rights by facilitating mass surveillance. For instance, there will be a chilling effect on the right to freedom of speech and expression because people will be wary of being prosecuted in case they express anti-government sentiments. Further, the right to freedom of movement would be hampered as mass surveillance would allow the government to track the movements of individuals in real time across the country. Finally, the right to privacy will be violated as  sensitive personal data which is collected by these FRT systems will be used by the Government without the informed consent of the individual. This would also hamper the individual from exercising the liberty to share their information in some contexts and remain anonymous in others according to their individual choice.

In conclusion, implementation of FRT systems in India has the potential of turning the country into a surveillance state. The problems that arise would not only affect the fundamental rights and civil liberties of individuals but also create mistrust towards any positive initiatives that the Government might undertake if no legal safeguards and best practices are put in place. 

_(This blogpost has been authored by Anushka Jain, a legal intern at IFF, and reviewed by IFF staffers, Devdutta and Sidharth.)_

### Important Documents

1. Introduction to Facial Recognition Projects in India ([link](https://internetfreedom.in/facial-recognition-in-india-part-i/))

### “I solemnly swear that I am up to no good.” - Indian Govt, Circa 2020. Help IFF prevent the Government from getting its own Marauder's Map by [becoming a member today](https://internetfreedom.in/donate/)!



