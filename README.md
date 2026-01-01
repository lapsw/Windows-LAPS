## Windows LAPS v3.0

Download latest version from Releases:       
https://github.com/admpack/Windows-LAPS/releases/tag/3.0

## System requirements

* Requires .NET Framework version 4.6 or higher
* Minimum supported operating systems: Windows Vista or Windows Server 2008

## Introduction

Windows LAPS (Local Administrator Password Solution) is a Microsoft security capability that helps organizations protect endpoints by automatically managing local administrator account passwords. It generates a unique, complex password for each Windows device, stores it securely (typically in Active Directory or Azure AD, depending on your deployment), and rotates it on a defined schedule. This reduces the risk of lateral movement and credential reuse, two common attack paths when identical local admin passwords exist across many machines.

With Windows LAPS, authorized IT staff can retrieve a device’s current local admin password when needed for support or recovery, while access is controlled through directory permissions and can be audited. Policies can enforce password length, complexity, expiration, and backup settings, allowing consistent governance across fleets of desktops, laptops, and servers. Modern implementations also support improved logging and clearer operational workflows, making it easier to meet internal security standards and compliance requirements.

Windows LAPS is designed for enterprise environments that need practical privileged access controls without adding third-party agents or complex vaulting systems. It integrates with standard Windows management approaches such as Group Policy, Intune, and configuration baselines, enabling scalable rollout and centralized administration. By eliminating shared local admin credentials and ensuring routine password rotation, Windows LAPS strengthens endpoint hardening, limits blast radius during incidents, and supports a more resilient security posture.
