+++
author = "Anushka Jain"
categories = ["Surveillance", "pegasus", "Privacy", "Arsenal", "BhimaKoregaon"]
date = 2021-08-12T07:10:24Z
description = ""
draft = false
image = "https://internetfreedom.in/content/images/2021/08/Bhima-Koregaon-Twitter-Post-1.png"
slug = "the-arsenal-reports-bhima-koregaon-arrests"
summary = "The reports by Arsenal Consulting show that  some of the BK-16 were surveilled and incriminating documents planted on their computers. We analyse what this means for the rise of targeted surveillance in India in light of the recent Pegasus revelations. "
tags = ["Surveillance", "pegasus", "Privacy", "Arsenal", "BhimaKoregaon"]
title = "The Arsenal Reports: The rise of targeted surveillance in India"

+++


{{< gallery >}}
{{< galleryImg  src="https://internetfreedom.in/content/images/2021/08/Bhima-Koregaon-Twitter-Post.png" width="1600" height="900" >}}{{< /gallery >}}

>>>> <form><script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_HLkgeWGQLMuddp" async> </script> </form>

### tl;dr

Reports by a digital forensics consulting company named Arsenal Consulting reveal that malware was used to surveil and plant evidence on the computers of two of the accused in the Bhima Koregaon case. In this post, we look at these reports closely to provide an informed basis for commentary on digital evidence, forensics, and ongoing conversations on the use of malware such as Pegasus.

### What is the Bhima Koregaon case?

The Bhima Koregaon case relates to the violence that took place on January 1, 2018 at the annual celebrations held in its namesake village to commemorate the Battle of Bhima Koregaon in which the predominantly Dalit British army defeated the Peshwa army, led by Peshwa Bajirao II. However, the celebrations taking place in 2018 were larger than usual to mark the 200th anniversary of the battle. [Tensions in the area had started simmering on December 29, 2017, the day Govind Gopal Mahar's memorial was found desecrated](https://www.business-standard.com/about/what-is-bhima-koregaon-case) as a result of ongoing issues between the Dalit and Maratha communities in the region. The incident found mention in the Elgar Parishad, a big public conference organised by Dalit and Bahujan groups on December 31, 2017. As a result, on January 1, the historically peaceful event turned violent which led to one person from the Maratha community being killed and several others being injured. A few months later, however, the police suddenly claimed the violence was provoked by activists and human rights lawyers, some of whom had attended the Elgar Parishad programme.

The activists and human rights lawyers who were arrested by the Police in connection to case are collectively referred to as the BK-16 and include: academics Anand Teltumbde, Shoma Sen and Hany Babu; Adivasi rights activists Stan Swamy and Mahesh Raut; poets Varavara Rao and Sudhir Dhawale; lawyers Surendra Gadling and Sudha Bharadwaj; writer-researcher Gautam Navlakha, activists Rona Wilson, Arun Ferreira and Vernon Gonsalves, and members of the cultural group, Kabir Kala Manch: Sagar Gorkhe, Ramesh Ghaichor and Jyoti Jagtap.

### How does it link to the Arsenal reports?

In spite of the court’s refusal to issue a search warrant, the [Pune police on April 17, 2018](https://www.newslaundry.com/2021/01/02/bhima-koregaon-case-three-years-of-legal-and-rights-violations), raided the Nagpur house of lawyer Surendra Gadling and the Delhi and Mumbai residences, respectively, of activists Rona Wilson and Sudhir Dhawle and confiscated their computers, hard drives, portable drives, personal DVDs of wedding and birthday parties. In the computer seized from Wilson, the police alleged to have [found files which included details about purported meetings of Maoist militants, alleged correspondence with Maoist leaders, and money received by the Communist Party of India (Maoist)](https://scroll.in/latest/999459/bhima-koregaon-evidence-was-planted-on-advocate-surendra-gadlings-computer-says-report) as well as letters detailing a plot to assassinate Prime Minister Narendra Modi.

In this post, we will be analysing the findings of [reports](https://drive.google.com/drive/folders/1QoonWsBbpWiJFaIl2zgLN6l0rxezNHHa?usp=sharing) submitted to the Court of the Special Judge notified under National Investigation Agency Act by [Arsenal Consulting](https://arsenalexperts.com/), which is a digital forensics consulting company founded in 2009, that analysed the electronic evidence seized from Rona Wilson and Surendra Gadling.

### What did the reports reveal?

The reports relate specifically to two of the accused, Rona Wilson (Reports [1](https://drive.google.com/file/d/1pM4XsoEPtUn-UCxMer0zO0L246i0fk_V/view?usp=sharing) & [2](https://drive.google.com/file/d/1_X8DYigIuIlbTSaK0fHRzQjhy9sNsr8I/view?usp=sharing)) and Surendra Gadling (Report [3](https://drive.google.com/file/d/1fXyg2gbU-kPrhzZseF5lXvPRRGXvpDnh/view?usp=sharing)). While the reports themselves are fairly technical, below we have distilled the crux of the reports which is helpful for our analysis.

1. According to the reports, both Rona Wilson’s and Surendra Gadling’s computers  were compromised for 22 and 20 months respectively.
2. The ​​primary goals of the attacker were surveillance and incriminating document delivery.
3. Arsenal has connected the same attacker to a significant malware infrastructure which has been deployed over the course of approximately four years to attack the co-defendants in the Bhima Koregaon case and defendants in other high-profile Indian cases as well.
4. The attack was carried out through NetWire, which is a commercially available malware. [It is a remote access trojan, or RAT, which gives control of the infected system to an attacker](https://www.thehindu.com/sci-tech/technology/the-hindu-explains-bhima-koregaon-violence-case-what-has-arsenal-consulting-found-about-an-attacker-using-a-malware-to-infiltrate-a-laptop/article33831896.ece).
5. Arsenal developed internal tools during the course of their analysis which allowed them to search for and decrypt NetWire logs anywhere on Mr. Wilson’s computer. NetWire logs are files used for surveillance purposes and contain keystrokes and other information related to the victim. Arsenal was able to recover a combination of complete and partial NetWire logs from 57 particular days between late 2016 and April 17, 2018, the day Mr. Wilson’s computer was seized by the Pune police. The activity captured in these logs included Mr. Wilson browsing websites, submitting passwords, composing emails, and editing documents.
6. Arsenal has found no evidence which would suggest that the top ten most important documents used in the prosecution against Mr. Wilson (“the top ten documents”) were ever interacted with in any legitimate way on Mr. Wilson’s computer. Arsenal has found no evidence which would suggest that any of the additional files of interest were ever interacted with in any legitimate way on Mr. Wilson’s computer, and can confirm that 22 of the 24 files were delivered to a hidden folder on Mr. Wilson’s computer by NetWire and not by other means.
7. More particularly, there is no evidence which would suggest any of the top ten documents, or the hidden folder they were contained in, were ever opened. One method that can be used to assist in determining whether a particular document has ever been opened on a particular computer is to review the NTFS file system’s “object identifier” (a/k/a $OBJECT_ID) attributes for that document. Object identifiers are normally assigned to documents when they are either created or first opened. In this case, none of the top ten documents have object identifiers.
8. Arsenal found and decrypted partial NetWire logs from Mr. Gadling’s computer which covered 55 particular days between March 5, 2016 and October 22, 2017. Arsenal has found no evidence which would suggest that the 14 important documents were ever interacted with in any legitimate way on Mr. Gadling’s computer, either in their original location on the tertiary volume or in their current location on the Windows volume.
9. Arsenal, in their report, has indicated that this is one of the most serious cases involving evidence tampering that they have ever encountered, based on various metrics which include the vast timespan between the delivery of the first and last incriminating documents ​​on multiple defendants’ computers.

### Are Indian investigation agencies and laws equipped to handle such surveillance attacks?

While alarming on their own, these revelations about people associated with the BK-16 case being surveilled are [not new](https://internetfreedom.in/statement-scary-disclosures-on-use-of-nso-spyware-in-india-signal-a-need-for-urgent-remedy/). [Reports, going as far back as 2019, revealed](https://www.huffpost.com/archive/in/entry/whatsapp-hacking-bhima-koregaon-lawyers-targeted_in_5dba8e9ae4b066da552c5028) that NSO Group’s spyware Pegasus, which has been [in the news recently](https://thewire.in/government/project-pegasus-journalists-ministers-activists-phones-spying) as well, was used on the [lawyers representing some of the BK-16](https://www.huffpost.com/archive/in/entry/whatsapp-hacking-bhima-koregaon-lawyers-targeted_in_5dba8e9ae4b066da552c5028) according to the University of Toronto’s [Citizen Lab](https://citizenlab.ca/2020/06/citizen-lab-amnesty-international-uncover-spyware-operation-against-indian-human-rights-defenders/). Thus, it is important to not only look at this case in light of the facts uncovered related to digital surveillance, but also to understand whether Indian citizens are protected under the current legal framework against such attacks.

As has become clear, NetWire and Pegasus were used in the BK-16 case to surveil the accused and individuals related to them, such as [Nihalsing Rathod](https://www.huffpost.com/archive/in/entry/whatsapp-hacking-bhima-koregaon-lawyers-targeted_in_5dba8e9ae4b066da552c5028) who represents Mr. Gadling, as well as to plant incriminating evidence. In this situation, it is important for us to know whether Indian investigation agencies, such as the NIA which is in charge of the BK-16 investigation, are cognisant of this new functionality that has been developed and whether they are equipped to uncover it so as to not be misled. The reports from Arsenal Consulting, which have led to the present revelations, were commissioned by the defence, and we do not know whether the NIA has conducted its own independent investigation in light of the reports. Currently, all that the NIA has said about these reports is that they [could be taken up during the trial but they could not be a ground for seeking quashing of the chargesheet](https://www.thehindu.com/news/national/wilson-cant-rely-on-arsenal-report-seeking-to-quash-chargesheet-nia/article35734532.ece) against Rona Wilson.

Such hacking of computer resources, including mobile phones and applications, is a criminal offence under the Information Technology Act, 2000 and it is only through such hacking that the NetWire or Pegasus spyware can be used against a person. However, the [Indian government has failed](https://internetfreedom.in/line-by-line-verification-of-the-it-ministers-statement-on-the-pegasus-hacks/) to sufficiently respond to these damning reports [unlike their counterparts abroad, where investigations into the use of such spyware against individuals have been launched](https://thewire.in/world/france-israel-probe-pegasus-spyware-surveillance-india-denial). Since it has been ascertained that individuals in the country are being maliciously targeted through such spyware in addition to evidence being fabricated, it is imperative that the Government take steps to ensure that the privacy and security of Indian citizens is maintained.

This revelation reveals an [urgent need for surveillance reform](https://www.thehindu.com/opinion/op-ed/surveillance-reform-is-the-need-of-the-hour/article35414371.ece) to protect citizens against the use of such invasive technologies which hamper their fundamental right to privacy and threatens the democratic ideals of our country. Use of such surveillance technology on human rights defenders stops them from working with vulnerable people, some of whom may have been victimised by their own government, without opening them up to further abuse. While it seems unlikely that any stringent measures will be taken, we all share a collective responsibility to first become aware of the increasing use of malware and advocate that any such reported infections be investigated seriously. IFF is committed towards advancing surveillance reform and prohibitions on the use of malware.

**Important Documents**

1. Reports submitted by Arsenal Consulting in the matter of _National Investigating Agency v. Sudhir Pralhad Dhawale & others_ ([link](https://drive.google.com/drive/folders/1QoonWsBbpWiJFaIl2zgLN6l0rxezNHHa?usp=sharing))
2. IFF’s work relating to NSO Group’s spyware Pegasus ([link](https://internetfreedom.in/tag/pegasus/))
3. “_Explainer: Arsenal Report on Surendra Gadling_” published in The Leaflet dated July 7, 2021 ([link](https://www.theleaflet.in/explainer-arsenal-report-on-surendra-gadling/))

> > > <form><script src="https://cdn.razorpay.com/static/widget/subscription-button.js" data-subscription_button_id="pl_HLk5qU1K35hmPH" data-button_theme="brand-color" async> </script> </form>

















