+++
author = "Devdutta Mukhopadhyay"
categories = ["aarogyasetu", "RTI", "Privacy", "Data Protection"]
date = 2020-12-03T06:24:53Z
description = ""
draft = false
image = "https://internetfreedom.in/content/images/2020/12/Aarogya-Setu-MoM-1.png"
slug = "aarogya-setu-minutes-of-meetings"
summary = "Minutes of meetings of the 9th Empowered Group on Technology and Data Management provide an insider view into the creation and expansion of Aarogya Setu and other government data collection projects during the COVID-19 pandemic."
tags = ["aarogyasetu", "RTI", "Privacy", "Data Protection"]
title = "Internal govt documents provide insight into the creation and expansion of Aarogya Setu #SaveOurPrivacy"

+++


{{< figure src="https://internetfreedom.in/content/images/2020/12/Aarogya-Setu-MoM.png" >}}

<div style="text-align:center;">
    <a href="https://internetfreedom.in/donate/" class="button">Donate to help sustain our work</a>
</div>

### Tl;dr

Minutes of meetings of the 9th Empowered Group on Technology and Data Management provide an insider view into the creation and expansion of Aarogya Setu  between 31 March 2020 to 10 August 2020. These documents were obtained by IFF through the Right to Information Act, 2005 and they contain information about several projects including the Aarogya Setu proximity exposure notification app, the ITIHAS hotspot mapping and prediction system, collection of cell tower location data by the Department of Telecom, and apps to input data regarding RT-PCR and antigen tests.

### Background

In April 2020, we filed RTI applications seeking information about the Aarogya Setu app with various government authorities including the Ministry of Health & Family Welfare (MoHFW). Since we did not receive a response to our RTI queries within the stipulated 30 day time period, we filed a first appeal with MoHFW which was transferred to the Department of Electronics and Information Technology (DeitY) like the original RTI application. Finally, on 10 November 2020, DeitY shared minutes of meetings of the 9th Empowered Group Committee on Technology and Data Management held between 31 March 2020 to 10 August 2020 in response to our RTI queries.

The Central Government has constituted several Empowered Groups under the Disaster Management Act, 2005 (DMA 2005) and powers have been delegated to these groups through orders which reference Sections 10(2)(h) and (i) of the Act. However, Section 10 does not permit any delegation of power and none of the provisions of DMA 2005 contain any reference to an “Empowered Group”. Therefore, the legality of this delegation of power upon Empowered Groups is questionable. The Government has constituted 11 Empowered Groups in total and the 9th Group has been specifically tasked with 'Technology and Data Management' and it is responsible for the creation and expansion of Aarogya Setu.

The minutes of meetings of the 9th Empowered Group obtained through the RTI Act provide an insider view of the government's data collection projects during the COVID-19 pandemic which include the Aarogya Setu proximity exposure notification app, the ITIHAS hotspot mapping and prediction system, collection of cell tower location data by the Department of Telecom, and apps to input data regarding RT-PCR and antigen tests.

### Aarogya Setu Mobile App

The documents clearly state that there should be two-way sharing of data between Aarogya Setu and other databases which include the COVID India Portal (S-3) and the Ayushman Bharat System. These databases would also be connected to apps for RT-PCR and antigen tests to create a single source of truth. __ Here are some of the relevant portions of the minutes which descibe the relationship between different databases.

**(i) Aarogya Setu and COVID India Portal (S-3)**

> _"It was decided that that there should be integration of Bluetooth contact tracing data of Confirmed Positive cases from Aarogya Setu to S3 System. The contact tracing data should be visible to the district / state officers through S3 System interface enabling them to track and take necessary action for testing/ surveillance of these suspect cases. The action taken by the officers on this cases then should flow back to Aarogya setu to complete the cycle."_

**(ii) Aarogya Setu and Ayushman Bharat**

> _"Leads in the Aarogya Setu should be verified by Ayushman Bharat System and the filtered set of leads should be shared with states. Further feedback and action taken from field staff should flow back to Aarogya Setu."__"The group was further informed that both Bluetooth and self assessment data (cleaned by Aarogya Bharat) are flowing from Aarogya Setu to S3 and vice-versa."_

During the meetings, concerns were raised about sharing of health data between so many databases with Dr. Harpreet Singh, ICMR noting that _"lab data of Covid-19 is highly sensitive (health data) and at present there are many APIs for sharing of data with different stakeholders including NDMA, NHA & others. There is need for Do’s and Don’ts with clear set of guidelines to secure the data."_ Government officials also seem to be aware of inaccurate reporting of a person's status by the Aarogya Setu app. For instance, during one of the meetings, Mr. RS Mani, DDG NIC highlighted _"the issue of false alarm (person released from hospital but status not updated)."_

The technical design choices of Aarogya Setu have been a subject of discussion among members of the 9th Empowered Group and officials from National Informatics Centre (NIC) were required to explain their reasons for adopting a static ID and not sharing the source code initially but these reasons are not mentioned in the minutes. NIC officials further pointed out that India could not use the Google-Apple API because it prohibited location tracking. NIC was also entrusted with the responsibility of handling the back end code of Aarogya Setu and it worked with pro bono volunteers from HP on this project.

### ITIHAS Hotspot Mapping and Prediction System

The minutes of meetings of the 9th Empowered Group contain several references to the ITIHAS system developed by Prof. Kamakoti, IIT Madras and NSAB for hotspot mapping and prediction. The forecasts from ITIHAS were to be integrated with the COVID India Portal (S3) and Prof. Kamakoti also made a presentation on findings from integration of ITIHAS with Aarogya Setu data. The documents also contain references to a project called 'Aarogya Rekha' being developed by Prof. Kamakoti which would be integrated with Aarogya Setu. Once this integration was done, states would then be asked to start using this tool for geographical marking of hot-spots.

### Use of Cell Tower Location Data

The minutes of meetings reveal that proposals to use cell tower location data to track the movement of persons was first considered in the context of the post lockdown exodus of migrants. It was decided that the Department of Telecom (DoT) would determine what kind of telecom data could be obtained about movement of migrants and this data could subsequently be shared with state governments to follow up with individual cases.

Once this data was collected by DoT, it was shared with Professor Kamakoti for further analysis and it was also made available on the COVID India Portal (S-3). In later meetings, it is clarified that the data has been aggregated at Cell Tower Level and anonymised to remove all mobile numbers and personal details but it is not clear at what stage such anonymisation took place.

During one of the meetings, the DoT officials also offered to _"monitor the intrusion (persons with/without pass) and report the telephone numbers which do not have valid pass to States/Authorities."_ For this purpose, DoT was supposed to create a dashboard with latitude and longitude coordinates for all telephone numbers which could be piloted in a city.

### Important Documents

1. Folder containing minutes of meetings of 9th Empowered Group ([link](https://drive.google.com/drive/folders/1fF-UmjWa0Sr_lLx9gkYsqZJID6C91hOM?usp=sharing))
2. Previous post titled 'A look at Aarogya Setu through the Right to Information lens' dated 27 May 2020 ([link](https://internetfreedom.in/aarogya-setu-through-the-right-to-information-lens/))







