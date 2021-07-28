+++
author = "Farkhanda Zahoor"
categories = ["66A", "Censorship", "freespeech"]
date = 2020-07-08T08:51:42Z
description = ""
draft = false
slug = "update-on-zombie-tracker"
summary = "IFF, in collaboration with CivicDataLab, is building a “Zombie Tracker” to track cases under S. 66A, Information Technology Act, at the district level. S.66A of the IT Act is termed as a legal zombie since, even though it was declared unconstitutional in 2015, its use is ongoing."
tags = ["66A", "Censorship", "freespeech"]
title = "Update on IFF’s Zombie Tracker"

+++


{{< figure src="https://lh5.googleusercontent.com/4NqA0UkCT1gByRrAMH5lIQFYktnltwU_KDMYvECU9cHQiV2kD2-b4Dh9QoQEOmd_DGzjHY8hOK-zK7ltRMeC3hu1HbdfTYiFm4YiOUJWUKcHOkagTCZLoG979giiC_GGbQkjQdft" >}}

<div style="text-align:center;">
    <a href="https://internetfreedom.in/donate/" class="button">Donate to help sustain our work</a>
</div>

**TL;DR**

IFF, in collaboration with [CivicDataLab](https://www.civicdatalab.in/), is building a “**Zombie Tracker**” to track cases under S. 66A, Information Technology Act, at the district level. S.66A of the IT Act is termed as a legal zombie since, even though it was declared unconstitutional in 2015, its use is ongoing. Currently, we have mined, curated and verified our dataset. Moving forward, we are working on building the tracker interface as well as conducting secondary research. We intend to use the insights gained from collected data to strengthen our advocacy efforts to ensure that S. 66A dies a complete constitutional death.

[**We are building a Zombie Tracker!**](https://internetfreedom.in/no-more-section-66a-cases-we-are-taking-the-agami-challenge/) ****

Section 66A of the Information Technology Act, 2000 was declared unconstitutional by the Supreme Court of India in March, 2015 in [_Shreya Singhal v Union of India_](https://indiankanoon.org/doc/110813550/). The Court declared that the provision was _void ab initio_ i.e was deemed to never have existed on the statute books. The effect of this would be that all pending cases would be dismissed and no fresh cases would be instituted under S. 66A. However, in 2018, [a research paper by Abhinav Sekhri and Apar Gupta](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3275893) highlighted that Section 66A was being still used for legal prosecutions all over the country. Taking note of the above-mentioned study, People’s Union for Civil Liberties (‘PUCL’), one of the original petitioners in the Shreya Singhal case approached the court in January, 2019 highlighting the study and applying for directions to ensure implementation of the Court’s decision. Inspite of repeated directions by the Supreme Court as late as 2019, [our preliminary research shows that, S. 66A is still being invoked in fresh cases](https://internetfreedom.in/66a-zombies-continue-to-menace-free-speech-on-the-internet/). Our preliminary findings were backed by a [recent media report which highlights the continued invocation of S.66A](https://www.livelaw.in/news-updates/financial-assistance-of-5000-each-granted-to-16448-advocates-to-deal-with-covid-19-crisis-bar-council-of-delhi-tells-delhi-hc-159564?infinitescroll=1). Further, we noticed that the mountain of pending cases including a charge under S.66A is ever increasing. Therefore, we are building a tool to track registered cases which include a charge under S.66A. We intend to use the data and insights generated from it to bolster our advocacy efforts to ensure that no fresh charge is registered under S.66A and pending charges under S.66A are dismissed. 

The **Zombie Tracker** will be tracking cases which include a charge under S.66A at the district level, across 11 states: Andhra Pradesh, Assam, Delhi, Jharkhand, Karnataka, Maharashtra, Rajasthan, Sikkim, Tamil Nadu, Telangana, and West Bengal. The tracker will be collecting case data using the E-Courts application programming interface (API) , for the period 27th October 2009 to 15th February 2020.

**Progress**

First, we conducted a manual search to identify if all cases on the website including a charge under S.66A were tagged as such on the E-courts website. During our manual tests on the E-courts website, we observed the following:

* Some cases which included a charge under S.66A, were tagged as Information Technology Act, but not as a 66A case under the section tags;
* Some cases including a charge under S.66A were tagged as S.66a instead
* certain sections of the Indian Penal Code(IPC) were repeatedly invoked with a charge under S.66A

We therefore decided to, at the first instance, cast our net to include all cases under the Information Technology Act, 2000. Considering the consistent presence of certain IPC provision, we further cast our net to include all cases under these* provisions of the IPC.

The above list of cases was then manually curated on the basis of sections invoked in the cases. Cases involving any variation of 66A i.e. 66a, 66(a),66AC etc. were flagged positive, and the rest of the cases were filtered out. This resulted in a list of cases with 1163 section tag combinations. This list was then further manually curated by reference to judgements and orders, where present, to create the final data set. Cases without an order/judgement were marked negative and filtered out to avoid a false positive result. A false positive, in this scenario, will result when a case is improperly reported as including a charge under S.66A, when in reality it doesn't. There are a number of cases with ambiguous tags which we have not been able to verify due to the lack of orders/judgements. Due to our inability to verify them these cases have currently been excluded from our final dataset. 

**The way forward**

We now have our final data set and are proceeding to analyse the data generated. We are also conducting secondary research to generate meaningful insights from the dataset, which can help support our advocacy efforts. Alongside our research, we are collaborating with CivicDataLab to build the tracker platform. We aim that our platform will, firstly, highlight the number of cases with an pending under S.66A as well as the number of cases registered after the decision of the Supreme Court in _Shreya Singhal_. Secondly, we intend to present our findings to the judiciary and law enforcement bodies to ensure S.66A is not invoked again and any pending charges are dismissed. Lastly, we hope to provide a privacy preserving open data set to aid researchers in further research and analysis. 

During our research, one of the main hurdles we have encountered is the incompleteness of data available on the E-courts website. Currently less than 20% of the decided cases in our dataset have an order or judgement available. This unavailability of documents has hampered our data verification process. 

Your experience might help our verification efforts, to ensure no case with a charge under S.66A is missed out. Have you been threatened with a charge under S.66A? Have you been charged under s.66A? Do you know someone who was or is currently charged under S.66A? If yes please forward the following survey to them.  Your experience can help reinforce our efforts, tell us your story by filling out this survey:

<div style="text-align:center;">
    <a href="https://blocksurvey.io/survey/1PfQfn62JSDjjyK4nuHoY5t21wKeuocLLm/86bf1e54-ceea-4c84-b122-bbd9aa19bf60" class="button">Fill out the survey here</a>
</div>



Further updates on the Zombie Tracker will be issued closer to the platform launch. Our efforts are possible only due to your support, [donate and become a member today](https://internetfreedom.in/donate/)!

_(This post has been authored by Sonalakshi Naidu, research assistant at IFF, and reviewed by IFF staffer, Anushka Jain)_

| Section (IPC) | Offence                                                                                                                                                             	|
|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 153 	| Wantonly giving provocation, with intent to cause riot—if rioting be committed; if not committed.                                                                   	|
| 153A	| Promoting enmity between different groups on grounds of religion, race, place of birth, residence.language, etc., and doing acts prejudicial to maintenance of harmony. |
| 153B	| Imputations, assertions prejudicial to national-integration.                                                                                                        	|
| 295A	| Deliberate and malicious acts,intended to outrage religious feelings of any class by insulting its religion or religious beliefs.                                   	|
| 298 	| Uttering words, etc., with deliberate intent to wound the religious feelings.                                                                                       	|
| 505 	| Statements conducing to public mischief                                                                                                                             	|
| 509 	| Word, gesture or act intended to insult the modesty of a woman.                                                                                                     	|



**Important Documents**

1. Section 66A and Other Legal Zombies by Abhinav Sekhri and Apar Gupta ([link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3275893))
2. 66A Zombies continue to menace Free Speech on the Internet ([link](https://internetfreedom.in/66a-zombies-continue-to-menace-free-speech-on-the-internet/))

<div style="text-align:center;">
    <a href="https://forum.internetfreedom.in/" class="button">Join the Internet Freedom Forum</a>
</div>



