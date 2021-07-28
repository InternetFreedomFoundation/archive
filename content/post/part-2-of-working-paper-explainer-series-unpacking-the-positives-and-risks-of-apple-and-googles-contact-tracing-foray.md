+++
author = "Sidharth Deb"
categories = ["big tech", "competition", "IFFresearch", "Surveillance", "SaveOurPrivacy", "Privacy", "Policy", "innovation", "Covid"]
date = 2020-04-17T12:01:38Z
description = ""
draft = false
slug = "part-2-of-working-paper-explainer-series-unpacking-the-positives-and-risks-of-apple-and-googles-contact-tracing-foray"
summary = "IFF’s Working Paper on Privacy Prescriptions for Technology Interventions on COVID-19 in India, affords significant space to the issue of contact tracing technologies. It offers a preliminary breakdown of the Apple and Google's proposed partnership to provide a digital contact tracing solution."
tags = ["big tech", "competition", "IFFresearch", "Surveillance", "SaveOurPrivacy", "Privacy", "Policy", "innovation", "Covid"]
title = "Unpacking the positives and risks of Apple and Google’s contact tracing foray #SaveOurPrivacy"

+++


{{< figure src="https://internetfreedom.in/content/images/2020/04/Apple-and-Google-are-bringing-their-own-contact-tracing-solution--1-.png" >}}

### Tl; dr

IFF’s Working Paper on [_Privacy Prescriptions for Technology Interventions on COVID-19 in India_](https://drive.google.com/file/d/1UK5rElhcdP5T3Y-8fYP6cCgQKKpQBeOX/view), affords significant space to the issue of contact tracing technologies. In Chapter 8 it offers a preliminary breakdown of the recently announced partnership between Apple and Google to provide a digital contact tracing solution. In this post we provide some insights into our working paper’s analysis of the partnership through the lens of what’s good, possible risks and the project’s relevance for India. For more texture, please read our working paper, and feel free to provide us with feedback on how we can improve our findings.

### Background | The Promise of Scale and Privacy

Even as the Aarogya Setu application [crosses the 50 million download mark](https://theprint.in/tech/aarogya-setu-is-fastest-app-in-the-world-to-reach-50-million-users-despite-privacy-concerns/403025/), there is another project which people should take notice of. On April 10, 2020 Apple and Google [announced](https://www.apple.com/in/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/) a partnership where they will collaborate on an interoperable contact tracing partnership. Considering they are the world’s two largest operating system (OS) providers for smartphones, they have the scale to potentially offer these facilities to in excess of 3 billion users globally.

The companies are positioning the system as a voluntary opt in system. It will be designed to notify users if they have come in contact with an infected individual. Subsequently, it will offer users recommended courses of action which may range from quarantine to self isolation.

This development essentially reflects earlier recommendations of technologists and stakeholders. Since these are pre existing infrastructures, stakeholders suggest that it may be a viable alternative to creating new surveillance systems installed and monitored by government.

In particular OS providers have been viewed as a promising alternative since these parties have considerable experience in deploying privacy-preserving technologies like differential privacy or homomorphic encryption.

### Proposed Timelines

Demonstrating the long term nature of the global response to COVID-19, and the way contact tracing systems are increasingly linked with the reopening of future economic activities, the plan is to introduce the system in two phases.

1. In **Phase 1** (to commence in **May, 2020**) public health authorities will be given the capability to run apps in which iPhones and Android phones will be able exchange information anonymously with one another. The design will allow users of the public health app to voluntarily notify the system if they test positive for COVID-19. Then users which were in close proximity in the last few days will be notified that such contact was made. The default timeline for this check will be 14 days. However, health authorities will have the discretion to amend this.
2. **Phase 2** will be administered over the course of a few months. This update to the programme will essentially reflect the recommendations discussed earlier. The contact tracing software will be embedded into the operating system itself, which removes the need for users to download an application. This functionality will also be opt-in but the potential for this solution to scale is enormous and brings with its own set of opportunities and risks.

### The Project Emphasises Individual Privacy

To reassure people on privacy, Google and Apple stressed on the fact that consent will be baked into its design and they will not collect location data. To their credit, after the publication of our working paper the two parties have [announced](https://www.cnet.com/news/apple-and-google-say-they-will-shut-down-covid-19-tracking-tools-once-pandemic-ends/) that they intend to terminate the systems once the COVID-19 pandemic ends. While this is a good step, given the uncertain nature of timelines in relation to the coronavirus there is a need for greater specificity and transparency on this front, and is not enough to allay concerns of permanence.

Coming to technical aspects of the project, it stresses that users will not be informed whom they came in contact with, or where the contact takes place. The companies will also not be able to access this data and the entire system can be shut down, if required.  Similar to Singapore’s _TraceTogether_ application and other global projects discussed in IFF’s Working Paper the proposed project will be based on Bluetooth. Once contact is established, devices exchange anonymous device identifiers (which are updated for every user’s device on a daily basis), which confirm a timestamped interaction. To enhance people’s privacy, anonymous digital identifiers will change roughly every fifteen minutes. The [inconsistency](https://internetfreedom.in/is-aarogya-setu-privacy-first-nope-but-it-could-be-if-the-government-wanted/) with the Aarogya Setu app’s own efforts at privacy protections, data minimisation and obfuscation is apparent.

Should an individual test positive for COVID-19, the person has the ability to enter their diagnosis into a corresponding app which is designed for health agencies. This application then must seek the consent of users to export their “close proximity” interactions which have been recorded in the days prior to diagnosis. This data which has been exported is stored temporarily in a remote server for 14 days. Again here it shows the level of agency and control being afforded to people and their personal data. Indeed, this ethos has even been reflected in other promising contact tracing models studied by our Working Paper.

When it comes to the devices of the people who have made contact with this diagnosed person, the process flow is as follows. First the phone will check the server periodically to assess if any of its identifier keys are linked with COVID-19 positive cases. All positive keys are downloaded back on to this individual’s phone and matched anonymously for validation purposes. When matched, a notification is sent to the other person’s phone along with suggestions from health agencies on how they can quarantine and self-isolate.

The project aims to create a common standard of interaction between different technologists and public health authorities across the world. The two firms state that privacy, transparency and consent will be underlying pillars of this project. The actual solution will also be informed by the inputs of other stakeholders. To further transparency, they have published specifications for Bluetooth, cryptography (i.e. encryption) and API frameworks. As of now information on accountability mechanisms remains difficult to discern.

### Risks Arising from the Project

One of the large outcomes of the coronavirus’ impact in relation to people’s increased dependence on information and communication technologies provided by big tech companies. Considering the fact that contact tracing solutions require the processing of highly sensitive personal information including health records, and insights on people’s movements and/or interpersonal communications, there is an added layer of complexity when these systems are managed by private sector behemoths. It is imperative that any private sector driven response to digital contact tracing must adequately tackle issues of transparency, consent, purpose limitation, and corporate objectives.

When private actors are entrusted for such projects, there is a need to engender public trust. Name recognition and brand of course, help with this trust, but trust also covers facets like safety, privacy and reliability. At a minimum these businesses must also have to comply on principles of (1) specific limited purpose, where there is a specified end data and a defined outcome to the project; (2) complete transparency; and (3) strong enforcement mechanisms which can hold these businesses accountable and protect people’s fundamental rights to informational privacy.

Stringent checks and balances are important to consider, since the creation of new systems, even if they are characterised as temporary, are difficult to roll back. Aside from these general risks, when analysing the project announced by Apple and Google, we must stay vigilant in a few distinct ways.

* ******Negotiating Government Use of Personal Data**:**** The project discusses a system wherein once users of the application are diagnosed with the novel coronavirus, they can export their records from the prior few days on to an external server. This external server allows public health officials to access relevant records. Since, this means health departments in governments are granted access to people’s personal data, there is an onus to ensure use limitations.  Under the guise of contact tracing, health authorities should not be allowed to share such information and insights towards civil liberty restrictions. For example, Apple and Google will have to update the public on how its systems can and cannot be used by governments.
* ******Issues of Competition and Conflict of Interest**:**** Competition authorities and policymakers must carefully scrutinise this project, in an ex-ante manner. This is because it may severely deter competition and innovation in a crucial area of urgent public interest. There is a need to consider conflicts of interest at two levels. In the project’s first phase, Apple and Google will be competing with other applications developed by other groups, companies, consortiums, researchers, and governments. In this context, there is a need for oversight on how _App Store_ and _Play Store_ treats its application(s) in comparison to other similar solutions.  Second, as the project evolves and integrates itself into the operating system, we need to evaluate what it will mean for innovation in the space. Does the project envision a means to be interoperable with other operating system providers in smartphone and feature phone markets. Such systems should not leave us in a paradigm with one digital contact tracing solution where large technology firms and governments have unimpeachable control over the system. To mitigate such risks, there may be an overriding need to administer ex-ante impact assessments-- both economic and rights oriented.
* ******Should Such Projects Be Administered by Pureplay Corporate Structures**:**** At a fundamental level, it is also important to consider the validity of such projects being administered in a purely corporate structure. Considering the overarching public interest in global responses to COVID-19 and the human rights implications of contact tracing, should these solutions and the supporting infrastructures, be categorised as public digital infrastructures? Instead, should there be regulated access to public-private models? Or should it merely be regulated opportunities for private actors to participate? While the model remains unknown, there is a need to have an expedited conversation on this front.

### Relevance for India and What’s Next?

It is important to highlight that India’s Ministry of Electronics and Information Technology (MeitY) is undertaking a consultation which is relevant to this issue. In particular under May 31, 2020 stakeholders may submit suggestions to a white paper toward a national strategy on National Open Digital Ecosystems. IFF’s submission will address the whitepaper/consultation’s interlinkages with such conversations in its substantive response.

Based on public feedback, IFF intends to update its findings and recommendations to its working paper and share it directly with stakeholders involved in crucial decision making processes.

### Links to IFF’s COVID-19 Related Work

1. Working paper "Privacy prescriptions for technology interventions around Covid-19 in India"  dated April 13, 2020 ([**Google Docs version**](https://docs.google.com/document/d/1nDoPzygQyTetEguOlzula5O9y5f3f5YJDsA2Pd99O6U/edit?usp=sharing) / [**PDF Version**](https://drive.google.com/file/d/1UK5rElhcdP5T3Y-8fYP6cCgQKKpQBeOX/view?usp=sharing))
2. Link to IFF’s first explainer blog post summarising the working paper’s analysis of India’s Aarogya Setu app ([**link**](https://internetfreedom.in/is-aarogya-setu-privacy-first-nope-but-it-could-be-if-the-government-wanted/))
3. Representation to the Department for Telecom on ensuring connectivity and protecting net neutrality due to higher dependency on telecom networks ([**link**](https://internetfreedom.in/urgent-steps-to-be-taken-by-the-department-of-telecom-due-to-the-covid/))
4. Representation to the Ministry of Health to issue an advisory against the disclosure of the names of persons placed under quarantine ([**link**](https://internetfreedom.in/quarantine-list/))
5. Petition before the Supreme Court to restore 4G connectivity in Jammu and Kashmir to properly equip healthcare professional around Covid-19 ([**link**](https://internetfreedom.in/sc-issues-notice-in-fmps-petition-seeking-restoration-of-4g-internet-services-in-jammu-kashmir-during-covid-19-crisis/))

[_**The Corona virus is not only a threat to our health. We need your help now more than ever to protect your digital rights and ensure technology responses to COVID-19 work toward your interests. Please donate to IFF today and become a member**_](https://internetfreedom.in/donate/).

**[Please Join in the Conversation at the Internet Freedom Forum as well.](https://forum.internetfreedom.in/)**

