# The Ultimate iOS Hardening Guide

[![English](https://img.shields.io/badge/English-active-2ea44f?style=for-the-badge)](README.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-lire-0969da?style=for-the-badge)](README.fr.md)

## Table of Contents
1. [Introduction](#introduction)
2. [Choosing the Right Device: Device Selection and Biometric Security](#choosing-the-right-device-device-selection-and-biometric-security)
3. [Purchasing iOS Devices Anonymously](#purchasing-ios-devices-anonymously)
4. [Initial Setup and Apple ID: Best Practices](#initial-setup-and-apple-id-best-practices)
5. [Passcodes and Encryption](#passcodes-and-encryption)
6. [Enable Find My](#enable-find-my)
7. [Enable Automatic Updates](#enable-automatic-updates)
8. [Two-Factor Authentication](#two-factor-authentication)
9. [Optimizing Tracking and Location Services](#optimizing-tracking-and-location-services)
10. [Advanced Location Services and Tracking: Disabling for Privacy](#advanced-location-services-and-tracking-disabling-for-privacy)
11. [Biometric ID Considerations and Legal Implications](#biometric-id-considerations-and-legal-implications)
12. [Enhancing Lock Screen Security](#enhancing-lock-screen-security)
13. [Disable Control Center when locked](#disable-control-center-when-locked)
14. [Enable Stolen Device Protection](#enable-stolen-device-protection)
15. [Managing App Permissions](#managing-app-permissions)
16. [Disabling Tracking and Ad Tracking](#disabling-tracking-and-ad-tracking)
17. [Using VPN and Firewall for Enhanced Security](#using-vpn-and-firewall-for-enhanced-security)
18. [VPN and DNS Configurations for Enhanced Privacy](#vpn-and-dns-configurations-for-enhanced-privacy)
19. [Privacy-Focused Alternatives to Apple Apps](#privacy-focused-alternatives-to-apple-apps)
20. [Secure Messaging Apps](#secure-messaging-apps)
21. [Privacy-focused Browsers](#privacy-focused-browsers)
22. [Secure Email Providers](#secure-email-providers)
23. [App Sandboxing](#app-sandboxing)
24. [Secure Wireless Connections](#secure-wireless-connections)
25. [Threat Modeling](#threat-modeling)
26. [Security Auditing Tools](#security-auditing-tools)
27. [Siri Privacy Settings](#siri-privacy-settings)
28. [Securing iCloud Settings](#securing-icloud-settings)
29. [Safari Privacy and Security Settings](#safari-privacy-and-security-settings)
30. [Detailed Privacy Settings Adjustments](#detailed-privacy-settings-adjustments)
31. [Live Listen (Real-Time Listening)](#live-listen-real-time-listening)
32. [Staying Secure with iOS Updates](#staying-secure-with-ios-updates)
33. [Physical Security Measures for Your Device](#physical-security-measures-for-your-device)
34. [The Risks of Jailbreaking](#the-risks-of-jailbreaking)
35. [Secure Backups](#secure-backups)
36. [Alternatives to Data Transfer and iCloud](#alternatives-to-data-transfer-and-icloud)
37. [Screen Time & Restrictions for Added Security](#screen-time--restrictions-for-added-security)
38. [Optimizing System Services for Privacy](#optimizing-system-services-for-privacy)
39. [Understanding and Using Lockdown Mode](#understanding-and-using-lockdown-mode)
40. [Learn to use Emergency SOS](#learn-to-use-emergency-sos)
41. [Enable USB Restricted Mode](#enable-usb-restricted-mode)
42. [Managing Emergency Alerts and Addressing False Privacy Warnings](#managing-emergency-alerts-and-addressing-false-privacy-warnings)
43. [Password Management and Account Security](#password-management-and-account-security)
44. [Privacy Implications of iCloud Backups](#privacy-implications-of-icloud-backups)
45. [Threat Modeling Scenarios](#threat-modeling-scenarios)
46. [Securely Disposing of Old Devices](#securely-disposing-of-old-devices)
47. [Privacy Trade-offs of Find My](#privacy-trade-offs-of-find-my)
48. [Securely Using Apple Pay and Wallet Features](#securely-using-apple-pay-and-wallet-features)
49. [Educating Family and Friends about Secure Practices](#educating-family-and-friends-about-secure-practices)
50. [Managing IoT Devices and Their Access](#managing-iot-devices-and-their-access)
51. [Contextualizing Jailbreaking Risks](#contextualizing-jailbreaking-risks)
52. [Regular Updates and Revisions](#regular-updates-and-revisions)
53. [Often-Overlooked Hardening Tricks (iOS 16–27)](#often-overlooked-hardening-tricks-ios-1627)
54. [External Resources for Further Learning](#external-resources-for-further-learning)
55. [Feedback and Contributions](#feedback-and-contributions)

## Introduction
Welcome to the Ultimate iOS Hardening Guide! This guide is designed to enhance the security and privacy of iPhones and iPads for users at all levels, from beginners to advanced. We explore and explain Apple's security features, their limitations, and provide alternative solutions for robust privacy and security within the Apple ecosystem.

## Choosing the Right Device: Device Selection and Biometric Security

When selecting an iOS device, it's crucial to consider the security features offered by different models. Apple continuously addresses security bugs and introduces new security enhancements with each new generation of iPhones and iPads.

**Upgrade to an A12 CPU or higher:**
In the latest models, Apple has made significant changes to address the [checkm8](https://www.theiphonewiki.com/wiki/Checkm8_Exploit) vulnerability and improve overall device security. The CPU (Central Processing Unit) is the "brain" of your device, responsible for executing instructions and handling security features. The checkm8 vulnerability is a permanent issue affecting devices with A11 chips and older, allowing attackers with physical access to run unauthorized code on your device.

By introducing Pointer Authentication Codes (PAC) in devices with A12 CPUs and newer, Apple has vastly improved the security of newer iOS devices. PAC uses cryptography to make certain attacks much harder, and it depends on features available starting with the A12 CPU, which are present in most devices released in 2018 and all devices released since 2019.

**Recommendation:**
The only fix for the checkm8 vulnerability is to replace your device with one that has an A12 or later CPU. If you're using an older device, consider upgrading to a newer model to protect yourself from this vulnerability and benefit from the improved security features offered by the latest iOS devices.

**Biometric Security:**
When setting up your device, you'll have the option to enable biometric authentication using Face ID or Touch ID, depending on your device model. While these features offer convenience, it's essential to understand the legal and security implications of using biometric authentication. In some jurisdictions, law enforcement may be able to compel you to unlock your device using your face or fingerprint, whereas a passcode may offer more legal protection.

Consider your threat model and the legal implications in your area when deciding whether to enable biometric authentication. If you do choose to use Face ID or Touch ID, be sure to also set a strong passcode as a backup authentication method.

## Purchasing iOS Devices Anonymously

To maintain anonymity when purchasing an iOS device, follow these best practices:

- **Pay with cash**: Purchase iOS devices with cash at physical stores to avoid leaving a digital trail. 

- **Avoid in-store setup or registration**: Decline any setup or registration offered in-store, as this may link your personal information to the device.

- **Use prepaid cards for online purchases**: If purchasing online, use a prepaid credit card or gift card to maintain anonymity. Avoid using personal credit cards or payment methods linked to your identity.

- **Limit personal information**: When purchasing in-store, avoid providing any personal information, such as your email address or phone number, even if asked by the store representative. If you need to provide a name for the purchase, consider using a pseudonym or a generic name not linked to your real identity.

- **Avoid using loyalty cards or memberships**: Don't purchase devices from stores where you have a membership or loyalty card, as these can be linked to your personal information.

- **Use a PO box or mailbox service**: If you need to have the device shipped, consider using a PO box or a mailbox service that allows you to receive packages without revealing your home address.

- **Set up the device privately**: After purchasing the device, avoid setting it up or connecting to Wi-Fi networks in the store. Wait until you are in a private, secure location to begin the setup process.

- **Provide minimal information during setup**: During the initial setup, skip or provide minimal information when prompted for Apple ID, email, or other personal details. You can always add this information later, if needed, in a more secure environment.

Remember, the goal is to minimize the amount of personal information associated with the purchase and initial setup of the device. By taking these precautions, you can help maintain your anonymity and reduce the risk of your personal data being linked to your iOS device.

## Initial Setup and Apple ID: Best Practices
Start with a new or factory reset device. Set up your Apple ID away from personal networks and use non-personal information for the account. During the initial setup, disable all connectivity options like Wi-Fi, Bluetooth, and cellular data.

## Passcodes and Encryption
- **Strong Passcode**: Opt for at least a 6-digit passcode, or better yet, an alphanumeric one for higher security.
- **Biometric Security**: Use Face ID or Touch ID with an understanding of the legal and privacy implications.
- **Advanced Options**: Turn off 'Simple Passcode' for more complex passcode options.
- **Data Protection**: Always enable data protection and keychain protection in your settings.

## Enable Find My

Use Find My to locate, lock, or erase your device if it gets lost or stolen. A locked iPhone cannot be reused without your Apple ID credentials, even if the phone is wiped and has its software reinstalled.

**What is Find My?**

Find My is a built-in app that allows you to:
- Locate your device on a map
- Play a sound to help you find your device
- Mark your device as lost and lock it with a passcode
- Erase your device remotely if needed

**Set up Find My:**
1. Open the Settings app.
2. Tap on your name at the top of the screen.
3. Tap on "Find My".
4. Enable the "Find My iPhone" option.
5. Enable "Find My network" to locate your iPhone even when it's offline, in power reserve mode, or after power off.
6. Enable "Send Last Location" to automatically send the location of your iPhone to Apple when the battery is critically low.

If you're asked to sign in, enter your Apple ID credentials. When you set up Find My, any paired Apple Watch and AirPods are automatically set up as well.

**Find My network:**
Participating in the Find My network allows you to locate your iPhone even when it's offline, in power reserve mode, or after power off. This is a crucial feature that increases the chances of recovering your device if it's lost or stolen.

**Send Last Location:**
Enabling "Send Last Location" ensures that your iPhone automatically sends its location to Apple when the battery is critically low. This information can be vital in locating your device if it runs out of power.

**Recommendation:**
It's essential to enable Find My on your iPhone or iPad, along with the "Find My network" and "Send Last Location" features. These settings provide an extra layer of security, making it much harder for thieves to resell or use your device if it's ever lost or stolen. Even if your device is wiped and the software is reinstalled, it will remain locked and unusable without your Apple ID credentials.

## Enable Automatic Updates
Turn on automatic updates under `Settings → General → Software Update → Automatic Updates` to ensure your device always has the latest security patches.

## Two-Factor Authentication
Two-factor authentication adds a critical layer of security. It combines something you know (your password) and something you have (your device). 

When enabled, you'll need to provide both your password and a six-digit verification code to sign in to your Apple ID account. This code is displayed automatically on your trusted devices or sent to your phone number. Even if someone knows your password, they won't be able to access your account without also having access to your trusted device or phone number.

Apple's two-factor authentication is different from two-step verification. If you're using two-step verification and want to upgrade to two-factor authentication, you'll need to turn off two-step verification and then turn on two-factor authentication.

To activate two-factor authentication:
1. Go to `Settings → [Your name] → Password & Security`
2. Tap `Turn On Two-Factor Authentication`
3. Follow the setup prompts

## Optimizing Tracking and Location Services
Privacy is key. Here's how to optimize your tracking and location settings:

1. Go to `Settings → Privacy & Security → Tracking`
2. Toggle off `Allow Apps to Request to Track` to prevent apps from tracking your activity across other companies' apps and websites for advertising purposes or sharing your information with data brokers
3. Go to `Settings → Location Services` to manage app permissions for location access
   - Choose to allow location access always, only while using the app, or never
   - For apps that don't need your precise location, consider granting access to your approximate location instead
4. Regularly review which apps have location permissions and revoke access for apps that don't need it

## Advanced Location Services and Tracking: Disabling for Privacy
Post-setup, regularly verify location and tracking settings, especially after iOS updates. Updates may reset your preferences or introduce new settings. Here are some additional steps to minimize tracking:

1. Go to `Settings → Privacy & Security → Location Services → System Services`
2. Consider disabling non-essential location services like location-based suggestions and ads
3. Check for any apps that are requesting background location access
   - Background access allows apps to track your location even when you're not actively using them
   - Only grant background access to apps that truly need it, such as navigation or fitness tracking apps

## Biometric ID Considerations and Legal Implications
Biometrics like Touch ID and Face ID are convenient but have legal implications. In some jurisdictions, law enforcement can compel you to unlock your device with your face or fingerprint, but they cannot force you to disclose your passcode.

Consider scenarios where biometrics might be less secure than a passcode:
- Someone could unlock your device while you're sleeping or unconscious
- In a robbery or kidnapping situation, you could be physically forced to unlock your device

If you do choose to use biometrics:
- Make sure to also set a strong passcode as a backup
- Remember, you can always disable biometrics quickly by pressing the power button five times in succession, which will require your passcode to unlock

## Enhancing Lock Screen Security
Your lock screen can be a vulnerability. To enhance lock screen security:

1. Go to `Settings → Touch ID/Face ID & Passcode`
2. Disable access to features like Today View, Notification Center, Control Center, Siri, Reply with Message, Home Control, Wallet, and USB Accessories while your device is locked
   - The fewer features accessible from the lock screen, the more secure your device will be
3. Go to `Settings → Display & Brightness → Auto-Lock` and set a reasonably short auto-lock timeout
   - This ensures your device will lock quickly when not in use, even if you forget to lock it manually

## Disable Control Center when locked

Disable access to Control Center when your device is locked to prevent unauthorized changes to your settings. By default, Control Center can be accessed from the lock screen, which introduces an unnecessary security risk.

For example, a thief could snatch your phone and quickly disable the cellular and Wi-Fi connections, preventing you from locating it with Find My. Additionally, settings such as Bluetooth or AirDrop, which you may have disabled to decrease your risk, can be re-enabled unless you follow these steps:

1. Open the Settings app.
2. Tap on one of the following, depending on your device's configuration:
   - Face ID & Passcode
   - Touch ID & Passcode
   - Passcode
3. Enter your passcode.
4. Scroll to the "Allow Access When Locked" section.
5. Uncheck "Control Center".
6. Also uncheck any other features you don't use.

By disabling Control Center access when your device is locked, you can prevent unauthorized changes to your settings and reduce potential security risks.

## Enable Stolen Device Protection
Stolen Device Protection adds a layer of security when your iPhone is away from familiar locations, such as home or work, and helps protect your accounts and personal information in case your iPhone is ever stolen.

To turn on Stolen Device Protection, you must use two-factor authentication for your Apple ID and set up or enable the following on your iPhone: a device passcode; Face ID or Touch ID; and Significant Locations* (Location Services). You also need to have Find My turned on, and you can't turn it off while Stolen Device Protection is enabled.

When Stolen Device Protection is enabled, some features and actions have additional security requirements when your iPhone is away from familiar locations:

- **Face ID or Touch ID biometric authentication**: Some actions such as accessing stored passwords and credit cards require a single biometric authentication with Face ID or Touch ID — with no passcode alternative or fallback — so that only you can access these features.
- **Security Delay**: Some security actions such as changing your Apple ID password also require you to wait an hour and then perform a second Face ID or Touch ID authentication.

You can turn on Stolen Device Protection in Settings:

1. Go to Settings, then tap Face ID & Passcode.
2. Enter your device passcode.
3. Tap Stolen Device Protection, then turn Stolen Device Protection on or off.

If you'd like your iPhone to enforce the additional Stolen Device Protection security measures regardless of its location, choose "Always" under Require Security Delay. By default, the additional security measures are required only when your iPhone is away from familiar locations.

*Significant Locations is an option within Location Services: Settings > Privacy & Security > Location Services > System Services > Significant Locations.

## Managing App Permissions
Review app permissions regularly in your device settings, paying special attention to access to the microphone, camera, and location services.

## Disabling Tracking and Ad Tracking
To limit ad tracking, navigate to `Settings → Privacy & Security → Apple Advertising` and disable 'Personalized Ads'.

## Using VPN and Firewall for Enhanced Security
Protect against Wi-Fi hacking and mask your IP address with a reliable VPN. This is crucial for maintaining privacy on public networks.

## VPN and DNS Configurations for Enhanced Privacy
Choose a privacy-respecting VPN provider and configure it not to log your data. Use DNS services for additional filtering and privacy.

## Privacy-Focused Alternatives to Apple Apps
Consider using privacy-centric alternatives to native Apple apps, such as:
- Safari → [Brave](https://brave.com) (see iOS browser comparison [here](https://privacytests.org/ios))
- iMessage → [Signal](https://signal.org)
- iCloud → [Proton Drive](https://proton.me/drive)
- iCloud Keychain → [Bitwarden](https://bitwarden.com) / [Proton Pass](https://proton.me/pass)
- Apple Calendar → [Proton Calendar](https://proton.me/calendar) 
- iCloud Private Relay (VPN) -> [MullvadVPN](https://mullvad.net/en) / [IVPN](https://www.ivpn.net) / [Proton VPN](https://protonvpn.com)
- Apple Mail -> [Proton Mail](https://proton.me/mail)
- Apple Notes -> [Standard Notes](https://standardnotes.com)
- iCloud Photos -> [ente](https://ente.io) ([ente vs Apple Photos](https://ente.io/compare/ente-vs-apple-photos))

Each alternative is selected for its strong focus on user privacy and security features.

## Secure Messaging Apps
When choosing a secure messaging app, consider the following options:
- Signal: An open-source, end-to-end encrypted messaging app that has been widely adopted and recommended by security experts.
- SimpleX Chat: A decentralized, open-source messaging platform that offers end-to-end encryption, no user identifiers (like phone numbers or usernames), and enhanced privacy features.
- Threema: A paid app that offers end-to-end encryption, doesn't require a phone number, and has a strong focus on privacy and security.

For a comprehensive comparison of secure messaging apps, visit [Secure Messaging Apps](https://www.securemessagingapps.com). This website compares various messaging apps based on their security features, privacy policies, and other important factors, helping you make an informed decision.

## Privacy-focused Browsers
When it comes to privacy-centric browsers, consider the following options:
- Brave: A Chromium-based browser with built-in ad and tracker blocking, as well as a privacy-focused incognito mode.
- Firefox Focus: A free, open-source browser with built-in tracking protection, ad-blocking, and the ability to erase your sessions easily.

These browsers offer robust privacy features to help protect your online activities from tracking and surveillance.

## Secure Email Providers
For secure and private email communication, consider the following providers:
- ProtonMail: An end-to-end encrypted email service that offers a free tier and paid plans with additional features.
- Tutanota: A free, open-source email service with end-to-end encryption, two-factor authentication, and the ability to send encrypted emails to non-Tutanota users.

To compare various secure email providers, visit [Email Provider Comparison](https://email-comparison.as93.net). This website offers a detailed comparison of email providers based on their security features, privacy policies, jurisdiction, and other crucial factors.

By carefully selecting a secure messaging app, privacy-focused browser, and secure email provider, you can significantly enhance your privacy and security when communicating and browsing online.

## App Sandboxing
iOS's app sandboxing is a critical security feature that contributes to the overall security of the device by isolating apps from each other and limiting their access to system resources.

Key benefits of app sandboxing:
1. **Data Protection**: Each app has its own dedicated space for storing data, preventing unauthorized access from other apps.
2. **Resource Access**: Apps can only access system resources, like the camera or location, with explicit user permission.
3. **Inter-App Communication**: Communication between apps is restricted to specific iOS APIs, preventing data theft or interference.
4. **Privilege Separation**: Apps run with the lowest level of privilege needed, minimizing potential damage if compromised.

While largely invisible to users, app sandboxing is essential to iOS security. However, it can be weakened by jailbreaking or sideloading apps from outside the App Store, exposing your device to greater risk.

## Secure Wireless Connections
Securing your wireless connections is crucial for protecting your data in transit. Here are some best practices:

1. **Use WPA3 encryption for Wi-Fi**: 
   - Choose WPA3 if your router supports it, as it offers the best protection against password guessing and encryption cracking.
   - If WPA3 isn't available, use WPA2 with AES encryption.
   - Avoid WPA, WEP, or open networks, as they are much less secure.

2. **Avoid unsecured public Wi-Fi**: 
   - Public Wi-Fi hotspots are often unsecured or poorly secured, exposing your data to interception.
   - If you must use public Wi-Fi, connect to a VPN first to encrypt your data (see VPN section for details).
   - Avoid accessing sensitive information, like banking, while on public Wi-Fi, even with a VPN.

3. **Use cellular data instead of Wi-Fi**: 
   - Cellular networks are generally more secure than public Wi-Fi, using encryption and being harder to intercept.
   - Be mindful of data costs, especially when roaming or on a limited plan.

4. **Keep your devices updated**: 
   - Install updates for your iOS devices and routers as soon as available.
   - Updates often include security patches for newly discovered vulnerabilities in Wi-Fi protocols and implementations.

By following these best practices, you can significantly reduce the risk of your wireless connections being compromised and your data being intercepted.

## Threat Modeling
Assess your individual security needs based on your specific situation and potential threats you may face. Threat modeling helps you identify, understand, and prioritize the potential threats and vulnerabilities specific to your situation. Consider the following aspects when threat modeling:

1. **Identify your assets**: Determine what you need to protect, such as personal data, financial information, or confidential business materials.

2. **Identify potential adversaries**: Consider who might want to access or compromise your assets. This could include hackers, thieves, government agencies, or even people you know.

3. **Identify potential attack vectors**: Think about the different ways an adversary could access your assets, such as physical theft, network hacking, social engineering, or malware.

4. **Evaluate the likelihood and impact of threats**: Assess how likely each threat is to occur and the potential damage it could cause. Prioritize the threats that are most likely and would have the greatest impact.

5. **Determine appropriate mitigations**: Based on your threat assessment, identify the security measures that would most effectively mitigate your top threats. This could include measures like strong encryption, two-factor authentication, physical security controls, or using privacy-focused apps and services.

Remember, threat modeling is not a one-time exercise. As your situation and the broader security landscape evolve, periodically reassess your threats and adjust your security posture accordingly.

### Threat Modeling Resources
- [EFF Surveillance Self-Defense Guide](https://ssd.eff.org/): Includes a section on assessing your risks and creating a security plan.
- [OWASP Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling): Provides a primer on threat modeling for application security, but many of the principles apply more broadly.

By taking the time to understand your unique threat landscape, you can ensure you're focusing your security efforts where they'll have the greatest impact in keeping your iOS devices and data safe.

## Security Auditing Tools
Consider using security auditing tools like [iVerify](https://www.iverify.io) to check your device for security vulnerabilities and misconfigurations.

## Siri Privacy Settings
Manage Siri's access under `Settings → Siri & Search` for better privacy. Consider disabling 'Listen for "Hey Siri"' to minimize data sharing.

## Securing iCloud Settings
Regularly review your iCloud settings. Enable two-factor authentication and use end-to-end encryption where possible.

## Safari Privacy and Security Settings
Enhance your privacy in Safari by enabling Fraudulent Website Warnings and managing cookies effectively. Consider disabling JavaScript for added security.

## Detailed Privacy Settings Adjustments
Limit Siri's access and turn off notifications for sensitive apps. In Safari, use private browsing and disable suggestions—opt-out of analytics data sharing for enhanced privacy.

## Live Listen (Real-Time Listening)

Live Listen turns iPhone into a remote microphone: sound captured by the iPhone is streamed live to AirPods, compatible Beats headphones, or Made for iPhone (MFi) hearing devices. It is an accessibility feature, but it can also be used to listen to a conversation from a distance, so it is worth checking that it is not running unexpectedly.

**Timeline**
- 2014: launched for MFi hearing devices.
- iOS 12 (2018): extended to AirPods.
- iOS 14.3 (2020): minimum version required by Apple for AirPods and Beats.
- iOS 26 (2025): added Live Captions and control from Apple Watch or another device signed in to the same Apple Account.

**Listening session vs. Remote Control**
Two different settings are available under `Settings → Accessibility → Audio & Visual → Live Listen`:
- **The listening session** ("Start / Stop Live Listen"): only this actually turns on the microphone. If it is stopped, no listening is taking place.
- **"Remote Control"**: allows a nearby device signed in to the same Apple Account (Apple Watch, another iPhone or iPad) to start, stop, or rewind a session. This may be enabled by default on recent iOS versions; being checked does not mean a session is active, but it lets a trusted device start one.

**Check that no session is active**
1. Open Control Center: the Live Listen button should not be highlighted.
2. In `Settings → Accessibility → Audio & Visual → Live Listen`, the session should be stopped (the button should read "Start Live Listen").
3. An orange dot (or red pill) at the top of the screen means the microphone is in use; check which app or feature is responsible.
4. On iOS 18 and earlier, use `Control Center → Hearing → [your AirPods] → Live Listen`. For hearing devices: `Settings → Accessibility → Hearing Devices`.

**Disable and lock down**
1. Stop any active session (Control Center or the setting above).
2. Turn off **"Remote Control"** if you do not use an Apple Watch or hearing device.
3. Remove the "Live Listen" / "Hearing" control from Control Center (`Settings → Control Center`).
4. Remove it from the Accessibility Shortcut (`Settings → Accessibility → Accessibility Shortcut`).
5. On Apple Watch, remove the "Hearing" control from its Control Center.
6. For hearing devices, turn off "Control on Lock Screen" under `Settings → Accessibility → Hearing Devices`.
7. Review the devices signed in to your Apple Account and remove any you do not recognize.

**Not to be confused with:** Siri and "Hey Siri" (wake-word listening), Sound Recognition, Live Captions, and microphone permission granted to apps (`Settings → Privacy & Security → Microphone`).

**References:** [Use iPhone as a remote microphone with Live Listen](https://support.apple.com/guide/iphone/use-live-listen-iph8bf9386f5/ios) · [Control Live Listen on iPhone from Apple Watch](https://support.apple.com/guide/watch/control-live-listen-apd4f5b634f3/watchos).

## Staying Secure with iOS Updates
Regularly update your iOS to the latest version to benefit from the newest security patches. Keep your apps updated as well.

## Physical Security Measures for Your Device
Never leave your device unattended in public places. Use features like Find My iPhone for theft recovery. Use a protective case, screen protector, and keep the device away from extreme temperatures.

## The Risks of Jailbreaking
Jailbreaking exposes your device to additional security risks. It's generally advised to avoid jailbreaking for maintaining device security.

## Secure Backups
Always use encrypted backups and regularly test backup restores to ensure data integrity.

## Alternatives to Data Transfer and iCloud
Explore secure cloud services like Proton Drive and prefer physical data transfers (like USB) over wireless ones for sensitive data.

## Screen Time & Restrictions for Added Security
Use Screen Time to enforce content and privacy restrictions, preventing unauthorized changes to your device settings. This is particularly useful if someone learns your device passcode.

## Optimizing System Services for Privacy
Fine-tune `Settings → Privacy & Security → Location Services → System Services`. Turn off non-essential services like `Location-Based Apple Ads` and `Significant Locations` to minimize location data collection.

## Understanding and Using Lockdown Mode
Lockdown Mode is designed for users at high risk of targeted cyber attacks. It limits certain functionalities to reduce the device's attack surface. Activate it under `Settings → Privacy & Security → Lockdown Mode`, but be aware that it will restrict many standard features. Familiarize yourself with Lockdown Mode and its implications.

## Learn to Use Emergency SOS

Emergency SOS is a critical feature that can help you quickly call for help and protect your device in dangerous situations. When activated, it disables Touch ID and Face ID until you enter your passcode, and optionally, it can automatically call emergency services (911 in the US).

**How to activate Emergency SOS:**

There are two ways to activate Emergency SOS:

1. **Call with 5 Button Presses**: Rapidly press the side button 5 times. When the countdown ends, iPhone will call emergency services.

2. **Call with Hold and Release**: Press and hold the side button and either volume button. A countdown begins and an alarm sounds. After the countdown, if you release the buttons, iPhone will call emergency services. In certain regions, you may need to specify an emergency service to dial.

If needed, you can call emergency services by sliding the Emergency SOS slider on the screen.

**Enabling Auto-Calling:**

You can set your device to automatically call emergency services after the Emergency SOS screen appears. The call will be made after an 8-second countdown. To enable auto-calling:

1. Open the Settings app.
2. Tap on Emergency SOS.
3. Enable the "Call with Hold" and "Call with 5 Presses" toggles.

There are two ways to use auto-calling:
1. Call after 5 presses: Continue holding the power and volume buttons for more than 10 seconds.
2. Call with Hold: Hold the buttons for more than 10 seconds.

**Setting Up Emergency Contacts:**

You can have Emergency SOS display an emergency contact by selecting "Set up Emergency Contacts in Health" in the Emergency SOS settings.

**Recommendations for Improvement:**

While Emergency SOS is a valuable feature, there are some potential enhancements that could make it even more effective:

- Implement a discreet gesture or button combination to trigger Emergency SOS more inconspicuously in dangerous situations.
- Allow users to customize the countdown timer for auto-calling (e.g., options for 3, 5, or 8 seconds).
- Enable sending automated emergency texts to designated contacts when Emergency SOS is activated, including location information if possible.
- Provide guidance on what information to convey to the emergency operator, especially in dangerous situations.
- Discuss using Emergency SOS in combination with other iOS emergency features like Medical ID and Emergency Contacts.

By familiarizing yourself with Emergency SOS and understanding how to activate it, you can be better prepared to respond to emergency situations and protect your device and personal information.

## Enable USB Restricted Mode

Enabling USB Restricted Mode further enhances the security of your iOS device. This feature prevents USB accessories from connecting when your device has been locked for over an hour, protecting against unauthorized access attempts via the Lightning port.

**How it works:** When USB Restricted Mode is enabled, your iPhone or iPad will not communicate with USB accessories if the device has been locked for more than an hour. This prevents potential attackers from using USB accessories to bypass the lock screen or extract data, even if they have physical access to your device.

**Protection against hacking tools:** USB Restricted Mode also defends against hacking tools like GrayKey and Cellebrite, which can be used to bypass the lock screen by connecting to the Lightning port. By enabling this feature, you add an extra layer of security to your device's passcode protection.

**Enabling USB Restricted Mode:**

1. Go to `Settings → Touch ID/Face ID & Passcode`.

2. Make sure the "Accessories" option is turned off under "Allow Access When Locked".

When this setting is off, your iPhone will display the following message:

"Unlock iPhone to allow accessories to connect when it has been more than an hour since your iPhone was locked."

This confirms that USB Restricted Mode is active and will prevent USB accessories from connecting if the device has been locked for over an hour.

**Why it matters:** Enabling USB Restricted Mode is especially important if your iPhone or iPad contains sensitive personal or business data. It helps ensure that this data remains secure even if your device is lost or stolen, providing a simple but effective way to enhance your device's security and protect against unauthorized access attempts.

## Managing Emergency Alerts and Addressing False Privacy Warnings
Understand that some government alerts may bypass your settings. Verify your settings if iOS flags a privacy warning due to DNS changes. Often, these can be dismissed for secure DNS setups.

## Password Management and Account Security
Use strong, unique passwords for all accounts, not just your device passcode. Consider using a password manager to generate and store complex passwords securely.

## Privacy Implications of iCloud Backups
iCloud backups, while convenient, may not provide the same level of privacy as local backups. Consider using secure alternatives for sensitive data.

## Threat Modeling Scenarios
Here are a few common threat scenarios and the most relevant security measures for each:

1. **Lost or Stolen Device**: Enable Find My, use a strong passcode, and consider enabling Stolen Device Protection. Regularly back up your data.
2. **Targeted Cyber Attack**: Use Lockdown Mode, keep your device and apps updated, and be cautious about installing apps from unknown sources.
3. **Data Breaches**: Use unique, strong passwords for each account, enable two-factor authentication wherever possible, and monitor your accounts for suspicious activity.

## Securely Disposing of Old Devices
Before disposing of an old device, make sure to sign out of all accounts, perform a factory reset, and remove the SIM card. Physically destroy the device if it contained highly sensitive data.

## Privacy Trade-offs of Find My
While Find My is valuable for locating a lost or stolen device, it does mean sharing your device's location data with Apple. Consider this trade-off in your threat model.

## Securely Using Apple Pay and Wallet Features
When setting up Apple Pay or other wallet features, verify that you're on a trusted device and network. Use Touch ID, Face ID, or a strong passcode for transactions.

## Educating Family and Friends about Secure Practices
Your security is only as strong as your weakest link. Encourage family and friends to also follow good security practices, especially if you frequently communicate with them.

## Managing IoT Devices and Their Access
Be mindful of the IoT devices you connect to your Apple devices. Regularly review their permissions and access, and use strong, unique passwords for their accounts.

## Contextualizing Jailbreaking Risks
Jailbreaking allows users to bypass many of iOS's security restrictions, which can be appealing for customization and access to certain apps. However, it exposes the device to significant security risks and should be avoided for most users.

## Regular Updates and Revisions

### Staying Current with iOS Developments
- **Evolving Security Landscape**: The realm of iOS security and privacy is continually evolving. New updates from Apple often introduce changes in features, settings, and security protocols.
- **Commitment to Relevance**: We are committed to keeping this guide updated with the latest information and best practices. This ensures that the advice and strategies provided here remain relevant and effective.
- **Recommendation for Readers**: We encourage readers to revisit this guide periodically. Staying informed about the latest updates and revisions will help you maintain the highest level of security and privacy on your iOS devices.
- **Community Input**: Your feedback and contributions are invaluable in keeping this guide comprehensive and up-to-date. Please feel free to suggest updates or new information that might be beneficial to include.

### Keeping Up with iOS Updates
- **Checking for iOS Updates**: Regularly check for and install the latest iOS updates on your device. These updates often contain crucial security patches and feature enhancements.
- **Reviewing Guide Updates**: After updating your iOS, revisit this guide to ensure that your security settings and practices align with any new changes introduced by the update.

## Often-Overlooked Hardening Tricks (iOS 16–27)

The settings below are easy to miss because they are buried, enabled by default, or only appear after an update. None of them replaces the basics (strong passcode, two-factor authentication, updates, and backups); they close gaps that the rest of this guide does not cover. Apply them independently according to your threat model.

**If you only do eight things:** enable Advanced Data Protection with a recovery key or contact, add security keys if you are high-risk, set notification previews to “When Unlocked,” lock or hide sensitive apps, turn on App Privacy Report, enable Background Security Improvements, screen unknown callers and senders, and review trusted devices and app-specific passwords.

### Account, recovery, and identity

- **Advanced Data Protection (ADP).** Turns on end-to-end encryption for most iCloud data, including device backups, Photos, and Notes. Apple cannot read that data, but it also cannot recover it for you.
  - **Path:** `Settings → [your name] → iCloud → Advanced Data Protection`.
  - **Before enabling:** set a recovery contact or a 28-character recovery key and store it offline. ADP disables iCloud.com web access; temporary web access must be approved from a trusted device.
  - **Limits:** not available for child or managed accounts; Shared Albums, iWork collaboration, and “anyone with the link” sharing remain outside ADP.

- **Security keys for your Apple Account.** A FIDO-certified hardware key blocks phishing and remote interception of your second factor. You must enroll at least two keys (maximum six) and keep them in separate places.
  - **Path:** `Settings → [your name] → Sign-in & Security → Two-Factor Authentication → Security Keys`.
  - **Caveat:** if you lose every trusted device and every key, the account can be permanently locked. Child and managed accounts are not supported. Requires iOS 16.3 or later on all devices.

- **Recovery contacts, recovery key, and Legacy Contact.** These are three different mechanisms; set at least two. A recovery contact can give you a code, a recovery key is a 28-character secret you store offline, and a Legacy Contact can request access after your death.
  - **Paths:** `Settings → [your name] → Sign-in & Security → Recovery Contacts` / `Recovery Key` / `Legacy Contact`.
  - **Caveat:** a recovery key disables Apple’s standard account recovery; losing it can lock you out. Do not store it only in iCloud.

- **Audit trusted devices and app-specific passwords.** Old iPads, Macs, and app passwords are persistent backdoors.
  - **Path:** `Settings → [your name]` for the device list, and `appleid.apple.com → Sign-In & Security → App-Specific Passwords`.
  - Remove devices you no longer use and revoke passwords for old apps. Changing your Apple Account password does not always revoke app-specific passwords.

- **Safety Check.** Reviews who can see your location, photos, notes, calendar, and app permissions; Emergency Reset stops all sharing and guides you through securing the account.
  - **Path:** `Settings → Privacy & Security → Safety Check`.
  - **Caveat:** it cannot change third-party accounts, passwords, or data shared from another device; some options are unavailable with Screen Time restrictions or MDM. Use Quick Exit if you need to leave the screen immediately.

- **iMessage Contact Key Verification.** Alerts you if a sophisticated attacker impersonates a contact or compromises iMessage servers; manual verification compares a code in person or over a secure call.
  - **Path:** `Settings → [your name] → Contact Key Verification`.
  - **Requirements:** iOS 17.2 or later, two-factor authentication, iCloud Keychain, and a passcode on all devices. Both parties must enable it; it does not stop phishing or SMS scams.

- **Passkeys and compromised-password alerts.** Passkeys are phishing-resistant and synced end-to-end encrypted through iCloud Keychain. Turn on breach detection and review Security Recommendations.
  - **Path:** `Passwords app → Security`; `Settings → Apps → Passwords → Detect Compromised Passwords`.
  - **Caveat:** passkeys are only as safe as your device passcode and Apple Account; keep a hardware key or another recovery method.

### iCloud, email, and network

- **iCloud Private Relay.** Hides your IP address and DNS queries from websites and network operators by routing traffic through two relays. It is not a VPN: it does not change your apparent country or hide traffic from Apple.
  - **Path:** `Settings → [your name] → iCloud → Private Relay`.
  - **Caveat:** requires iCloud+; some networks, carriers, or countries do not support it. Turn it off per network if a captive portal or VPN conflicts.

- **Hide My Email.** Creates unique `@privaterelay.appleid.com` aliases that forward to your real address; disable an alias when it starts receiving spam.
  - **Path:** `Settings → [your name] → iCloud → Hide My Email`; also offered by Sign in with Apple.
  - **Caveat:** iCloud+ required; some services block relay addresses; aliases are not anonymous if you use them with identifying data.

- **Mail Privacy Protection.** Preloads remote content through two relays and hides your IP, so senders cannot reliably tell when or where you opened a message.
  - **Path:** `Settings → Apps → Mail → Privacy Protection → Protect Mail Activity`.
  - **Stronger option:** `Block All Remote Content` (images may not load). Requires `Limit IP Address Tracking`; it does not protect links or attachments you open.

- **Private Wi-Fi Address and Limit IP Address Tracking.** Use a different MAC address per network (Fixed or Rotating) and hide your IP from known trackers.
  - **Path:** `Settings → Wi-Fi → (i) next to the network → Private Wi-Fi Address` and `Limit IP Address Tracking`; cellular equivalent under `Settings → Cellular → Cellular Data Options`.
  - **Caveat:** captive portals, corporate Wi-Fi, and some routers may require the hardware address; use Fixed rather than Off when possible.

- **Encrypted DNS via a trusted profile.** DNS-over-HTTPS or DNS-over-TLS stops your ISP or hotspot from reading every domain you visit, but it does not hide the destination IP.
  - **Path:** install a configuration profile from a reputable resolver (Quad9, Cloudflare, NextDNS) via `Settings → General → VPN & Device Management`.
  - **Caveat:** a DNS profile can intercept all traffic; only install one you trust, and remove profiles you no longer use. DNS filtering is not a substitute for a VPN.

- **Stop auto-joining old and open Wi-Fi networks.** A phone that silently joins a familiar SSID is vulnerable to evil-twin hotspots.
  - **Path:** `Settings → Wi-Fi → Ask to Join Networks → Notify` (or Off); forget networks you no longer use; disable `Auto-Join Hotspot`.
  - **Caveat:** `Ask to Join` still prompts; verify the network name and use a VPN on untrusted networks.

### Lock screen, notifications, and apps

- **Notification previews.** Set previews to `When Unlocked` or `Never` so codes, messages, and medical alerts do not appear on a locked screen.
  - **Path:** `Settings → Notifications → Show Previews`.
  - **Also:** `Settings → Notifications → Screen Sharing` to hide notifications while sharing your screen; per-app overrides can re-enable previews.

- **Lock and hide apps.** Requires Face ID, Touch ID, or your passcode to open sensitive apps and removes them from search, notifications, and some system surfaces.
  - **Path:** touch and hold the app icon → `Require Face ID` → `Require Face ID` or `Hide and Require Face ID`.
  - **Caveat:** iOS 18 or later; built-in Apple apps cannot be hidden; hidden apps remain in the App Library’s Hidden folder and can be revealed with authentication.

- **App Privacy Report.** Shows which apps used the camera, microphone, location, contacts, photos, and other sensors, plus the domains they contacted.
  - **Path:** `Settings → Privacy & Security → App Privacy Report → Turn On App Privacy Report`.
  - Use it monthly: revoke sensors that do not match the app’s purpose, and investigate unexpected domains.

- **Strip location from photos before sharing.** Photos can carry GPS coordinates, timestamps, and device details.
  - **Path:** `Photos → open photo → Info (i) → Adjust → No Location`; when sharing, tap `Options` and turn off `Location` and `All Photos Data`.
  - **Caveat:** screenshots and some edited or exported images may retain metadata; use a metadata-removal tool for high-risk sharing.

- **Clipboard and third-party keyboards.** iOS asks before an app pastes from another app; do not grant `Allow Paste` to apps that do not need it. Third-party keyboards with `Full Access` can read what you type.
  - **Path:** `Settings → General → Keyboard → Keyboards → [keyboard] → Full Access` (turn off); review paste prompts as they appear.
  - **Caveat:** some keyboards need Full Access for glide typing or text replacement; prefer the built-in keyboard for passwords and sensitive messages.

- **Require Attention and Erase Data.** `Require Attention` prevents Face ID from unlocking while your eyes are closed; `Erase Data` wipes the device after 10 failed passcode attempts.
  - **Path:** `Settings → Face ID & Passcode → Require Attention` and `Erase Data`.
  - **Caveat:** Erase Data can be triggered by children or pranksters; keep backups. It is a last-resort protection, not a substitute for a strong passcode.

- **Audit the permissions people forget.** `Local Network`, `Bluetooth`, `Contacts` (limited access), and `Photos` (selected photos) are common leaks.
  - **Path:** `Settings → Privacy & Security → Local Network / Bluetooth / Contacts / Photos`.
  - Prefer `Limited Access` for photos and contacts; revoke Local Network from apps that do not need to discover devices.

### Calls, messages, and sharing

- **Call Screening (iOS 26 or later).** Unknown callers are asked to state their name and reason before your phone rings; you see a live transcript and decide whether to answer.
  - **Path:** `Settings → Apps → Phone → Screen Unknown Callers → Ask Reason for Calling` (or `Silence`).
  - **Caveat:** emergency calls disable screening for 24 hours; roaming calls are not screened; some callers hang up.

- **Screen unknown senders in Messages.** Moves texts from unknown numbers out of the main list and suppresses notifications; spam gets a separate folder.
  - **Path:** `Messages → Filters → Manage Filtering → Screen Unknown Senders` (and `Filter Spam`); or `Settings → Apps → Messages → Unknown Senders`.
  - **Caveat:** verification codes and delivery messages can be filtered; allow time-sensitive notifications or check the Unknown Senders folder.

- **AirDrop and NameDrop.** Set AirDrop to `Contacts Only` or `Receiving Off`; disable `Bringing Devices Together` so holding two iPhones together does not share your contact card.
  - **Path:** `Settings → General → AirDrop`.
  - **Caveat:** `Contacts Only` still allows anyone in your contacts; `Receiving Off` is best in crowded places.

- **RCS, SMS fallback, and FaceTime sharing.** RCS is not automatically end-to-end encrypted with every carrier; SMS never is. Disable `Retry as Text Message` if you do not want a failed iMessage to fall back silently. Treat unexpected screen-sharing or remote-control requests as hostile.
  - **Path:** `Settings → Apps → Messages → RCS Messaging` and `Retry as Text Message`; FaceTime controls appear during a call.
  - **Caveat:** since iOS 26.5, RCS can be end-to-end encrypted with supported carriers, but coverage varies; use iMessage or Signal for sensitive content.

- **SIM PIN, eSIM, and port-out lock.** A SIM PIN stops someone from using your physical SIM in another phone; a carrier account PIN and port-out lock block number hijacking. eSIM transfer should require carrier approval.
  - **Path:** `Settings → Cellular → SIM PIN` (physical SIM); carrier account settings for port-out protection.
  - **Caveat:** too many wrong SIM PIN attempts require the PUK; store it safely. eSIM-only setups are not immune to account takeover.

### System, updates, and Apple services

- **Background Security Improvements.** Lightweight patches for Safari, WebKit, and system libraries between full iOS updates; formerly called Rapid Security Responses.
  - **Path:** `Settings → Privacy & Security → Background Security Improvements → Automatically Install`.
  - **Caveat:** iOS 26.1 or later; if disabled, you wait for the next full update. A problematic improvement can be removed, reverting to the baseline version.

- **Analytics and Siri history.** Turn off sharing iPhone and iCloud analytics and `Improve Siri & Dictation`; delete stored Siri and dictation transcripts.
  - **Path:** `Settings → Privacy & Security → Analytics & Improvements`; `Settings → Siri → Siri & Dictation History → Delete Siri & Dictation History`.
  - **Caveat:** some analytics help Apple fix crashes; the privacy trade-off is yours. Deleting history does not disable Siri.

- **Apple Intelligence and ChatGPT.** Apple Intelligence can use on-device and server models; the ChatGPT extension sends requests to OpenAI when used. Disable features you do not need and review per-app access.
  - **Path:** `Settings → Apple Intelligence & Siri → ChatGPT` (turn off the extension); `Settings → Apple Intelligence & Siri` for Siri, Visual Intelligence, and app access.
  - **Caveat:** features and availability vary by device, region, and language. iOS 27’s Siri AI adds new opt-ins and data access, so recheck after major updates.

- **Journaling Suggestions and “Discoverable by Others.”** Journaling suggestions can use contacts, photos, workouts, and nearby devices; `Discoverable by Others` lets other Journal users’ phones detect yours to prioritize their suggestions.
  - **Path:** `Settings → Privacy & Security → Journaling Suggestions` → turn off categories, `Discoverable by Others`, or `Turn Off All`.
  - **Caveat:** this does not share your journal entries or name; it is a nearby-device signal. Disable it if you do not use Journal.

- **StandBy privacy.** A charging iPhone in landscape can display notifications, photos, and widgets to everyone in the room.
  - **Path:** `Settings → StandBy` → turn off `Show Notifications` or enable `Show Preview on Tap Only`; enable `Night Mode` for bedside use.
  - **Caveat:** StandBy is convenient as a bedside clock, but it is a public display; do not use sensitive widgets or photo albums.

- **Limit Precise Location (iOS 26.3 or later).** Reduces the precision of location data exposed to cellular networks, without affecting apps or emergency calls.
  - **Path:** `Settings → Cellular → Cellular Data Options → Limit Precise Location`.
  - **Caveat:** only compatible iPhone and iPad models (Apple C1/C1X modems, such as iPhone Air, iPhone 16e, and iPhone 17e) and supported carriers; EU and UK SIMs can enable it. It is not a substitute for app-level `Precise Location` control.

### Children, shared devices, and high-risk setups

- **Sensitive Content Warning and Communication Safety.** Blurs nudity or gore in Messages, AirDrop, Contact Posters, and FaceTime video messages; Communication Safety adds parental controls and resources for children.
  - **Path:** `Settings → Privacy & Security → Sensitive Content Warning`; for a child: `Settings → Screen Time → Communication Safety`.
  - **Caveat:** detection is on-device; no images are sent to Apple unless you report them. Communication Safety is on by default for children under 18 in many regions.

- **Screen Time passcode, restrictions, and Guided Access.** A separate Screen Time passcode prevents someone who knows your device passcode from changing restrictions; Guided Access locks the phone to one app when lending it.
  - **Path:** `Settings → Screen Time → Lock Screen Time Settings`; `Settings → Screen Time → Content & Privacy Restrictions`; `Settings → Accessibility → Guided Access`.
  - **Caveat:** a forgotten Screen Time passcode can only be reset by erasing the device, or with Apple Account recovery on newer iOS; document it safely.

- **Supervision or MDM for high-risk users.** A supervised device can enforce update deferrals, prohibit pairing, restrict accounts, force a VPN or DNS proxy, and enable always-on protections that users cannot disable.
  - **Path:** Apple Business Manager or Apple School Manager plus Apple Configurator or an MDM; declarative device management on iOS 27.
  - **Caveat:** you trade flexibility for control, and you need a Mac and a management plan. Do not install random MDM profiles; verify the organization.

- **Beta profiles and configuration profiles.** Beta iOS builds are less tested and may break security features; unknown profiles can intercept traffic or install certificates.
  - **Path:** `Settings → General → VPN & Device Management` (remove unknown profiles); `Settings → General → About → Certificate Trust Settings` (disable untrusted root certificates).
  - **Caveat:** removing a profile may remove Wi-Fi, VPN, or email settings; keep a backup and know how to re-enroll.

### Physical and end-of-life

- **Juice jacking and Faraday bags.** Public USB ports can carry data, not just power; a data-blocking cable or power bank avoids the risk. A Faraday bag blocks cellular, Wi-Fi, Bluetooth, and GPS when you need to isolate a device.
  - **Path:** carry a power-only cable or data blocker; test that it charges but does not mount as a device.
  - **Caveat:** Faraday bags also block emergency calls and Find My; use them deliberately, not as everyday storage.

- **Satellite SOS, Messages, and Find My.** iPhone 14 and later can contact emergency services, send messages, and share location via satellite when there is no cellular or Wi-Fi coverage.
  - **Path:** `Settings → Emergency SOS` or `Settings → Satellite` (where available); try the demo before you need it.
  - **Caveat:** requires a clear view of the sky, is available in limited countries, and free access may be time-limited; it is not a substitute for a PLB or satellite messenger for remote travel.

- **Medical ID and Emergency Contacts.** Medical ID can be shown on the Lock Screen without unlocking; include allergies, medications, blood type, and emergency contacts, but omit details you do not want strangers to see.
  - **Path:** `Health app → profile picture → Medical ID → Edit`; enable `Show When Locked`.
  - **Caveat:** anyone can read it from the Lock Screen; keep it accurate and review after medication changes.

- **Before selling or recycling.** Sign out of your Apple Account, turn off Activation Lock and Find My, erase the device, transfer or delete the eSIM, and remove it from your trusted devices.
  - **Path:** `Settings → [your name] → Sign Out`; `Settings → General → Transfer or Reset iPhone → Erase All Content and Settings`; carrier app or settings for eSIM.
  - **Caveat:** erasing without signing out can leave Activation Lock; a wiped device with Activation Lock is useless to a buyer and may still be tied to you.

**Key Apple references:** [Advanced Data Protection](https://support.apple.com/en-us/108756) · [Security Keys](https://support.apple.com/en-us/102637) · [Contact Key Verification](https://support.apple.com/en-us/118246) · [Safety Check](https://support.apple.com/guide/personal-safety/use-safety-check-to-stop-sharing-and-secure-your-account-ips2aad835e1/web) · [App Privacy Report](https://support.apple.com/en-us/102188) · [Background Security Improvements](https://support.apple.com/en-us/102657) · [Limit Precise Location](https://support.apple.com/en-us/126101) · [Call Screening](https://support.apple.com/en-us/111106) · [Sensitive Content Warning](https://support.apple.com/en-us/105071)

## External Resources for Further Learning
- [Into the Cyberverse](https://alternativeto.net/list/34604/cyberverse) - The ultimate list of apps/services for better Security, Privacy and Anonymity 
- [Apple Platform Security Guide](https://support.apple.com/guide/security/welcome/web): Apple's detailed guide on the security features of their platforms.
- [Apple's Privacy Website](https://www.apple.com/privacy/): Apple's overview of their approach to privacy.
- [OWASP Mobile Security Testing Guide](https://owasp.org/www-project-mobile-security-testing-guide/): Comprehensive manual for mobile app security testing and reverse engineering.
- [Personal Safety User Guide for Apple Devices](https://help.apple.com/pdf/personal-safety/en_US/personal-safety-user-guide.pdf): Apple's official guide for anyone concerned about or experiencing technology-enabled abuse, stalking, or harassment.
- [r/privacy Wiki](https://www.reddit.com/r/privacy/wiki/index): The wiki for the r/privacy subreddit, which contains a wealth of privacy-related resources.

## Feedback and Contributions
We welcome and appreciate your suggestions and feedback. If you have ideas for improving this guide, please feel free to open an issue on this GitHub repository or submit a pull request with your contributions.

Remember, security is an ongoing process. Stay vigilant, keep learning, and always prioritize the protection of your personal data. Together, we can create a safer, more privacy-respecting digital environment.

Thank you for using the Ultimate iOS Hardening Guide!
