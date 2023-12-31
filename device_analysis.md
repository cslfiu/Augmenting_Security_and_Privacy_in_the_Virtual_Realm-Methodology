# XR Device Analysis

## 1) Device Search Methodology

From the papers that we considered (can be found from [List of Potential and Final Papers](full_list_of_papers.md)), we gathered the devices used for the experiments. Some papers included the device name only as an example, while others used it to implement their proposed methods for the attacks or defense solution. We also looked at the companies that produced the devices mentioned in the papers and added the other XR devices from those companies to our device dataset. Additionally, we also added the older and newer versions of the devices, if there are any. At the end of this process, in total, we identified 30 XR devices which a whole list of can be found in the following sections.

## 2) Device Manifacturer's Security Documentation and Privacy Policy Links

| Device Manufacturers | Documentation Website | Privacy Policy |
| -------------------- | --------------------- | -------------- |
| Epson | [support.epson.net](https://support.epson.net) | [epson.com/privacy-policy/](https://epson.com/privacy-policy/) |
| Google | [developers.google.com/glass/design/principles](https://developers.google.com/glass/design/principles) | [policies.google.com/privacy](https://policies.google.com/privacy) |
| HTC | [developer.vive.com/resources/](https://developer.vive.com/resources/) | [htcinc.com/privacy-policy/](https://www.htcinc.com/privacy-policy/) |
| Magic Leap | [magicleap.com/en-us/](https://www.magicleap.com/en-us/) | [magicleap.com/privacy-policy](https://www.magicleap.com/privacy-policy) |
| Meta | [developers.facebook.com/docs/](https://developers.facebook.com/docs/) | [meta.com/legal/quest/privacy-policy-for-oculus-account-users/](https://www.meta.com/legal/quest/privacy-policy-for-oculus-account-users/) |
| Microsoft | [learn.microsoft.com/en-us/hololens/security-overview](https://learn.microsoft.com/en-us/hololens/security-overview) | [learn.microsoft.com/en-us/hololens/hololens2-privacy](https://learn.microsoft.com/en-us/hololens/hololens2-privacy) |
| Pico | [picoxr.com/global/safety-center/security-privacy](https://www.picoxr.com/global/safety-center/security-privacy) | [picoxr.com/global/legal/privacy-policy](https://www.picoxr.com/global/legal/privacy-policy) |
| Pimax | [pimax.com/](https://pimax.com/) | [affiliate.pimax.com/program-legal/privacy](https://affiliate.pimax.com/program-legal/privacy) |
| Samsung | [samsung.com/us/account/privacy-policy/](https://www.samsung.com/us/account/privacy-policy/) | [samsung.com/us/account/privacy-policy/](https://www.samsung.com/us/account/privacy-policy/) |
| Sony | [playstation.com/en-us/privacy-security-safety/](https://www.playstation.com/en-us/privacy-security-safety/) | [electronics.sony.com/privacy-policy](https://electronics.sony.com/privacy-policy) |
| Vuzix | [vuzix.com/products/vuzix-blade-smart-glasses-upgraded](https://www.vuzix.com/products/vuzix-blade-smart-glasses-upgraded) | [vuzix.com/pages/privacy-policy](https://www.vuzix.com/pages/privacy-policy) |


## 3) List of All Devices Considered

| Platform | Devices                                      | Type |
|----------|----------------------------------------------|------|
| Android  | Google Glass Enterprise Edition 2            | AR   |
|          | Magic Leap 2                                 | MR   |
|          | Meta Quest Pro                               | VR   |
|          | Oculus Quest 2/ Meta Quest 2                 | VR   |
|          | Oculus Quest / Meta Quest                    | VR   |
|          | Oculus Go                                    | VR   |
|          | Epson Moverio                                | AR   |
|          | Google Glass Explorer Edition                | AR   |
|          | Google Glass Enterprise                      | AR   |
|          | Google Daydream                              | VR   |
|          | Magic Leap                                   | MR   |
|          | Samsung Gear VR                              | VR   |
|          | Vuzix Blade 2                                 | AR   |
|          | Pico 4                                       | VR   |
| Windows  | Oculus Rift                                  | VR   |
|          | Microsoft Kinect One                         | AR   |
|          | Microsoft HoloLens 2                         | MR   |
|          | Microsoft HoloLens                           | MR   |
|          | HTC Vive Flow                                | VR   |
|          | HTC Vive Focus                               | VR   |
|          | HTC Vive Cosmos                              | VR   |
|          | HTC Vive Focus Plus                          | VR   |
|          | HTC Vive Pro Eye                             | VR   |
|          | HTC Vive                                     | VR   |
|          | HTC Vive Pro                                 | VR   |
|          | The Vive Wave                                | VR   |
|          | Windows Mixed Reality                        | MR   |
|          | Pimax Vision 8k                              | VR   |
| Unix     | PSVR                                         | VR   |
|          | PSVR 2                                       | VR   |


## 4) XR Devices' Security Analysis

In the following table, the references for the security properties discussed for each device in the paper are given. The references are included in this GitHub repository due to the limit of 15 references in the magazine paper.

| Device Vendor   | Devices that Applies                                                                                                       | Links |
|-----------------|----------------------------------------------------------------------------------------------------------------------------|----------------------|
| Epson           | - Epson Moverio                                                                                                             |    [Communication Security](https://epson.com/faq/SPT_V11H935020AL~faq-00006AF-bt35es?faq_cat=faq-8796158830668), [Account Security](https://files.support.epson.com/docid/cpd5/cpd53175.pdf)                  |
| Google          | - Google Glass Enterprise Edition 2 <br> - Google Glass Explorer Edition <br> - Google Glass Enterprise <br> - Google Daydream |     [Communication Security](https://support.google.com/glass-enterprise/customer/answer/9324122?hl=en)                 |
| HTC             | - HTC Vive Flow <br> - HTC Vive Focus <br> - HTC Vive Cosmos <br> - HTC Vive Focus Plus <br> - HTC Vive Pro Eye <br> - HTC Vive <br> - HTC Vive Pro <br> - The Vive Wave |    [Communication Security](https://www.htc.com/mea-en/esg/strategy-management/information-security/), [Account Security](https://www.vive.com/us/support/flow/category_howto/signing-in-with-your-htc-account.html)                  |
| Magic Leap      | - Magic Leap 2 <br> - Magic Leap                                                                                            |    [Account Security](https://www.magicleap.care/hc/en-us/articles/360008653252--ML1-Magic-Leap-ID-Overview)                  |
| Meta (formerly Oculus) | - Meta Quest Pro <br> - Oculus Quest 2/ Meta Quest 2 <br> - Oculus Quest / Meta Quest <br> - Oculus Go                   |        [Application Security](https://about.meta.com/actions/protecting-privacy-and-security/#privacy-protection), [Communication Security](https://www.theverge.com/2022/5/16/23078073/meta-quest-vr-end-to-end-encryption-messenger-v40-software-update)              |
| Microsoft       | - Oculus Rift <br> - Microsoft Kinect One <br> - Microsoft HoloLens 2 <br> - Microsoft HoloLens <br> - Windows Mixed Reality  |       [Application Security](https://learn.microsoft.com/en-us/windows/security/operating-system-security/virus-and-threat-protection/microsoft-defender-smartscreen/), [Communication Security](https://azure.microsoft.com/en-us/solutions/mixed-reality), [Hardware Security](https://learn.microsoft.com/en-us/hololens/security-hardware-backed-integrity), [Hardware Security](https://learn.microsoft.com/en-us/hololens/hololens2-privacy), [Account Security](https://learn.microsoft.com/en-us/hololens/hololens-identity)               |
| Pico            | - Pico 4                                                                                                                     |       [Application Security](https://www.picoxr.com/global/safety-center/resources#:~:text=ETSI%20EN%20303%20645%20is,protect%20users'%20information%20security%20and), [Hardware Security](https://www.picoxr.com/uk/safety-center/security-privacy)              |
| Pimax           | - Pimax Vision 8k                                                                                                           |   [Account Security](https://pimax.com/product-setup/)                   |
| Samsung         | - Samsung Gear VR                                                                                                           |                      |
| Sony            | - PSVR <br> - PSVR 2                                                                                                         |     [Application Security](https://www.playstation.com/en-us/privacy-security-safety/)                 |
| Vuzix           | - Vuzix Blade 2                                                                                                              |       [Application Security](https://www.vuzix.com/pages/app-privacy-policy)               |



## 5) Some Additional Links
In our paper, information from these links is used to summarize the properties of XR devices. 

|Link's Purpose| Link|
| -------------------- | --------------------- | 
| Information on Degree of Freedom| https://developers.google.com/vr/discover/degrees-of-freedom | 
| Meta Quest Pro's face tracking | https://www.roadtovr.com/quest-pro-face-tracking-tech-demo-aura/|
| Meta's privacy information regarding their hand-tracking technology | https://www.meta.com/help/quest/articles/accounts/privacy-information-and-settings/hand-tracking-privacy-notice/ |
| Vive Tracker 3 and body motion tracking | https://www.vive.com/us/accessory/tracker3/|
| Vive Focus 3 eye tracking technology | https://business.vive.com/eu/product/vive-focus-3-eye-tracker/|
| Meta Quest Pro's facial expression tracking | https://www.meta.com/help/quest/articles/accounts/privacy-information-and-settings/natural-facial-expressions-privacy-notice/|
| Meta devices' passthrough technology | https://www.meta.com/help/quest/articles/in-vr-experiences/oculus-features/passthrough/|
| Meta developer's website on haptic feedback APIs | https://developer.oculus.com/documentation/unity/unity-haptics/|
| Haptic feedback gloves | https://haptx.com/ | 
| HTC Vive haptic feedback controller | https://www.vive.com/us/accessory/controller/| 
| Microsoft HoloLens 2's security baseline| https://learn.microsoft.com/en-us/hololens/security-baseline|

