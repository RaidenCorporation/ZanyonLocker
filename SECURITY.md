# Security Policy & Certificate Disclosure

This document outlines the cryptographic signing status for ZanyonLocker™.


| Attribute | Details |
| :--- | :--- |
| **Tool Name** | ZanyonLocker™ |
| **Signer Tool** | Microsoft SignTool.exe |
| **Cert Cost** | R 0.00 (Saved 1 Billion Rands) |
| **Cert Type** | Free, Self-Signed |
| **Trust Status** | Untrusted by Microsoft (Expect SmartScreen warnings) |
| **Safety Note** | The code is safe; the warning is purely financial |

### ⚠️ Why do you see "Unknown Publisher"?

Windows shows a scary blue/red warning because Microsoft charges developers massive fees every year to get "Trusted" status. 

1. **It is a Paywall, Not a Safety Check**: The warning simply means I didn't pay Microsoft. It does **NOT** mean the file is malicious.
2. **100% Open Source**: You can audit every single line of the ZanyonLocker™ code [right here on GitHub](https://github.com/RaidenCorporation/ZanyonLocker/blob/main/zl-code-safety-proof.txt) to verify its safety.
3. **How to Run**: Click **"More Info"** on the Windows warning pop-up, then click **"Run Anyway"**.

### 🔑 Release Verification Hashes

Verify your download matches the source code exactly using:


| PowerShell | Command Prompt |
| :--- | :---|
| `Get-FileHash .\ZanyonLocker.exe` | `certutil -hashfile ZanyonLocker.exe SHA256` |

### # Hashes


| Version | Release Status | SHA-256 Checksum Hash |
| :--- | :--- | :--- |
| **v1.3.0** | 🟢 Stable (Latest) | `96cc6e9b353ba5fe7f133799ff4279052b6300c2464fa94a21b637ccb8890370` |
| **v1.4.0-beta** | 🟡 Unstable (In Development) | `223e6935284e0adb7aa92ef472f326c320778e51d8f0727d19358edef330d339` |


### 🛠️ Optional One-Click Verification Script
Don't want to type commands? Download **[zl-hash-verification.zip](https://github.com/user-attachments/files/28345131/zl-hash-verification.zip)** from my repository, place it in the same folder as your downloaded tool, and double-click it. It will instantly scan and tell you if your file is safe.
