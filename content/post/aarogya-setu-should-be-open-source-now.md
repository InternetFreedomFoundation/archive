+++
author = 'Raghav Kaushal'
categories = ['SaveOurPrivacy', 'aarogyasetu']
date = 2020-08-19T05:52:11Z
description = ''
draft = false
image = 'https://internetfreedom.in/content/images/2020/08/Blog-Post-Aarogya-Setu-Open-Source-1.png'
slug = 'aarogya-setu-should-be-open-source-now'
summary = 'Four months, after its initial release, the Aarogya Setu app is not open-source in the true sense of the term. Source code releases have been slow and incomplete. This is preventing the Indian tech community from collaborating and contributing.'
tags = ['SaveOurPrivacy', 'aarogyasetu']
title = 'Four months on, Aarogya Setu is still not open-source. WHY and WHEN is what the nation really wants to know! #SaveOurPrivacy'

+++


{{< figure src="https://internetfreedom.in/content/images/2020/08/Blog-Post-Aarogya-Setu-Open-Source.png" >}}

<div style="text-align:center;">
    <a href="https://internetfreedom.in/donate/" class="button">Donate to help sustain our work</a>
</div>

## tl;dr

The Aarogya Setu app was made available for public download on April 2, 2020. Ever since its release, there have been calls to make it open source as part of the government’s Policy on Adoption of Open Source Software. More than four months on, all that the developers, and the researchers have is a source code that is not even the code of the actual app. Moreover, the server-side code, which handles most of the functions of the app remains missing and the code repository barely gets updated. In this scenario, the privacy, and security of over 150 million users remain to be at risk. So, we wrote to the government asking them to step up, and soon!

## What is Open Source?

[Red Hat](https://www.redhat.com/en/topics/open-source/what-is-open-source), one of the world’s leading open source software developers define an open source software as ‘...code that is designed to be publicly accessible—anyone can see, modify, and distribute the code as they see fit.’ Furthermore, they state that making a software open source fosters principles like transparency, flexibility, reliability as the process promotes peer review and, open collaboration. The Ministry of Electronics and Information and Technology through its [Policy on the Adoption of Open Source Software](https://www.meity.gov.in/writereaddata/files/policy_on_adoption_of_oss.pdf) aims to encourage a formal adoption of the open source system by government organisations, whenever they come up with a software or a related technological service. According to the policy, the open source process ensures efficiency, transparency and reliability of such services. While it all seems good on paper, the government’s actions have been quite the opposite when it comes to Aarogya Setu.

## The Aarogya Setu and its tryst with Open Source

The Aarogya Setu App was released for public access for the first time on April 2, 2020. Not long after this launch, tech experts and media outlets from across the globe started flagging massive issues related to privacy, transparency, data minimisation, liability and accountability. In other words, early on after the release, a strong consensus had developed that the app and its deployment had glaring issues that needed swift and prudent redressal. We had detailed out these issues in our [blog post](https://internetfreedom.in/is-aarogya-setu-privacy-first-nope-but-it-could-be-if-the-government-wanted/) dated April 14, 2020.Given these issues, it is not surprising that ever since its release, security experts, digital rights defenders and the country’s developer community have been calling for the app to go the open-source route. While there was initial resistance from the government, especially through the earlier terms of the app, which explicitly prohibited reverse-engineering even for the purpose of research, the MeitY finally decided to make the app open source through a [PIB release](https://pib.gov.in/PressReleasePage.aspx?PRID=1626979) dated 26 May 2020. To this effect, the native source code of the Android version of the app was [released officially on GitHub.](https://github.com/nic-delhi/AarogyaSetu_Android)

## Is Aarogya Setu finally open source? Well, not really. We explain.

**1. Massive delays in source code release:** MeitY’s PIB release, which announced the app going the open source route, only released the Android version source code of the app. The app also has an iOS version for the Apple devices and a KaiOS version, which runs on various Nokia phones and the JioPhone. While the PIB release promised the iOS app’s source code within two weeks, it was only [recently released](https://www.livemint.com/technology/tech-news/india-open-sources-code-for-aarogya-setu-ios-app-11597321681940.html) on 10 August, 2020 after a two month deviation from the timeline. Here, there are two major problems: 

* With Aarogya Setu’s user footprint increasing rapidly, any delay in releasing the source code effectively defeats the purpose of the open source process. This is because as more Indians are urged to use the app, sometimes through coercive measures, more Indians become vulnerable to the inherent privacy, and security issues of the app. Therefore, any delay in releasing the source code runs a massive risk of taking us to a point of no return, where the privacy and security of the users is irreversibly compromised.
* The press release does not even mention the KaiOS version of the app, which is cause of great worry as quite a sizeable number of app users on these platforms might miss out on essential fixes and enhancements that might develop through the open source collaboration. This is tantamount to putting the privacy and security of a lot of users are at a deliberate risk.

**2. The released source does not match the actual app:** An even bigger issue has been flagged by multiple developers and users on the GitHub page of the source code. These users have commented that the app that the source code provided on the official GitHub release does not match the actual version of the app, which is available for the users to download and use. In other words, the researchers and developers cannot contribute to the process because they have not even been given the actual code to work with! While the press release invokes the Policy on Adoption of Open Source Software and calls for collaboration with the top technical brains of the country, such a move prevents any such collaboration and is antithetical to the principles of making a venture open source. To exacerbate this further, the code repository on GitHub has not been updated since its initial release and there is a massive backlog of queries and flagged issues.

**3. The server-side code and cloud deployment functions are nowhere to be seen:** Perhaps the biggest issue right now is the absence of the server-side code of the app. The Aarogya Setu app uses the WebView project to load [https://web.swaraksha.gov.in/ncv19/](https://web.swaraksha.gov.in/ncv19/) through the app to perform most of the app’s functions. Most of the major and the most important functions of the app, therefore, are executed and stored on the app’s server infrastructure itself and not on the device. This means that without access to the server source code and cloud deployment details not much insight can be gained about the app’s functions and data storage. Therefore, the developers and researchers keen to work on this app cannot help in making it better, more robust and more privacy-friendly.

So you decide, is Aarogya Setu really open-source yet?

## IFF raises concerns with the Government

We have been vociferously supporting the cause of making Aarogya Setu an open source project. We, at, IFF, believe that this is absolutely necessary given that the app deals with sensitive personal information and therefore privacy, security and liberty of all its users. In such a scenario, ensuring that the bright Indian tech community is given a chance to collaborate with the government and contribute towards making the app more secure, more robust and overall, better. Therefore, [we wrote](https://drive.google.com/file/d/1-YjR200HNz_GNaVj82ltNJ6lxOL8ej_b/view?ts=5f3bdd9b) to the Ministry of Electronics and Information Technology, NITI Aayog and the National Informatics Centre to urgently take note of these pressing issues and provide quick redressal. To this effect, we also gave a few recommendations that will steer the process in the right direction:

1. **Expedite the release of the server-side code, cloud deployment features and KaiOS source code:** The Aarogya Setu app relies on the server code for most of its functions. This means that simply releasing the device code will not give any real insight to the developers into the functioning of the app. Hence, releasing the server code, the KaiOS code, and cloud deployment features at the earliest should be the priority.

**2. Resolve the issues on GitHub in real-time and engage with the queries of the developers:** The first set of native app code for Aarogya Setu was released nearly three months ago. Since then, developers from across the country have been working tirelessly towards making the app more functional, more secure and overall, better. However, it is important that their queries and the issues that they flag should be dealt with in real-time or at least within an acceptable time frame. This will ensure that the young developer community of the country is further encouraged to positively contribute to government ventures, something which is extremely important to foster an environment of collaboration and innovation in the technological innovation and more particularly the cybersecurity space.

**3. Regularly update the code repository on GitHub:** The mismatch between the public app version and the code available to the developers and researchers is antithetical to the whole premise of open source testing. Therefore, we would like the government to look into this matter and ensure that the GitHub code repository is up-to-date and up-to-speed with the actual app so that the open source protocol can be duly followed.

## Important Documents:

1. Our representation to MeitY, NITI Aayog and NIC highlighting the loopholes in the open source process of Aarogya Setu dated August 18, 2020 [[link](https://drive.google.com/file/d/1-YjR200HNz_GNaVj82ltNJ6lxOL8ej_b/view?ts=5f3bdd9b)]
2. Is Aarogya Setu privacy-first? Nope, but it could be-- If the government wanted. dated April 14, 2020 [[link](https://internetfreedom.in/is-aarogya-setu-privacy-first-nope-but-it-could-be-if-the-government-wanted/)]
3. A look at Aarogya Setu through the Right to Information lens dated May 27, 2020 [[link](https://internetfreedom.in/aarogya-setu-through-the-right-to-information-lens/)]

