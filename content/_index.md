---
title: ""
date: 2023-02-08T14:47:01-05:00
draft: false
---

<style type="text/css">
      body {
        <!-- font-size: 48px;
        font-family: sans;
        font-weight: bold; -->
      }
      #container {
        /* horizontal centering */
        margin-left: auto;
        margin-right: auto;
        text-align: center;
        /* vertical centering */
        position: relative;
        top: 40%;
        transform: translateY(-50%);
      }
</style>

<br>
<div id='container'>
<p><strong>Should you enable Enhanced Open (<a href="https://en.wikipedia.org/wiki/Opportunistic_Wireless_Encryption#:~:text=Opportunistic%20Wireless%20Encryption%20(OWE)%20is,access%20point%20is%20%22individualized%22.">Opportunistic Wireless Encryption</a> with transition mode enabled)?</strong></p>
<p><strong><font size=48px>Yes!</font></strong></p>
</div>

Strong client tolerance for OWE and growing native support as sampled below:
| Device Info | Sees EO SSID? | Connects to EO SSID? | OWE support? |
|---|:---:|:---:|:---:|
| Apple iPad 2 (2011) @ iOS 9.3.5 | Yes | Yes | No |
| Apple iPad 4th Gen (2012) @ iOS 10.3.3 | Yes | Yes | No |
| Apple iPad Pro 3rd Gen (2018) @ iOS 13.5.1 | Yes | Yes | No |
| Asus Transformer Pad TF300T (2012) @ Android 4.2.1 | Yes | Yes | No |
| Fire HD 8 @ FireOS 5.6.8.0 (Nov 2020) | Yes | Yes | No |
| Galaxy A10e @ Android 9 | Yes | Yes | No |
| Macbook Pro (early 2011) @ 10.11.6 (July 2018) | Yes | Yes | No |
| Netscout AirCheck G2 @ version 4.0.0.1794 | Yes | No | No |
| Netscout AirCheck G2 @ version 5.2.0.1862 | Yes | Yes | No |
| Pixel 2 XL @ Android 10 @ August 5th, 2020 security updates | Yes | Yes | Yes |
| Pixel 3a XL / Android 11 @ October 1, 2021 security updates | Yes | Yes | Yes |
| Pixel 6 Pro @ Android 12  | Yes | Yes | Yes* |
| Samsung Galaxy J7 Sky Pro @ Android 6.0.1 (Dec 2015) | Yes | Yes | No |
| Samsung Galaxy Tab E @ Android 7.1.1 (Dec 2016) | Yes | Yes | No |
| TCL A502DL @ Android 8.1.0 (Dec 2017) | Yes | Yes | No |
| Windows 10 Home version 21H1 w/Realtek RTL8821CE adapter @ 2024.0.10.209 dated 12/4/2019 | Yes | Yes | No |
| Chromecast with Google TV (4K) @ firmware STTE.220920.016.H1 (~Jan 2023) | Yes | No | No |

[Apple Client OWE support](https://support.apple.com/guide/deployment/how-apple-devices-join-wi-fi-networks-dep3b0448c58/web#:~:text=iOS%2016%2C%20iPadOS%2016.1%2C%20and%20macOS%2013%20add%20support%20for%20Opportunistic%20Wireless%20Encryption%20(OWE)%20for%20all%20iPhone%2011%20models%20or%20later%20and%20all%20Mac%20computers%20with%20Apple%20silicon)

<p>--</p>

[Aruba Networks](https://www.arubanetworks.com/techdocs/ArubaOS_87_Web_Help/Content/arubaos-solutions/802-1x/enha-open-secu.htm)

[Cisco Systems](https://www.cisco.com/c/en/us/support/docs/wireless/catalyst-9800-series-wireless-controllers/217737-configure-enhanced-open-ssid-with-transi.html)

[Meraki](https://documentation.meraki.com/MR/Access_Control)

[Mist](https://www.mist.com/documentation/june-3rd-2021-updates/)



<font size=1px>Sorry for the terrible layout, web dev is definitely not my strong suit!<br>
WLPC2023 envy!</font>

<!-- But but my super important device doesn't support it!  I doubt you want to use an unauthenticated network anyway.... right?! -->
<!-- Standard wifi answer of It Depends! is still valid, but if your device can't do something an iPad from 2011 can do or Android 4.2.1, I'm not sure what to tell you.  -->
