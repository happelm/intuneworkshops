# Intune 1 - Link Collection

Welcome to the curated list of core resources for Microsoft Intune. This is the first part of the Intune workshop series and provides foundational links across modern desktop deployment, identity, licensing, platform enrollment, app deployment, and device configuration.

---

## 📘 Course Materials & Certification
- [Modern Desktop Certification Overview](https://learn.microsoft.com/en-us/credentials/certifications/modern-desktop/?practice-assessment-type=certification)
- [MD-102 Training Course](https://learn.microsoft.com/en-us/training/courses/md-102t00)
- [Study Guide for MD-102](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/md-102)

## 📰 What's New & Release Information
- [What's New in Microsoft Intune](https://learn.microsoft.com/en-us/intune/whats-new/)
- [Windows 11 Release Information](https://learn.microsoft.com/en-us/windows/release-health/windows11-release-information)

## 🎤 Events
- [Tech Accelerator: Microsoft Intune Suite](https://techcommunity.microsoft.com/event/techcommunitylive/tech-accelerator-microsoft-intune-suite/3756368)
- [Microsoft Technical Takeoff](https://techcommunity.microsoft.com/event/techcommunitylive/microsoft-technical-takeoff/3968237)

## 🧾 Licensing
- [Compare EMS Plans](https://www.microsoft.com/en-us/microsoft-365/enterprise-mobility-security/compare-plans-and-pricing)
- [Microsoft 365 Enterprise Plans and Pricing](https://www.microsoft.com/en-us/microsoft-365/enterprise/microsoft-365-plans-and-pricing)
- [M365 Maps - Microsoft Licensing Diagrams](https://m365maps.com)

## 🔄 Microsoft Entra Connect
- [Topologies for Entra Connect](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/plan-connect-topologies)
- [Entra Connect Version History](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/reference-connect-version-history)
- [Seamless Single Sign-On](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-connect-sso)
- [Choose the Right Authentication Method](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/choose-ad-authn)
- [Sync Scheduler](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-connect-sync-feature-scheduler)

## 🖥️ Device Identity & Hybrid Join
- [Configure Microsoft Entra Hybrid Join](https://learn.microsoft.com/en-us/entra/identity/devices/how-to-hybrid-join)
- [Auto MDM Enrollment for Existing Entra-Joined Devices](https://call4cloud.nl/enroll-existing-entra-azure-intune/)
- [Primary Refresh Token (PRT)](https://learn.microsoft.com/en-us/entra/identity/devices/concept-primary-refresh-token)
- [Troubleshoot Devices with dsregcmd](https://learn.microsoft.com/en-us/entra/identity/devices/troubleshoot-device-dsregcmd)

## 🔑 Passwords & Passwordless
- [Self-Service Password Reset on Windows](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-sspr-windows)
- [Deploy Entra Password Protection On-Premises](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-password-ban-bad-on-premises-deploy)
- [FIDO2 Security Keys for On-Premises Resources](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-authentication-passwordless-security-key-on-premises)
- [Passkeys (FIDO2) in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-passkeys-fido2)

## 🚀 Windows Autopilot
- [Cloud-Native Windows Endpoints - Setup Tutorial](https://learn.microsoft.com/en-us/intune/solutions/cloud-native-endpoints/tutorial-cloud-native-setup)
- [Autopilot Scenarios Tutorial](https://learn.microsoft.com/en-us/autopilot/tutorial/autopilot-scenarios)
- [Windows Autopilot Hybrid Join](https://learn.microsoft.com/en-us/autopilot/windows-autopilot-hybrid)
- [Autopilot Troubleshooting FAQ](https://learn.microsoft.com/en-us/autopilot/troubleshooting-faq)
- [Autopilot Branding & Update OS Scripts](https://oofhours.com/2020/05/18/two-for-one-updated-autopilot-branding-and-update-os-scripts/)
- [Autopilot Manager](https://oliverkieselbach.com/2020/12/08/autopilot-manager/)

## ⚙️ Configuration Profiles & CSPs
- [Configuration Service Provider (CSP) Reference](https://learn.microsoft.com/en-us/windows/client-management/mdm/)
- [Understanding ADMX-Backed Policies](https://learn.microsoft.com/en-us/windows/client-management/understanding-admx-backed-policies)
- [Policy CSP - RestrictedGroups](https://learn.microsoft.com/en-us/windows/client-management/mdm/policy-csp-restrictedgroups)
- [Custom Device Settings (OMA-URI)](https://learn.microsoft.com/en-us/intune/device-configuration/templates/configure-custom-settings)
- [Settings Catalog: Device vs. User Scope](https://learn.microsoft.com/en-us/intune/device-configuration/settings-catalog/#device-scope-vs-user-scope-settings)
- [Intune Hydration Kit - Default Policies](https://www.intunehydrationkit.com/)

## 🛡️ BitLocker & Security Hardening
- [Encrypt Windows Devices with BitLocker](https://learn.microsoft.com/en-us/intune/device-configuration/endpoint-security/encrypt-bitlocker-windows)
- [BitLocker Configuration via Endpoint Security](https://techcommunity.microsoft.com/blog/intunecustomersuccess/configuring-bitlocker-encryption-with-endpoint-security/2283101)
- [MBAM Server Migration](https://techcommunity.microsoft.com/blog/coreinfrastructureandsecurityblog/mbam-server-migration-to-microsoft-endpoint-manager/2192984)
- [Windows CIS Benchmarks - Patching the Gaps](https://www.oddsandendpoints.co.uk/posts/windows-cis-patching-gaps-part1/)

## 📦 App Deployment (Win32 & PSADT)
- [Win32 App Management](https://learn.microsoft.com/en-us/intune/app-management/deployment/win32)
- [Win32 Content Prep Tool](https://github.com/Microsoft/Microsoft-Win32-Content-Prep-Tool)
- [Intune Management Extension Overview](https://learn.microsoft.com/en-us/intune/device-management/tools/management-extension-windows)
- **IME log folder:** `C:\ProgramData\Microsoft\IntuneManagementExtension\Logs`
- [Best Practices with PSADT](https://deploymentshare.com/articles/bp-psadt/)
- [PSADT + Intune Guide](https://deploymentshare.com/articles/bp-psadtintune/)
- [User-Interactive App Deployment with PSADT](https://svdbusse.github.io/SemiAnnualChat/2019/09/14/User-Interactive-Win32-Intune-App-Deployment-with-PSAppDeployToolkit.html)
- [Installing Visio via PSADT](https://365bythijs.be/2019/09/19/installing-visio-onto-an-existing-office-installation-with-psadt-and-intune/)
- [Win32App Migration Tool (ConfigMgr to Intune)](https://byteben.com/bb/automatically-migrate-applications-from-configmgr-to-intune-with-the-win32app-migration-tool/)

## 📥 Windows Package Manager (WinGet)
- [WinGet on GitHub](https://github.com/microsoft/winget-cli)
- [WinGet Deployment via Intune](https://scloud.work/en/how-to-winget-intune/?amp=1)
- [WinGet Wrapper (GitHub)](https://github.com/SorenLundt/WinGet-Wrapper)

## 🗂️ Network Drives & Printers
- [Intune Drive Mapping Generator](https://intunedrivemapping.azurewebsites.net/)

## 🤖 Android Enterprise
- [Android Enterprise Terminology](https://developers.google.com/android/work/terminology)
- [Android Enterprise Recommended Devices](https://androidenterprisepartners.withgoogle.com/devices/#!/?aer)
- [Package Name Viewer App](https://play.google.com/store/apps/details?id=com.csdroid.pkg&hl=de_AT)
- [Fully Managed Device Enrollment](https://learn.microsoft.com/en-us/intune/device-enrollment/android/setup-fully-managed)
- [Dedicated Device Enrollment](https://learn.microsoft.com/en-us/intune/device-enrollment/android/setup-dedicated)
- [Samsung Knox Mobile Enrollment](https://learn.microsoft.com/en-us/intune/device-enrollment/android/setup-samsung-knox-mobile)
- [QR Code Generator](https://bayton.org/qr-generator/)
- [Defender for Endpoint Onboarding with Samsung Knox Service Plugin](https://www.oddsandendpoints.co.uk/posts/android-enterprise-defender-onboarding/)

## 🍎 Apple iOS/iPadOS
- [Renew the Apple Push Notification Certificate](https://haydog.tech.blog/2022/09/08/how-to-renew-apple-push-notification-certificate-in-microsoft-intune/)
- [Automated Device Enrollment (ADE) for iOS/iPadOS](https://learn.microsoft.com/en-us/intune/device-enrollment/apple/setup-automated-ios)
- [Personal Device Enrollment Options for iOS/iPadOS](https://learn.microsoft.com/en-us/intune/device-enrollment/apple/personal-device-options-ios)
- [User Enrollment Methods for iOS/iPadOS](https://learn.microsoft.com/en-us/intune/device-enrollment/apple/user-enrollment-methods-ios)
- [iMazing Profile Editor - "Apple Configurator" for Windows](https://imazing.com/profile-editor)

## 📱 Mobile Application Management (MAM)
- [Microsoft Edge Mobile - Policies](https://learn.microsoft.com/en-us/deployedge/microsoft-edge-mobile-policies)
- [Manage Microsoft Edge on iOS and Android with Intune](https://learn.microsoft.com/en-us/intune/app-management/configuration/configure-edge-ios-android)
- [Configure Outlook for iOS and Android with Intune](https://learn.microsoft.com/en-us/intune/app-management/configuration/configure-outlook)

## 🎓 Windows for Education
- [Windows for Education Documentation](https://learn.microsoft.com/en-us/education/windows/)
- [eEducation Community Austria](https://community.eeducation.at/)

## 🙋 End-User Help
- [Intune Help for End Users](https://learn.microsoft.com/en-us/intune/user-help/enrollment/)

---
