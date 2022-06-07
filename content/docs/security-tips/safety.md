---
title: "Tips for staying safe online during a cyber-war"
description: "Examples of common Discord scams and advice for keeping your accounts safe. Article written by lordpipe"
weight: 1
---

The Russo-Ukrainian cyberwar has suddenly revealed many vulnerabilities in software and web services &mdash; many of which are now being used on random people. **Below are some general tips for staying safe while playing Minecraft and using Discord, as well as some general internet safety advice, to lower your footprint to getting hacked or other problems.**

This article is geared towards being advice for the staff of the UltraVanilla Minecraft server, but you may copy and adapt for your own use under the terms of the CC-BY license.

## {{% header-icon src="img/icons/password-dark.svg" classes="dark-only" %}} {{% header-icon src="img/icons/password-light.svg" classes="light-only" %}} Use strong passwords, and don't give them away

If someone has borrowed your account in the past, change your password now. If you use the same Minecraft/Discord password as other websites, change your password now.

{{% warning %}}
You may have heard various outdated advice from intitutional IT departments. Nowadays, passwords strength cannot be reliably determined by simplistic rules like "include special characters" or "use at least 10 characters". Instead, use the [How Secure is My Password](https://www.security.org/how-secure-is-my-password/) tool.
{{% /warning %}}

Consider [enabling 2-factor authentication](/obscure-tutorials/docs/security-tips/discord-2fa/) on your accounts.

Lock your computer when not in use, if you live with younger family members they almost certainly wish to screw up your computer!

Consider using a password manager that supports master passphrase encryption.

- Related article: [How to enable 2-factor authentication on Discord](/obscure-tutorials/docs/security-tips/discord-2fa/) by lordpipe
- Related article: [How to use TOTP 2-factor auth on a Microsoft account](/obscure-tutorials/docs/security-tips/microsoft-2fa/) by lordpipe    
  **Note:** the above instructions do not require the Microsoft app
- Related article: [How to enable automatic screen locking on Windows and macOS](/obscure-tutorials/docs/security-tips/auto-screen-lock/) by lordpipe

## {{% header-icon src="img/icons/report.svg" %}} Know how to report

You should familiarize yourself with how to report posts, comments, or behaviors that are in violation of the guidelines of any online community you are a part of.

{{% uv-specific %}}

**UltraVanilla:** We have **#grief-and-theft-reporting** channel and a **@Staff** ping, and you can also contact staff members privately. I vouch for all of the staff members. They are all trained the same and are vetted for maturity and alignment with our values of being respectful and competent.

{{% /uv-specific %}}

- Related external resource: [How to report issues to Discord](https://support.discord.com/hc/en-us/articles/360000291932-How-to-Properly-Report-Issues-to-Trust-Safety)
- Related external resource: [How to report issues to Reddit](https://reddit.zendesk.com/hc/en-us/articles/360058309512-How-do-I-report-a-post-or-comment-)

## {{% header-icon src="img/icons/malware.svg" %}} Avoid downloading malware and adware

Malware can steal accounts, and some malware even causes Minecraft to crash.

Avoid account stealing tools such as MCLeaks or AltDispenser, as they will screw up your ability to login to Minecraft even after uninstalling. If you have used a tool like this in the past, please join the Minecraft Community Support discord for help with removing.

Consider installing the [StopModReposts](https://stopmodreposts.org/) browser extension, which is specifically designed for safety against malware while browsing Minecraft-related websites.


{{% uv-specific %}}

**UltraVanilla**: Minecraft mod `.jar`s can only be posted to **#redstone-and-farms** by this list of trusted users: lordpipe, EcksD, Beeper, Spacewardharpy7, TheSecondLord, thewindmillman.

{{% /uv-specific %}}

- Related article: [How to run a full malware checkup](/obscure-tutorials/docs/security-tips/full-malware-checkup) by lordpipe

## {{% header-icon src="img/icons/ublock.svg" %}} Install an ad blocker

[uBlock Origin](https://ublockorigin.com/) can be installed for most web browser and considerably increases your resilience to malware websites. It also cuts down on your data usage.

## {{% header-icon src="img/icons/stop-phishing.svg" %}} Avoid phishing

Below are some examples of phishing attempts. Report them to the platform you find them on.

{{< figure src="/obscure-tutorials/img/phishing-examples/fMwrMlh.png" title="Discord nitro scam" >}}

{{< figure src="/obscure-tutorials/img/phishing-examples/1sGyLUt.png" title="Discord login scam — Looks identical to normal login screen. Scanning the fake QR code is just as dangerous as entering a password. Check the URL!" >}}

{{< figure src="/obscure-tutorials/img/phishing-examples/uf2Zduh.png" title="Video game developer scam. With this type of scam, advanced social engineering tactics may be used, possibly even building up trust over a period of several months." >}}

{{< figure src="/obscure-tutorials/img/phishing-examples/two-links.png" title="In this scam, a real Discord URL is placed visually close to where the embed for a fake URL is. Embeds always show up at the end of the message, no matter where the URL is, and their styling can be faked to look like anything!" >}}

{{< figure src="/obscure-tutorials/img/phishing-examples/mod-academy.png" title="Fake moderator academy page." >}}

{{< figure src="/obscure-tutorials/img/phishing-examples/mojang.png" title="Mojang account scam. Your transaction ID is sensitive info, as it can be used to steal a Minecraft account." >}}

## {{% header-icon src="img/icons/question.svg" %}} Be cautious with personal information and IRL meetups

Don't post too much identifying information. If you ever see anything online that you find particularly upsetting, or are unsure about a situation, tell someone you trust.

## {{% header-icon src="img/icons/heart.svg" %}} Be nice to people

The golden rule is pretty good. Avoiding stepping on people’s toes keeps you safe.

{{% uv-specific %}}

## {{% header-icon src="img/icons/lock.svg" %}} Appendix: UltraVanilla staff policy

Moderators and above must:

- Review the above scam examples
- Have a secure password, following the above advice
- [Enable screen locking](/obscure-tutorials/docs/security-tips/auto-screen-lock/) if living with weird people
- [Enable 2-factor authentication on Discord](/obscure-tutorials/docs/security-tips/discord-2fa/)
- Install an ad blocker or equivalent/stronger security software
- Run a [one-time full malware checkup](/obscure-tutorials/docs/security-tips/full-malware-checkup/). If you are on Windows this includes RKill + Malwarebytes + ADWCleaner + Browser checkup procedure, but you are not required to run Sophos HitmanPro or Windows Defender.

Additionally, Admins must:

- [Enable 2-factor authentication (TOTP or Microsoft app) on Microsoft account](/obscure-tutorials/docs/security-tips/microsoft-2fa/)

{{% uv-specific %}}

---

© lordpipe

Licensed CC BY — copy this document for your own use.

Copyright © Uri Herrera and others (KDE Breeze icons)

Copyright © Twitter (Twemoji)
