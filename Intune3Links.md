# 🧰 Intune Troubleshooting Workshop Link Collection

Welcome to the curated list of resources for troubleshooting Microsoft Intune environments. This is the third part of the Intune workshop series and focuses on diagnostics, root cause analysis, policy and deployment troubleshooting, and community tools.

---

## 🔎 Overview: Troubleshooting & Root Cause Analysis
- [Intune Troubleshooting Overview](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/welcome-intune)
- [Send Logs (Control Panel - Windows)](https://learn.microsoft.com/en-us/mem/intune/user-help/send-logs-to-your-it-admin-cp-windows)
- [Send Logs (Settings - Windows)](https://learn.microsoft.com/en-us/mem/intune/user-help/send-logs-to-your-it-admin-settings-windows)
- [Send Errors (iOS)](https://learn.microsoft.com/en-us/mem/intune/user-help/send-errors-to-your-it-admin-ios)
- [Send Logs (Email - Android)](https://learn.microsoft.com/en-us/mem/intune/user-help/send-logs-to-your-it-admin-by-email-android)
- [Verbose Logging (Android)](https://learn.microsoft.com/en-us/mem/intune/user-help/use-verbose-logging-to-help-your-it-administrator-fix-device-issues-android)

## 📄 How to Read Intune Logfiles
- [Intune Management Extension Logs Overview](https://petervanderwoude.nl/post/getting-familiar-with-the-intune-management-extension-log-files/)
- [IME Summary – Jannik Reinhard](https://jannikreinhard.com/2022/07/31/summary-of-the-intune-management-extension/)
- [Deep Dive: IME Logs](https://www.anoopcnair.com/intune-management-extension-deep-dive-level-300/)

## 🧾 Troubleshooting Device Registration & Enrollment
- [Diagnosing Enrollment Issues](https://learn.microsoft.com/en-us/windows/client-management/mdm-diagnose-enrollment)

## ⚖️ Troubleshooting Policy Conflicts & Compliance
- [Device vs User Scope](https://learn.microsoft.com/en-us/mem/intune/configuration/settings-catalog?tabs=sc-search-filter%2Csc-reporting#device-scope-vs-user-scope-settings)
- [Policy Assignment Timelines](https://learn.microsoft.com/en-us/mem/intune/configuration/device-profile-troubleshoot#how-long-does-it-take-for-devices-to-get-a-policy-profile-or-app-after-they-are-assigned)
- [Config Refresh Feature](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/intro-to-config-refresh-a-refreshingly-new-mdm-feature/ba-p/4176921)
- [Remove Apps & Configurations](https://learn.microsoft.com/en-us/mem/intune/remote-actions/remove-apps-config?tabs=iOS%2Cavailable-actions)
- [Temporarily Remove Mobile Apps](https://petervanderwoude.nl/post/temporarily-removing-apps-and-configurations-from-mobile-devices/)

## 📦 Troubleshooting Application Deployment
- [Win32 App Installation Phases](https://call4cloud.nl/2021/05/win32app-ime-installation-phases-intune/)
- [IME Summary](https://jannikreinhard.com/2022/07/31/summary-of-the-intune-management-extension)
- [Change Log Level for IME](https://jannikreinhard.com/2022/06/06/dive-deeper-into-the-ime-log-with-a-simple-change-of-the-log-level)
- [Force Reinstall of Win32 Apps](https://www.deploymentresearch.com/force-application-reinstall-in-microsoft-intune-win32-apps)
- [Win32 App State Messages](https://msendpointmgr.com/2023/08/28/win32-app-state-messages-demystified/)
- [Win32 App Troubleshooting](https://www.anoopcnair.com/intune-win32-app-troubleshooting/)
- [Develop & Deliver Working Win32 App](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/app-management/develop-deliver-working-win32-app-via-intune)
- [Retry Interval for Win32 App](https://patchtuesday.com/blog/tech-blog/win32app-retry-interval/)
- [Trigger IME Retry](https://www.anoopcnair.com/override-grs-trigger-ime-to-retry-failed-win32)

## 💻 Troubleshooting Script Deployment
- [Troubleshooting PowerShell Scripts in Intune](https://www.velessoftware.com/troubleshooting-intune-powershell-scripts/)

## 🔐 Security Templates & Endpoint Security
- [Security Baselines Overview](https://learn.microsoft.com/en-us/mem/intune/protect/security-baselines)
- [All Security Settings – MDM](https://learn.microsoft.com/en-us/mem/intune/protect/security-baseline-settings-mdm-all?pivots=mdm-23h2)
- [Security Baseline 23H2 Overview](https://emsroute.com/2024/04/03/security-baseline-23h2/)
- [Security Baselines (Rami T.)](https://ramitamminen.com/?p=17)
- [Trace Endpoint Security](https://techcommunity.microsoft.com/t5/intune-customer-success/how-to-trace-and-troubleshoot-the-intune-endpoint-security/ba-p/3261452)

## 🧮 Legacy Management Conflicts
- [MDM vs GPO – What Wins?](https://www.anoopcnair.com/mdm-wins-over-gpo-group-policy-intune-policy/)
- [WinRM on AAD Devices](https://manage-the.cloud/2023/06/02/windows-remote-management-winrm-on-azure-ad-joined-devices/)
- [Connect to AADJ PCs Remotely](https://learn.microsoft.com/en-us/windows/client-management/client-tools/connect-to-remote-aadj-pc)
- [Enable Remote Access for AAD Users](https://petervanderwoude.nl/post/enabling-remote-access-for-specific-users-on-azure-ad-joined-devices/)
- [Web Sign-In via Intune](https://learn.microsoft.com/en-us/windows/security/identity-protection/web-sign-in/?tabs=intune)
- [WUfB Reporting Overview](https://learn.microsoft.com/en-us/windows/deployment/update/wufb-reports-overview)
- [WUfB Config Guide](https://www.systemcenterdudes.com/configure-windows-update-for-business-reporting/)
- [WUfB Custom Reporting](https://docs.smsagent.blog/microsoft-endpoint-manager-reporting/windows-update-for-business-custom-reporting)
- [Update Primary User via PowerShell](https://www.tbone.se/2023/02/16/update-intune-primary-user-with-powershell-or-azure-automation/)
- [Windows Upgrade Log Files](https://learn.microsoft.com/en-us/windows/deployment/upgrade/log-files)

## 🧷 SSO to On-Prem & Azure Files
- [FIDO2 for On-Premises](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-authentication-passwordless-security-key-on-premises)
- [Hybrid Identity Auth for Azure Files](https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-hybrid-identities-enable?tabs=azure-portal%2Cintune)
- [Hybrid Cloud Kerberos Trust](https://learn.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/deploy/hybrid-cloud-kerberos-trust?tabs=Intune)

## 🧰 Community Tools for Troubleshooting
- [Intune Debug Toolkit](https://msendpointmgr.com/intune-debug-toolkit/)
- [Troubleshooting Scripts GitHub](https://github.com/petripaavola/Intune/tree/master/Troubleshooting)
- [Get-IntuneManagementExtensionDiagnostics](https://github.com/petripaavola/Get-IntuneManagementExtensionDiagnostics)
- [SyncML Viewer via WinGet](https://oliverkieselbach.com/2024/03/04/syncml-viewer-via-winget/)
- [Get-AutopilotDiagnostics (Community)](https://oofhours.com/2024/02/05/new-enhancements-to-get-autopilotdiagnosticscommunity/)
- [Get Assigned Intune Policies & Apps](https://timmyit.com/2023/10/09/get-all-assigned-intune-policies-and-apps-from-a-microsoft-entra-group/)

---
