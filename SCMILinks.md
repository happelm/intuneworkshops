# SCMI Workshop - Link Collection

Curated resources for **SCMI – Migrating from Configuration Manager to Microsoft Intune**. The links follow the course modules: strategy, identities, tenant attach and co-management, cloud-first clients, workload authority, policy and app migration, updates, device actions and the clean sweep.

Lab instructions for the course: [happelm.github.io/SCMI](https://happelm.github.io/SCMI/)

---

## 🧭 Migration Strategy
- [Migration Guide to Microsoft Intune](https://learn.microsoft.com/en-us/intune/fundamentals/setup-migration)
- [Co-management for Windows Devices](https://learn.microsoft.com/en-us/intune/configmgr/comanage/overview)
- [FAQ for Co-management](https://learn.microsoft.com/en-us/intune/configmgr/comanage/faq)
- [Third-party MDM Coexistence](https://learn.microsoft.com/en-us/intune/configmgr/comanage/coexistence)

## 🪪 Identities: Hybrid Join, Cloud Sync, Entra Join
- [Configure Device Sync with Microsoft Entra Cloud Sync (Preview)](https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/device-sync)
- [What Is Microsoft Entra Cloud Sync?](https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/what-is-cloud-sync)
- [Cloud Sync Migration Decision Guide](https://learn.microsoft.com/en-us/entra/identity/hybrid/cloud-sync/connect-to-cloud-sync-decision-guide)
- [Configure Microsoft Entra Hybrid Join](https://learn.microsoft.com/en-us/entra/identity/devices/how-to-hybrid-join)
- [Verify Microsoft Entra Hybrid Join State](https://learn.microsoft.com/en-us/entra/identity/devices/how-to-hybrid-join-verify)
- [Troubleshoot Microsoft Entra Hybrid Joined Devices](https://learn.microsoft.com/en-us/entra/identity/devices/troubleshoot-hybrid-join-windows-current)
- [Microsoft Entra Hybrid Join Using Microsoft Entra Kerberos (Preview)](https://learn.microsoft.com/en-us/entra/identity/devices/how-to-hybrid-join-using-microsoft-entra-kerberos)
- [Entra Kerberos for Hybrid Join Devices (AdminDroid)](https://blog.admindroid.com/entra-kerberos-for-hybrid-join-devices/)

## 🔗 Tenant Attach
- [Tenant Attach Prerequisites](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/prerequisites)
- [Enable Tenant Attach](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/device-sync-actions)
- [Intune Policies for Tenant Attached Devices](https://learn.microsoft.com/en-us/intune/fundamentals/tenant-attach)
- [Device Timeline in the Admin Center](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/timeline)
- [ConfigMgr Applications in the Admin Center](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/applications)
- [Launch Tenant Attached CMPivot](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/cmpivot-start)
- [Endpoint Security Policies for Tenant Attached Devices](https://learn.microsoft.com/en-us/intune/configmgr/tenant-attach/endpoint-security-get-started)

## 🤝 Co-management
- [Enable Co-management](https://learn.microsoft.com/en-us/intune/configmgr/comanage/how-to-enable)
- [Tutorial: Enable Co-management for Existing Clients](https://learn.microsoft.com/en-us/intune/configmgr/comanage/tutorial-co-manage-clients)
- [Switch Co-management Workloads](https://learn.microsoft.com/en-us/intune/configmgr/comanage/how-to-switch-workloads)
- [Monitor Co-management](https://learn.microsoft.com/en-us/intune/configmgr/comanage/how-to-monitor)
- [Co-manage Internet-based Devices](https://learn.microsoft.com/en-us/intune/configmgr/comanage/how-to-prepare-win10)

## ☁️ Cloud-first Clients: ConfigMgr Client from Intune
- [Install the Client with Microsoft Entra ID](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/deploy/deploy-clients-cmg-azure)
- [Microsoft Entra Authentication Workflow](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/manage/azure-ccmsetup)
- [Client Installation Parameters and Properties](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/deploy/about-client-installation-properties)
- [Client Installation Methods](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/deploy/plan/client-installation-methods)
- [Configure Azure Services (Cloud Management)](https://learn.microsoft.com/en-us/intune/configmgr/core/servers/deploy/configure/azure-services-wizard)
- [Enhanced HTTP](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/hierarchy/enhanced-http)
- [Certificates Overview](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/security/certificates-overview)

## 🔑 Workload Authority
- [How to Enroll with Windows Autopilot (Co-management Settings)](https://learn.microsoft.com/en-us/intune/configmgr/comanage/autopilot-enrollment)
- [Troubleshooting Co-management Workloads](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/comanage-configmgr/troubleshoot-co-management-workloads)
- [Co-management Capabilities 2147479807 on Windows 11 (Microsoft Q&A)](https://learn.microsoft.com/en-us/answers/questions/763544/windows-11-co-management-capabilities-2147479807)
- [Co-management Workloads and Capabilities (MSEndpointMgr)](https://msendpointmgr.com/2023/02/04/co-management-workloads-capabilities/)

## 📜 Policy Migration & Conflicts
- [Import and Analyze Group Policies](https://learn.microsoft.com/en-us/intune/device-configuration/import-group-policy-analytics)
- [Migrate Imported Group Policy to Intune](https://learn.microsoft.com/en-us/intune/intune-service/configuration/group-policy-analytics-migrate)
- [Settings Catalog](https://learn.microsoft.com/en-us/intune/device-configuration/settings-catalog/)
- [ControlPolicyConflict Policy CSP (MDMWinsOverGP)](https://learn.microsoft.com/en-us/windows/client-management/mdm/policy-csp-controlpolicyconflict)
- [Remediations](https://learn.microsoft.com/en-us/intune/device-management/tools/deploy-remediations)
- [Device Action: Run Remediation](https://learn.microsoft.com/en-us/intune/device-management/actions/run-remediation)

## 🎯 Targeting: Collections to Groups & Filters
- [Assignment Filters](https://learn.microsoft.com/en-us/intune/fundamentals/filters/overview)
- [Assignment Filter Properties and Operators](https://learn.microsoft.com/en-us/intune/fundamentals/filters/ref-device-properties)
- [Dynamic Membership Rules for Groups](https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership)
- [Fix Problems with Dynamic Membership Groups](https://learn.microsoft.com/en-us/entra/identity/users/groups-troubleshooting)

## 📦 App Migration & Win32 Apps
- [Win32 App Management](https://learn.microsoft.com/en-us/intune/app-management/deployment/win32)
- [Prepare a Win32 App for Upload](https://learn.microsoft.com/en-us/intune/app-management/deployment/create-win32-package)
- [Add and Assign Win32 Apps](https://learn.microsoft.com/en-us/intune/app-management/deployment/add-win32)
- [Win32 App Flow: Deployment, Delivery and Processing](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/app-management/develop-deliver-working-win32-app-via-intune)
- [Understand the Intune Management Extension](https://learn.microsoft.com/en-us/intune/intune-service/apps/intune-management-extension)
- [Add the Windows Company Portal App](https://learn.microsoft.com/en-us/intune/app-management/deployment/add-company-portal-windows)
- [Win32App Migration Tool (MSEndpointMgr)](https://msendpointmgr.com/2021/03/27/automatically-migrate-applications-from-configmgr-to-intune-with-the-win32app-migration-tool/)
- [Win32App Migration Tool (PowerShell Gallery)](https://www.powershellgallery.com/packages/Win32AppMigrationTool/)

## 🏭 App Factory: PSAppDeployToolkit
- [PSAppDeployToolkit: Creating a New Deployment](https://psappdeploytoolkit.com/docs/getting-started/creating-a-new-deployment)
- [PSAppDeployToolkit: New-ADTTemplate](https://psappdeploytoolkit.com/docs/reference/functions/New-ADTTemplate)
- [PSAppDeployToolkit Release Notes](https://psappdeploytoolkit.com/docs/getting-started/release-notes)
- [PSAppDeployToolkit Releases (GitHub)](https://github.com/psappdeploytoolkit/psappdeploytoolkit/releases)
- [PSADT v3 to v4 Cheat Sheet (Community)](https://discourse.psappdeploytoolkit.com/t/psadt-v3-to-v4-cheatsheat/5930)

## 🔄 Updates & Content Delivery
- [WSUS Deprecation (Windows IT Pro Blog)](https://techcommunity.microsoft.com/blog/windows-itpro-blog/windows-server-update-services-wsus-deprecation/4250436)
- [Deprecation of WSUS Driver Synchronization](https://techcommunity.microsoft.com/blog/windows-itpro-blog/deprecation-of-wsus-driver-synchronization/4177831)
- [Windows Update Management Overview](https://learn.microsoft.com/en-us/intune/device-updates/windows/)
- [Manage Update Ring Policies](https://learn.microsoft.com/en-us/intune/device-updates/windows/manage-update-rings)
- [Update Ring Policy Settings](https://learn.microsoft.com/en-us/intune/device-updates/windows/ref-update-ring-settings)
- [Configure Feature Update Policies](https://learn.microsoft.com/en-us/intune/device-updates/windows/configure-feature-update-policy)
- [Configure Driver Update Policies](https://learn.microsoft.com/en-us/intune/device-updates/windows/configure-driver-update-policy)
- [Troubleshoot Update Ring Policies](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/device-protection/troubleshoot-update-rings)
- [What Is Windows Autopatch?](https://learn.microsoft.com/en-us/windows/deployment/windows-autopatch/overview/windows-autopatch-overview)
- [Delivery Optimization Settings for Intune](https://learn.microsoft.com/en-us/intune/device-configuration/templates/ref-delivery-optimization-settings-windows)
- [Delivery Optimization Reference](https://learn.microsoft.com/en-us/windows/deployment/do/waas-delivery-optimization-reference)
- [Configure Delivery Optimization](https://learn.microsoft.com/en-us/windows/deployment/do/delivery-optimization-configure)
- [Microsoft Connected Cache Overview](https://learn.microsoft.com/en-us/windows/deployment/do/waas-microsoft-connected-cache)
- [Microsoft Connected Cache for Enterprise and Education](https://learn.microsoft.com/en-us/windows/deployment/do/mcc-ent-edu-overview)

## 🛠️ Device Actions & Provisioning
- [Device Actions Overview](https://learn.microsoft.com/en-us/intune/device-management/actions/)
- [Device Action: Collect Diagnostics](https://learn.microsoft.com/en-us/intune/device-management/actions/collect-diagnostics)
- [Tutorial: Set Up Cloud-native Windows Endpoints](https://learn.microsoft.com/en-us/intune/solutions/cloud-native-endpoints/tutorial-cloud-native-setup)

## 🧹 Clean Sweep
- [Manage Clients: Uninstall the ConfigMgr Client](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/manage/manage-clients)
- [Manage Stale Devices in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/devices/manage-stale-devices)
- [Configuration Manager Hotfixes and Update Rollups](https://learn.microsoft.com/en-us/intune/configmgr/hotfix/)

## 📄 Logs & Troubleshooting
- [Configuration Manager Log File Reference](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/hierarchy/log-files)
- [About Configuration Manager Log Files](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/hierarchy/about-log-files)
- [Client Notification](https://learn.microsoft.com/en-us/intune/configmgr/core/clients/manage/client-notification)
- [Troubleshoot Co-management Bootstrap with Modern Provisioning](https://learn.microsoft.com/en-us/troubleshoot/mem/intune/comanage-configmgr/troubleshoot-co-management-bootstrap)
- [Support Center UI Reference](https://learn.microsoft.com/en-us/intune/configmgr/core/support/support-center-ui-reference)

---
