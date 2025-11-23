# Microsoft Defender for Endpoint Lab - Preparation Notes

## 🎯 Purpose
Set up a test environment to evaluate MDE detection, onboarding, and alert investigation.

## 🧩 Planned Tests
- Onboarding Windows client
- Test malware detection (EICAR)
- Log collection and alert analysis
- Coverage comparison by OS

## 🧱 Requirements
- Windows 11 Pro
- Microsoft 365 E5 (Developer Program sandbox planned)
- Entra ID integration

## 🖥️ Portals
- https://security.microsoft.com
- https://entra.microsoft.com

## 🛠️ Useful Commands

```powershell
Get-MpComputerStatus | Select AntivirusEnabled, RealTimeProtectionEnabled

