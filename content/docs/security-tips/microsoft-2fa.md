---
title: "How to enable TOTP-based 2FA on a Microsoft account"
description: Tips for securing your MS account. Includes instructions for generic TOTP without having to use the Microsoft Authenticator app.
weight: 4
---

## Choosing a 2-factor authentication app

TOTP-based authentication is a standardized system, so there are different options to choose from:

| App | Platforms | Has sync? | Open source? | Notes |
|-|-|:-:|:-:|-|
| [Authy](https://authy.com/) | ![Windows](/obscure-tutorials/img/icons/platforms/WIN.png) ![macOS](/obscure-tutorials/img/icons/platforms/MAC.png) ![Linux](/obscure-tutorials/img/icons/platforms/LIN.png) ![Ubuntu](/obscure-tutorials/img/icons/platforms/UBT.png) ![Android](/obscure-tutorials/img/icons/platforms/AND.png) ![iOS](/obscure-tutorials/img/icons/platforms/IOS.png) | ✅ | ❌ | Requires Snap on Linux. Has vendor lock-in &mdash; it will not show you your codes. Has better restore functionality than other apps |
| [Aegis](https://getaegis.app/) | ![Android](/obscure-tutorials/img/icons/platforms/AND.png) | ✅ | ✅ | Sync is via cloud storage API |
| [WinAuth](https://winauth.github.io/winauth/index.html) |![Windows](/obscure-tutorials/img/icons/platforms/WIN.png) | ❌ | ✅ | | |
| [Ravio](https://apps.apple.com/us/app/raivo-otp/id1459042137?platform=iphone) |![iOS](/obscure-tutorials/img/icons/platforms/IOS.png) ![iPadOS](/obscure-tutorials/img/icons/platforms/IPA.png) | ✅ | ✅ | Sync is via iCloud |
| [TOTP.app](https://totp.app/) | ![Web](/obscure-tutorials/img/icons/platforms/FOS.png) ![Web](/obscure-tutorials/img/icons/platforms/COS.png) | ❌ | ✅ | Stored in browser cookies |
| [oathtool](https://www.nongnu.org/oath-toolkit/) | ![Linux](/obscure-tutorials/img/icons/platforms/LIN.png) ![Debian](/obscure-tutorials/img/icons/platforms/DEB.png) ![Ubuntu](/obscure-tutorials/img/icons/platforms/UBT.png) ![Fedora](/obscure-tutorials/img/icons/platforms/FED.png) ![CentOS](/obscure-tutorials/img/icons/platforms/CES.png) ![Archlinux](/obscure-tutorials/img/icons/platforms/ARL.png) ![Linux](/obscure-tutorials/img/icons/platforms/BSD.png) | ❌ | ✅ | Advanced |
| [pass-otp](https://github.com/tadfisher/pass-otp) | ![Linux](/obscure-tutorials/img/icons/platforms/LIN.png) ![Ubuntu](/obscure-tutorials/img/icons/platforms/UBT.png) ![Debian](/obscure-tutorials/img/icons/platforms/DEB.png) ![Fedora](/obscure-tutorials/img/icons/platforms/FED.png) ![Archlinux](/obscure-tutorials/img/icons/platforms/ARL.png) ![Linux](/obscure-tutorials/img/icons/platforms/BSD.png) | ❌ | ✅ | Advanced |

<!--| [Bitwarden Premium](https://bitwarden.com/download/) | ![Windows](/obscure-tutorials/img/icons/platforms/WIN.png) ![macOS](/obscure-tutorials/img/icons/platforms/MAC.png) ![Linux](/obscure-tutorials/img/icons/platforms/LIN.png) ![Ubuntu](/obscure-tutorials/img/icons/platforms/UBT.png) ![Debian](/obscure-tutorials/img/icons/platforms/DEB.png) ![Fedora](/obscure-tutorials/img/icons/platforms/FED.png) ![Android](/obscure-tutorials/img/icons/platforms/AND.png) ![iOS](/obscure-tutorials/img/icons/platforms/IOS.png) | ✅ | ✅ | ✅ | Costs money |-->

| App to avoid | Reason |
|-|-|
| ❌ Google Authenticator | Bad vendor lock-in, no sync |
| ❌ Microsoft Authenticator | Bad vendor lock-in, very buggy |

## After you have chosen an app

Before starting, you should consider performing [a malware checkup and browser checkup procedure](/obscure-tutorials/docs/security-tips/full-malware-checkup) to defang any current compromise on your PC from being able to steal authentication info.

In this example, we will use Authy. Login to your account by visiting [account.microsoft.com](https://account.microsoft.com) or search the web for `login to microsoft account`.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/1.png" >}}

Scroll down and click `Security`

{{< figure src="/obscure-tutorials/img/microsoft-2fa/2.png" >}}

Scroll down and click `Two step verification - Turn on`.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/3.png" >}}

Click `Next`.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/4.png" >}}

Click `set up a different Authenticator app` to avoid the [dark pattern](https://en.wikipedia.org/wiki/Dark_pattern).

Why? The Microsoft Authenticator app is buggy and has vendor lock-in preventing you from easily switching to other services.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/5.png" >}}

Go to your authenticator app and create a new entry. In this example we are using Authy.

{{< figure src="/obscure-tutorials/img/authy/1.png" >}}

Scan the QR code, or type in the code it generates.

**Tip:** You can copy this QR code or the text for later reference, and you can add the code to multiple different apps for redundancy.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/6.png" >}}

{{< figure src="/obscure-tutorials/img/authy/2.png" >}}

Give it a name and an icon (optional) and set the token length to 6-digit. Click `Save`.

{{< figure src="/obscure-tutorials/img/authy/3-microsoft.png" >}}

Copy the 6-digit code it generates into the Microsoft website to verify that it is working properly. Click `Next`.

{{< figure src="/obscure-tutorials/img/authy/4-microsoft.png" >}}
{{< figure src="/obscure-tutorials/img/microsoft-2fa/7.png" >}}

You are done! Make a paper backup of your backup codes if you wish.

{{< figure src="/obscure-tutorials/img/microsoft-2fa/8.png" >}}

---

© lordpipe

Licensed CC BY — copy this document for your own use.

