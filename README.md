VANTAGE — Beta v1.0.0

Vantage is a high-performance desktop security application designed to protect your digital assets using military-grade **AES-256 encryption**. Developed by **SyncPointFlow**, this Beta release delivers a complete encrypted image vault with cloud sync, OCR-powered search, and a privacy-first architecture.

> **Windows only.** macOS and Linux support is planned for a future release.

---

## 🛡️ Security & Trust

We prioritize transparency at every level:

- **End-to-end encryption:** All image content is encrypted using AES-256 before it ever leaves your machine.
- **Zero plaintext storage:** Your OCR-extracted text is encrypted with a key derived from your password — we cannot read it.
- **Recovery codes:** A one-time recovery code is generated at signup. Store it securely — it's the only way to recover your account if you forget your password while not logged in anymore.
- **Session security:** Tokens are stored in the Windows Credential Manager via the system keyring, never in plaintext files.
- **Microsoft Verified:** Our installer has been manually reviewed and cleared by Microsoft Security Intelligence.

---

## 🚀 Key Features (Beta)

- **Encrypted Image Vault:** Upload images and screenshots — content is OCR-scanned, encrypted, and synced to your private cloud vault.
- **AES-256 Encryption:** Industry-standard encryption with a password-derived key unique to your account.
- **OCR-Powered Search:** Search the text content of your images without ever decrypting server-side.
- **Ghost Mode:** Blurs all images and hides deposit names in the UI for over-the-shoulder privacy.
- **Email OTP Verification:** Account creation requires email confirmation via a 6-digit code.
- **Password Reset via Email:** Secure reset links sent through Resend — no plaintext passwords stored anywhere.
- **50MB Free Storage:** 50MB vault included on the free plan with a Pro tier coming soon.
- **Session Persistence:** Optional "Remember Me" skips login on startup while keeping your vault secure.
- **Ctrl+U Shortcut:** Trigger a deposit from anywhere in the app instantly.
- **WebP Support:** Upload JPEG, PNG, GIF, BMP, and WebP images.
- **System Logs Tab:** Full deposit history with ghost-mode-aware name masking.
- **Support Tab:** Built-in contact panel with response time guidance and direct email links.

---

## 📥 Installation

1. Download the latest `vantageinstaller.exe` from the [Releases](https://github.com/VantageVault/Vantage-vault/releases) page.
2. Run the installer — Windows may show a SmartScreen prompt on first run, click **More Info → Run Anyway**. The build is Microsoft-verified.
3. Launch Vantage, create a node (account), verify your email, and save your recovery code somewhere safe.

---

## ⚠️ Beta Disclaimer

This is a **Beta** release. Core features are stable but you may encounter edge cases.

- Do **not** use Vantage as your only backup for critical files during the beta period.
- The **50MB free vault limit** is enforced both client-side and server-side.
- If an upload fails, check your internet connection and try again — the app will attempt a token refresh automatically before reporting an error.
- Ghost Mode hides names and blurs images in the UI only — your vault data is always encrypted regardless of this setting.
- Please report bugs before posting publicly — see the Support section below.

---

 🌐 Community & Support

Join our Discord for the **Beta Tester** role, bug reports, and announcements:
👾 **https://discord.gg/DCNfAcfgsN**

| Channel | Use |
|---|---|
| `support` | Open a ticket if you need support |
| `bug-reports` | Report bugs with your Node ID and steps to reproduce |
| `suggestions` | Feature requests — we review these daily/weekly |

---

 📬 Contact

| Purpose | Email |
|---|---|
| bugs / billing / account | support@vantagevault.dev |
| General enquiries | contact@vantagevault.dev |
| Security vulnerabilities | security@vantagevault.dev |

**Found a security issue?** Please email **security@vantagevault.dev** directly and do NOT post it publicly. We respond within 12-24 hours and will credit you in the changelog.

---

 🔭 Coming Soon

- Pro tier with expanded storage
- macOS & Linux builds
- Google Sign-In
- TOTP-based MFA (authenticator app)
- Browser extension vault integration

---

**SyncPointFlow** | *Security First.* | [vantagevault.dev](https://vantagevault.dev)
