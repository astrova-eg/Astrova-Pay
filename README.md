<div align="center">
  <h1>💳 Astrova Pay</h1>
  <h3>Developed by <a href="https://astrova.online">Astrova</a></h3>

  <p>
    <strong>Egyptian Digital Wallets, Vodafone Cash, InstaPay IPN & Visa Payment Gateway for WooCommerce & Custom Websites</strong><br />
    Enterprise-Grade Payment Confirmation & Financial Reconciliation Engine for Egypt & MENA.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Developer-Astrova-0F172A?style=for-the-badge" alt="Developed by Astrova" />
    <img src="https://img.shields.io/badge/Release-v1.0.0-0066FF?style=for-the-badge" alt="Release v1.0.0" />
    <img src="https://img.shields.io/badge/WordPress-6.0%2B-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress 6.0+" />
    <img src="https://img.shields.io/badge/WooCommerce-HPOS%20Ready-96588A?style=for-the-badge&logo=woocommerce&logoColor=white" alt="WooCommerce HPOS" />
    <img src="https://img.shields.io/badge/PHP-8.1%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.1+" />
    <img src="https://img.shields.io/badge/License-Proprietary-EF4444?style=for-the-badge" alt="Proprietary License" />
  </p>

  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-supported-payment-methods">Payment Methods</a> •
    <a href="#-key-features">Features</a> •
    <a href="#-bank-grade-security">Security</a> •
    <a href="#-installation--setup">Installation</a> •
    <a href="#-frequently-asked-questions">FAQ</a> •
    <a href="#-license">License</a>
  </p>
</div>

<hr />

## 🚀 Overview

**Astrova Pay** is a flagship commercial payment confirmation and financial reconciliation gateway engineered and developed by **Astrova**. Built specifically for the Egyptian and MENA e-commerce ecosystem, it enables merchants, store owners, and software developers to accept direct, zero-fee peer-to-peer and card payments without complex merchant onboarding bottlenecks.

Architected with a decoupled, modular core, **Astrova Pay** operates natively inside **WooCommerce** while also supporting seamless activation and integration across **Custom-Built Websites** (Custom PHP, Laravel, and REST APIs).

---

## 💳 Supported Payment Methods

<table>
  <tr>
    <td align="center" width="33%">
      <h3>📱 Egyptian Digital Wallets</h3>
      <p>Instant wallet-to-wallet transfers across all major telecom and bank wallets in Egypt:</p>
      <p><strong>Vodafone Cash • Etisalat Cash<br />Orange Cash • WE Pay • Meeza Wallets</strong></p>
    </td>
    <td align="center" width="33%">
      <h3>⚡ InstaPay IPN</h3>
      <p>Real-time interbank transfers via Instant Payment Address (IPA) or bank account number with one-click copy functionality and instant notification logging.</p>
    </td>
    <td align="center" width="33%">
      <h3>💳 Visa & Mastercard</h3>
      <p>Streamlined card payment processing support for local and international debit/credit cards with unified order reconciliation.</p>
    </td>
  </tr>
</table>

---

## ✨ Key Features

<table>
  <thead>
    <tr>
      <th align="left" width="28%">Feature</th>
      <th align="left" width="72%">Technical & Commercial Specification</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>⚡ WooCommerce HPOS Ready</strong></td>
      <td>Officially declares full compatibility with WooCommerce <strong>High-Performance Order Storage (HPOS)</strong>, eliminating legacy <code>wp_postmeta</code> bottlenecks for high-volume stores.</td>
    </tr>
    <tr>
      <td><strong>🧱 Checkout Blocks Support</strong></td>
      <td>Native integration with <code>@woocommerce/blocks-checkout</code>, ensuring seamless rendering on both modern React-based block checkouts and classic shortcode checkouts.</td>
    </tr>
    <tr>
      <td><strong>🌐 Custom Websites Support</strong></td>
      <td>Flexible licensing and integration architecture by <strong>Astrova</strong> enabling activation on both WordPress/WooCommerce stores and standalone custom-coded web applications.</td>
    </tr>
    <tr>
      <td><strong>🖥️ Single-Screen Reconciliation</strong></td>
      <td>Dedicated Merchant Administrative Dashboard featuring real-time KPI metrics, a pending review queue, exact amount matching, and an inline secure receipt viewer.</td>
    </tr>
    <tr>
      <td><strong>⚙️ Financial State Machine</strong></td>
      <td>Deterministic, bank-grade order state transitions preventing duplicate approvals, race conditions, or invalid payment status overrides.</td>
    </tr>
    <tr>
      <td><strong>🌍 RTL & Egyptian Localization</strong></td>
      <td>100% localized into Egyptian Arabic with an RTL-native user interface tailored to local buyer behavior, alongside full English administrative support.</td>
    </tr>
  </tbody>
</table>

---

## 🛡️ Bank-Grade Security

Engineered by **Astrova** with defense-in-depth security protocols to protect financial records and customer payment proofs from unauthorized access or tampering:

* **Fortified Receipt Storage:** Uploaded payment screenshots are stored inside an isolated directory (`wp-content/uploads/astrovapay_proofs/`) hardened with `.htaccess` rules and `index.php` guards to strictly block direct HTTP web access.
* **Anti-IDOR Secure File Streamer:** Receipts are served exclusively to authorized store administrators via a nonce-signed streaming controller completely immune to **IDOR** and **Path Traversal** attacks.
* **MIME Magic Bytes Verification:** Deep binary file inspection validates actual file headers (Magic Bytes) rather than trusting file extensions, neutralizing malicious file upload attempts.
* **Transient Sliding Rate Limiter:** Protects checkout and proof-submission endpoints against spam and brute-force abuse using transient-based rate limiting with cryptographic IP salting.
* **Forensic Immutable Audit Trail:** Every payment submission, status change, and admin verification action is recorded in an **Append-Only** audit log for complete financial accountability.

---

## ⚙️ Installation & Setup

### 1. Plugin Installation
1. Download the `astrova-pay.zip` package or clone this repository into your `/wp-content/plugins/` directory.
2. Navigate to **WordPress Admin → Plugins** and click **Activate** on **Astrova Pay**.

### 2. License Activation (WooCommerce & Custom Sites)
1. Open the **Astrova Pay → License** settings panel.
2. Enter your registered **Email Address**, **License Key**, and **Active Domain** issued by **Astrova** to unlock full gateway capabilities and updates.

### 3. Gateway Configuration
1. Go to **WooCommerce → Settings → Payments → Astrova Pay**.
2. Enter your **Merchant Wallet Number** (Vodafone Cash / InstaPay IPA) and **Account Holder Name**.
3. Configure optional parameters such as receipt upload requirements, allowed file sizes, and manual/auto review modes.
4. Click **Save changes**.

---

## ❓ Frequently Asked Questions

<details>
<summary><strong>Does Astrova Pay require an official Vodafone merchant API?</strong></summary>
<br />
No. Astrova Pay is engineered as a direct peer-to-peer / wallet-to-wallet payment confirmation gateway. Customers transfer funds directly to your Vodafone Cash number or InstaPay address and submit the transaction confirmation reference (along with a receipt screenshot), which you verify in one click from your admin dashboard.
</details>

<details>
<summary><strong>Is Astrova Pay compatible with WooCommerce HPOS?</strong></summary>
<br />
Yes! Astrova Pay officially declares full compatibility with WooCommerce High-Performance Order Storage (HPOS) and does not rely on legacy post meta queries, ensuring optimal database performance at scale.
</details>

<details>
<summary><strong>Can customers pay using WooCommerce Checkout Blocks?</strong></summary>
<br />
Yes! Astrova Pay includes full native integration for <code>@woocommerce/blocks-checkout</code>, allowing seamless operation with modern block-based checkouts as well as classic shortcode checkouts.
</details>

<details>
<summary><strong>Can I use Astrova Pay on custom-coded websites outside WordPress?</strong></summary>
<br />
Yes. Astrova Pay supports licensing and integration for both WooCommerce stores and custom-built web applications (PHP/Laravel/REST APIs).
</details>

<details>
<summary><strong>Where are customer proof images stored?</strong></summary>
<br />
Receipts are stored in an isolated directory (<code>wp-content/uploads/astrovapay_proofs/</code>) fortified with <code>.htaccess</code> and <code>index.php</code> guards. Direct web access to these files is strictly denied; only store administrators can view them through a secure, nonce-signed streaming controller.
</details>

---

## 📝 Changelog

### `1.0.0` — Initial Commercial Release
* **Core:** Initial commercial release of **Astrova Pay** by **Astrova**, supporting Egyptian Digital Wallets, Vodafone Cash, InstaPay IPN, and Visa/Mastercard.
* **Compatibility:** Full WooCommerce HPOS & Checkout Blocks (`@woocommerce/blocks-checkout`) integration, plus Custom Site activation support.
* **Security:** Fortified receipt storage with MIME Magic Bytes verification, Anti-IDOR / Path Traversal immune secure file streamer, and transient sliding rate limiter with IP salting.
* **Auditing:** Bank-grade financial state machine and immutable append-only forensic audit trail.
* **Localization:** 100% Egyptian Arabic localization and RTL-native UI.

---

## 📄 License

**Proprietary Commercial Software**  
This software is exclusively developed, owned, and maintained by **Astrova** (`https://astrova.online`). Unauthorized copying, redistribution, modification, reverse engineering, or commercial deployment without an active license key issued by **Astrova** is strictly prohibited.

<div align="center">
  <br />
  <p>Developed & Engineered by <strong><a href="https://astrova.online">Astrova</a></strong></p>
  <p><sub>Copyright © 2026 Astrova. All Rights Reserved.</sub></p>
</div>
