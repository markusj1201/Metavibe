![Protocol](https://img.shields.io/badge/Protocol-BitcoinSV-yellow.svg)
![Framework](https://img.shields.io/badge/Framework-ReactNative-blue.svg)
![GitHub contributors](https://img.shields.io/github/contributors/Kohze/Metavibe.svg)
![GitHub issues](https://img.shields.io/github/issues-raw/kohze/Metavibe.svg)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/Kohze/fireData/master/LICENSE.txt)
![MetaVibe](http://kohze.com/metaVibe/headTitle.jpg)



MetaVibe creates a location based meta layer on top of our physical world. Thereby allowing to drop media content, comments and other smart contract based events to specific locations while ensuring that only people at the location can read the content. Here we present the functional prototype (Android & iOS) as well as the open protocol of MetaVibe. 

Key Innovations: Location Based Encryption, MetaVibe Protocol & Ecosystem, Location specific media & smart contracts, Mediates micro ecosystem and blockchain adoption.

![Frameworks](http://kohze.com/metaVibe/Screenshot_21.jpg)



![Showcase](http://kohze.com/metaVibe/Showcase.jpg)

![Mockup](http://kohze.com/metaVibe/S7_mockup_preview_2.jpg)

![Application](http://kohze.com/metaVibe/Application.jpg)

[![ytVideo](http://kohze.com/metaVibe/yt_screen.jpg)](https://www.youtube.com/watch?v=sqAN92Vhqjo)


People are forming virtual communities, but are increasingly disconnected from their local community. Humans are naturally curious about their physical surroundings and want to interact with other users of that space, but information is suspended in the virtual world without connection to the real world.

MetaVibe places meta layer on top of our physical world to allow users to drop content (messages, photos, audio etc) to specific physical locations while ensuring that only users who visit that location can interact with that content. MetaVibe encourages a more authentic connection between content and the physical world. MetaVibe heightens the user’s experience of the physical world and heightens the online experience by linking it to the physical world.

MetaVibe will enable users to experience content localised and linked to a physical location.  Like scattering digital breadcrumbs across the physical world for others to read and interact with.  Content can be matched to suit the mood, scenery and history of the place where the creator left it. 

TLDR: While social media enables us to find a variety of connections and events, they also take away a sense of locality and the willingness to explore the unknown. Here we connect user experience of reddit (multi-interest heterogeneity) with the excitement of roleplay games (solving quests) and the exploration aspect of augmented reality games. 



![GardenImage](http://kohze.com/metaVibe/garden_image2.jpg)

Our pitch: https://docs.google.com/presentation/d/1uWEwfcsHcMdVM-dcYgeLZg2Nv_ks_OQsPSjmdyV2ves/edit?usp=sharing

![Use Cases](http://kohze.com/metaVibe/use_cases.jpg) 




- Place editable content to specified places to enrich user experience and knowledge
- Follow local creators and see the places they placed content. The content will have the handle, identifier, qualifications of the person who added it (adds credibility/weight to the content)
- User can select a city tour based entirely on content uploaded by content loaders
eg Kings college professor uploads a history of kings college chapel, including personal anecdotes about his experience of the chapel 
- phone of user buzzes when reaching a site with previously specified content
- boosting tourist numbers and experience at tourist locations
- Adoption and onboarding: Users can receive bitcoin for solving quests and challenges. Businesses owners can share rewards for coming to their location. Thereby boosting customer & tourist numbers and experience.
- Beacon wallet that is static to defined places to preserve historic sites/natural spaces/local wildlife
- Local donations: visitors deposit small fee after enjoying interacting with that space
- Smart contract based unlocking: facial recognition software to identify the individual and transfer bitcoin-based currency
- Message dropping: leaving messages/media at specified locations
eg song recommendation for that particular geographic location
- Filter ‘Vibes’ by type to see only content of interest
- Access side specific media content: poem written about that site, book recommendations about the site, photos taken at the site (and get rewarded by tipping mechanism)
- Add content to monuments: visiting former home/gravesite of famous person - access biography, interactive content on their life
- Messages and comment thread attached to a geographic location (location specific reddit threads)
- including jokes from previous visitors 
- can add to the banter/chat around the statue/site/location
- can vote for best jokes/puns on each location
- Content creator tipping: can make small payments to best joke/pun
- good for people travelling alone to tap into the kind of experience group travellers have - ie the interpretation/cultural interaction/experiencing of the sights/locations
- getting location based ticket for event in proximity (eg a museum, niche concert)
- Rewarded in micropayments for: Reading warning signs for X seconds
- Accessing premium virtual tours all around the city (audiobooks and description)
- Create activity challenges: local users upload recommended jogging routes in the area. Get rewarded for completing challenges 
- Trip Advisor: useful for visitors who don’t know the lie of the land (eg quiet backstreets, good parks)
- Value and reward ecosystem: getting tipped for interesting insights left behind 
- Location based transfers: drop bitcoins to everyone at the current location or conference 
- “green” list of valuable locations connected with information child/family friendly content


![AR](http://kohze.com/metaVibe/ar.jpg)

Augmented reality (AR) is used to allow users to visualize messages in their visible environment in real time. The AR messages track with the physical movement of the user's device, allowing them to see and interact with the messages at their precise location as they move/walk. The message location within the AR portion of the app is shown at a specific height above the ground, allowing content creators to place messages at, for example, façades of buildings or on billboards, etc.

An AR application, to be embedded within the main React Native app, allows the virtual visualization of messages (represented as tap-able icons) at their real location. The user’s camera provides the background of the image; live GPS location allows dynamic loading of messages within a reasonable distance. Messages have a 3-component location associated with them, so their corresponding icons can be placed in the correct location on the camera feed. The React Native app will communicate with the blockchain, and send a list of nearby messages to the Unity AR app, which will then process their location data and render the virtual icons in real time [MessageAR2/Assets/TapObject.cs]. Downloadable demo version for Android, currently in alpha stage development and featuring moving message icons simulating a user walking down a street, is at [MessageAR2/MetaVibeAR.apk] (NB: the full AR functionality is currently only available on some devices; see ![Vuforia supported devices](https://library.vuforia.com/articles/Solution/vuforia-fusion-supported-devices.html).

Quick facts: 

- AR mockup: https://3yqf6b.axshare.com
- Made with Unity/Vuforia, the leading platform for fully-featured AR development
- Allows users to interact with messages in their physical 3D location
- Icons stay where they belong in space even as user pans their phone around the environment
- Highly extensible and customizable - beta stage implementation will include customized message icons, etc.

![Challenges](http://kohze.com/metaVibe/challenge2.jpg) 

**Getting users onto the app**
- what initial motivation?
- sticker on the physical location - “download this app for more information on this site”
- starts to build awareness of the app’s existence and build broader interest 
- how do they find out about the app

**Initial bitcoin injection**
- payments from advertisers seeking to connect with their customers
- ie customer gets paid to accept ads from products they already enjoy

**Medium/long term bitcoin ecosystem**
- users uploading content get paid in micro-payments
- incentivises good quality/tailored content

![Ecosystem](http://kohze.com/metaVibe/ecosystem.jpg)

![ecosystemImage](http://kohze.com/metaVibe/eco_screenshot.jpg)

MetaVibe Introduces an extensible blockchain environment for a variety of applications under the same base protocol and same dataset. Therefore, businesses might develop commercially optimised apps that add and access the same environment. MetaVibe is a high level user experience focused Android and iOS implementation within the ecosystem.

op_return scheme:

- [1] protocolID (MetaVibeAlpha)
- [2] open message title
- [3] open message
- [4] type (to enable filtering)
- [5] location: longitude
- [6] location: latitude
- [7] image
- [8] persistence time
- [9] encryption type (msg, wifi, image captcha)
- [10] secret message (encrypted) 
- [11] uploader (to enable following people)


![Insights](http://kohze.com/metaVibe/Insights.jpg)

Since GPS alone can be spoofed, we added additional safeguards to ensure that a user is at the specific location and made it part of the content encryption [not implemented yet]. We thereby found 3 viable solutions to safeguard that a user is actually at the location.

**BSSID based location authentication:**

TLDR: The router BSSID is used as part of the threshold encryption, thereby the user needs to know the majority of router identifiers at their location. The BSSIDs of all surrounding routers are used while the user submits the message/event. 

Code for creating a list of local wifi networks
https://github.com/devstepbcn/react-native-android-wifi

*GPS + BSSID*
- content uploader must visit the geographic location in order to deposit the content
- the list of SSIDs it detects as it adds the content will form part of the authentication mechanism (along with GPS coordinates)
Downside of this: restricts content contributors to locals
Positive of this: keeps the ‘hyperlocality’ nature of the app
- this app allows content to be shared at a specific physical location, through different temporal landscapes

```
Eg: Wifi networks near King’s College Chapel
Latitude: 52.2045 to 52.2049
Longitude: 0.1161 to 0.1173
‘events’ BSSID: 26:a4:3c:bb:d1:a9
‘eduroam’ BSSID: 36:a4:3c:bb:d1:a9
‘eduroam’ BSSID: 2e:a4:3c:bb:df:ae
‘Guest-Rms’ BSSID: 1c:af:f7:2e:2e:3d
‘e_network’ BSSID: 7c:d1:c3:ca:05:68
‘_TheCloud’ BSSID: c4:10:8a:19:b3:68
‘BTOpenzone-CaffeNero’ BBSID: 00:1e:13:45:29:21
Honor 8 Lite, BSSID: 50:04:b8:2b:b5:b0
sparessid, BSSID: 32:a4:3c:bb:df:ae
guests, BSSID: 24:a4:3c:df:a0:6a
```

**Image Based Recognition**

Since BSSIDs can be recorded and potentially acquired for the location via network database, we added a feature where the user needs to recognize one or more images at the location (again threshold based). In addition to encryption image the content creator uploads of a easily recognizable detail of the surrounding, a google image search query will add multiple similar looking images. The user then needs to pick the right one in a captcha style

![Captcha](http://kohze.com/metaVibe/Captcha.jpg)

**Local Knowledge Based**

A third variant is to ask for a key that consists of the answer of locally well known facts, such as the number on a certain building or the opening times of a shop (that might not easily be verifiable online). This method does not require images and is most simple.

![Legal](http://kohze.com/metaVibe/Legal.jpg)

**1. Illegal or harmful content uploaded to MetaVibe**

The UK is looking to introduce the first online safety laws of their kind late 2019 or 2020, placing new obligations on social media companies and tech firms to protect their users and face tough penalties if they do not comply.

In the offline world the owners of physical spaces owe a duty of care to visitors. The drafters of the new UK law are considering a parity principle in which owners of online services are also required to take reasonable measures to prevent harm. MetaVibe would face such a duty of care towards its users as the host of content uploaded by its users.

Not all harms that users face in the digital world are easily identifiable illegal harms. Some online harms have a clear legal definition, such as child pornography, terrorist content and encouraging or assisting suicide. Other harms with a less clear legal definition in the online space include cyberbullying, offensive or extremist content and advocacy of self-harm.
  
The MetaVibe developers seek to address these concerns of harmful/offensive content uploaded to the app by:
- Green listing content to enable family friendly version [currently in planning, not yet integrated]
- Blacklisting of offending content creators [currently integrated]
- User rating system to promote trusted/reliable content creators and assist in identifying offensive material
- User accounts linked to a bitcoin wallet to enhance accountability
- a limited liability policy to address unreasonable behavior from users of MetaVibe who do not respect legal and non-harmful content requirements
- Removing the harmful data from the app
 
**2. Consumer Privacy Protection**

The UK’s Data Protection Act 2018 places obligations on businesses in handling personal information from customers. These obligations require that such information is handled in a way that ensures appropriate security, including protection against unauthorized access or destruction. This includes protecting the security of financial transactions occurring on the app. 

MetaVibe will utilise user logins via the MoneyButton app. Users will first need to sign up to the MoneyButton app to create a bitcoin wallet to be used to transfer micropayments used to view other users’ content or upload their own content to the app. The MetaVibe app developers will not require users to provide full personal information (e.g. real name or DOB) to MetaVibe. The MoneyButton bitcoin wallet will function as the secure payment processing mechanism for all transactions on MetaVibe.

**3. Intellectual Property Protection**

Given that MetaVibe will serve as a largely open source platform, the users uploading content will retain copyright over their work loaded to the app. 
MetaVibe will secure the IP behind the app concept via patent with the UK Intellectual Property Office and file an application with the European Patent Office and WIPO International Patent System to enable IP protection across more than 140 countries. 

Sources:
(1) The Malicious Communications Act 1988 prohibits the sending of messages which are threatening or grossly offensive; it applies whether the message is through the post or through any form of electronic communication. The Computer Misuse Act 1990 targets online behaviour, introducing criminal liability for hacking and other unauthorised access or modification of computer material.

![Demo](http://kohze.com/metaVibe/demo.jpg)

Install: 
clone repo, then:
- yarn install
- yarn start

Quick peek at Android demo via Expo App in Google Playstore: exp://172.29.13.101:19000

Update: 7-05-2019 18:30:
- The App got in the meantime published to the permanent Expo repository (optimized to Android). Download the Expo App and scan the QR code below to use the app. 

![QR](http://kohze.com/metaVibe/qr.png)

![Team](http://kohze.com/metaVibe/Team.jpg)

- Robin Kohze, PhD Student, Cambridge Department of Genetics
- Chris Maits, MPhil Student, Cambridge Law
- Reina Nakamoto, Professional Game Designer 
- Noah Kessler, PhD Student, Cambridge Department of Genetics
- Gioia Riboni-Verri, MPhil Student, Cambridge Life Sciences


