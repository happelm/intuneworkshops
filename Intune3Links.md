# Intune Troubleshooting Workshop - Link Collection

Welcome to the curated list of resources for troubleshooting Microsoft Intune environments. This is the third part of the Intune workshop series and focuses on diagnostics, root cause analysis, policy and deployment troubleshooting, and community tools.

---

## 🔎 Troubleshooting Overview
- [Intune Troubleshooting Documentation](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/welcome-intune)

## 📤 Collecting Logs from Devices
- [Collect Logs via Company Portal (Windows)](https://learn.microsoft.com/en-us/intune/user-help/diagnostics/collect-logs-company-portal-windows)
- [Collect Logs via Settings (Windows)](https://learn.microsoft.com/en-us/intune/user-help/diagnostics/collect-logs-settings-windows)
- [Collect Logs (iOS/iPadOS)](https://learn.microsoft.com/en-us/intune/user-help/diagnostics/collect-logs-ios)
- [Collect Logs (Android)](https://learn.microsoft.com/en-us/intune/user-help/diagnostics/collect-logs-android)
- [Enable Verbose Logging (Android)](https://learn.microsoft.com/en-us/intune/user-help/diagnostics/enable-verbose-logging-android)

## 📄 Reading Intune Log Files
- [Intune Management Extension Log Files](https://petervanderwoude.nl/post/getting-familiar-with-the-intune-management-extension-log-files/)
- [Summary of the Intune Management Extension](https://jannikreinhard.com/summary-of-the-intune-management-extension/)
- [IME Deep Dive (Level 300)](https://www.anoopcnair.com/intune-management-extension-deep-dive-level-300/)
- [Change the IME Log Level](https://jannikreinhard.com/dive-deeper-into-the-ime-log-with-a-simple-change-of-the-log-level/)

## 🧾 Device Registration & Enrollment
- [Diagnosing MDM Enrollment Failures](https://learn.microsoft.com/en-us/windows/client-management/mdm-diagnose-enrollment)

## ⚖️ Policy Conflicts & Compliance
- [Settings Catalog: Device vs. User Scope](https://learn.microsoft.com/en-us/intune/device-configuration/settings-catalog/#device-scope-vs-user-scope-settings)
- [Policy Refresh Intervals](https://learn.microsoft.com/en-us/intune/device-configuration/troubleshoot-device-profiles#policy-refresh-intervals)
- [Config Refresh](https://techcommunity.microsoft.com/blog/windows-itpro-blog/intro-to-config-refresh-%e2%80%93-a-refreshingly-new-mdm-feature/4176921)
- [MDM vs. GPO - What Wins?](https://www.anoopcnair.com/mdm-wins-over-gpo-group-policy-intune-policy/)
- [Remove Apps & Configurations](https://learn.microsoft.com/en-us/intune/device-management/actions/remove-apps-config?tabs=iOS%2Cavailable-actions)
- [Temporarily Remove Apps & Configurations from Mobile Devices](https://petervanderwoude.nl/post/temporarily-removing-apps-and-configurations-from-mobile-devices/)

## 📦 App Deployment
- [Develop & Deliver a Working Win32 App](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/app-management/develop-deliver-working-win32-app-via-intune)
- [Win32 App Installation Phases](https://call4cloud.nl/win32app-ime-installation-phases-intune-troubleshoot/)
- [Win32 App State Messages Demystified](https://msendpointmgr.com/2023/08/28/win32-app-state-messages-demystified/)
- [Win32 App Troubleshooting](https://www.anoopcnair.com/intune-win32-app-troubleshooting/)
- [Win32 App Retry Interval](https://patchtuesday.com/blog/tech-blog/win32app-retry-interval/)
- [Trigger IME Retry for Failed Win32 Apps](https://www.anoopcnair.com/override-grs-trigger-ime-to-retry-failed-win32/)
- [Force Reinstall of Win32 Apps](https://www.deploymentresearch.com/force-application-reinstall-in-microsoft-intune-win32-apps/)

## 💻 Script Deployment
- [Troubleshooting PowerShell Scripts in Intune](https://www.velessoftware.com/blog/troubleshooting-intune-powershell-scripts)
- [Code Signing for PowerShell Scripts](https://www.gradenegger.eu/en/code-signature-for-powershell-script-files/)

## 🛡️ Security Baselines & Endpoint Security
- [Security Baselines Overview](https://learn.microsoft.com/en-us/intune/device-security/security-baselines/overview)
- [Windows MDM Security Baseline Settings](https://learn.microsoft.com/en-us/intune/device-security/security-baselines/ref-windows-mdm-settings?pivots=mdm-24h2)
- [Security Baseline Upgrade](https://emsroute.com/2024/04/03/security-baseline-23h2/)
- [Security Baselines (Rami Tamminen)](https://ramitamminen.com/?p=17)
- [Trace and Troubleshoot Endpoint Security Firewall Rules](https://techcommunity.microsoft.com/blog/intunecustomersuccess/how-to-trace-and-troubleshoot-the-intune-endpoint-security-firewall-rule-creatio/3261452)

## 🔄 Windows Update & Upgrade
- [Windows Update for Business Reports Overview](https://learn.microsoft.com/en-us/windows/deployment/update/wufb-reports-overview)
- [Configure WUfB Reports](https://www.systemcenterdudes.com/configure-windows-update-for-business-reporting/)
- [WUfB Custom Reporting](https://docs.smsagent.blog/microsoft-endpoint-manager-reporting/windows-update-for-business-custom-reporting)
- [Windows Upgrade Log Files](https://learn.microsoft.com/en-us/windows/deployment/upgrade/log-files)

## 🖥️ Remote Access to Entra-Joined Devices
- [WinRM on Entra-Joined Devices](https://manage-the.cloud/2023/06/02/windows-remote-management-winrm-on-azure-ad-joined-devices/)
- [Connect to Entra-Joined PCs Remotely](https://learn.microsoft.com/en-us/windows/client-management/client-tools/connect-to-remote-aadj-pc)
- [Enable Remote Access for Specific Users](https://petervanderwoude.nl/post/enabling-remote-access-for-specific-users-on-azure-ad-joined-devices/)

## 🔐 Authentication, SSO & Azure Files
- [FIDO2 Security Keys for On-Premises Resources](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-authentication-passwordless-security-key-on-premises)
- [Hybrid Identities for Azure Files](https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-auth-hybrid-identities-enable?tabs=azure-portal%2Cintune)
- [Windows Hello for Business - Cloud Kerberos Trust](https://learn.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/deploy/hybrid-cloud-kerberos-trust?tabs=Intune)
- [Web Sign-In](https://learn.microsoft.com/en-us/windows/security/identity-protection/web-sign-in/?tabs=intune)

## 🧰 Community Tools & Scripts
- [Intune Debug Toolkit](https://msendpointmgr.com/intune-debug-toolkit/)
- [Troubleshooting Scripts by Petri Paavola (GitHub)](https://github.com/petripaavola/Intune/tree/master/Troubleshooting)
- [Get-IntuneManagementExtensionDiagnostics (GitHub)](https://github.com/petripaavola/Get-IntuneManagementExtensionDiagnostics)
- [SyncML Viewer via WinGet](https://oliverkieselbach.com/2024/03/04/syncml-viewer-via-winget/)
- [Get-AutopilotDiagnosticsCommunity](https://oofhours.com/2024/02/05/new-enhancements-to-get-autopilotdiagnosticscommunity/)
- [Get All Assigned Intune Policies & Apps for an Entra Group](https://timmyit.com/2023/10/09/get-all-assigned-intune-policies-and-apps-from-a-microsoft-entra-group/)
- [Update the Intune Primary User with PowerShell](https://www.tbone.se/2023/02/16/update-intune-primary-user-with-powershell-or-azure-automation/)

---
