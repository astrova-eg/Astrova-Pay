<div align="center">
  <h1>💳 Astrova Pay</h1>
  <h3>Developed by <a href="https://astrova.online">Astrova</a></h3>

  <p>
    <strong>Egyptian Digital Wallets, Vodafone Cash, InstaPay IPN & Visa Payment Gateway for WooCommerce & Custom Websites</strong><br />
    Enterprise-Grade Payment Confirmation, Universal REST API & Financial Reconciliation Engine for Egypt & MENA.
  </p>

  <br />

  <table>
    <tr>
      <td align="center" bgcolor="#0066FF">
        <a href="https://astrova.online/product/astrovapay-woocommerce-payment-gateway/" target="_blank">
          <br />
          &nbsp;&nbsp;&nbsp;&nbsp;<strong>🚀 GET ASTROVA PAY — OFFICIAL LICENSE & DOWNLOAD</strong>&nbsp;&nbsp;&nbsp;&nbsp;
          <br /><br />
        </a>
      </td>
    </tr>
  </table>

  <br />

  <p>
    <kbd>Developer: Astrova</kbd> &nbsp;
    <kbd>Release: v1.0.0</kbd> &nbsp;
    <kbd>WordPress: 6.0+</kbd> &nbsp;
    <kbd>WooCommerce: HPOS Ready</kbd> &nbsp;
    <kbd>API: REST & Webhooks</kbd> &nbsp;
    <kbd>License: Proprietary</kbd>
  </p>

  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-supported-payment-methods">Payment Methods</a> •
    <a href="#-key-features">Features</a> •
    <a href="#-woocommerce-installation--setup">WooCommerce Setup</a> •
    <a href="#-universal-api-developer-guide">Universal API Guide</a> •
    <a href="#-frequently-asked-questions">FAQ</a> •
    <a href="#-license">License</a>
  </p>
</div>

<hr />

## 🚀 Overview

**Astrova Pay** is a flagship commercial payment confirmation, Universal API gateway, and financial reconciliation engine engineered and developed by **Astrova**. Built specifically for the Egyptian and MENA digital ecosystem, it enables merchants, e-commerce stores, and software developers to accept direct peer-to-peer and card payments without complex merchant onboarding bottlenecks.

Architected with a decoupled, modular core, **Astrova Pay** operates natively inside **WooCommerce** while simultaneously providing a full-featured **Universal REST API & HMAC-Signed Webhook Engine** for **Custom-Built Websites** (Laravel, SMM Matrix, SMM Panels, Node.js, Python, and Native PHP).

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
      <p>Real-time interbank transfers via Instant Payment Address (IPA) or bank account number with one-click copy functionality and instant IPN notifications.</p>
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
      <td><strong>🌐 Universal REST API & IPN</strong></td>
      <td>Direct programmatic integration for <strong>Laravel, SMM Matrix, SMM Panels, Node.js, and Custom PHP</strong> applications with automated HMAC-SHA256 webhook callbacks.</td>
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

Engineered by **Astrova** with defense-in-depth security protocols to protect financial records, API endpoints, and customer payment proofs:

* **Fortified Receipt Storage:** Uploaded payment screenshots are stored inside an isolated directory (`wp-content/uploads/astrovapay_proofs/`) hardened with `.htaccess` rules and `index.php` guards to strictly block direct HTTP web access.
* **Anti-IDOR Secure File Streamer:** Receipts are served exclusively to authorized store administrators via a nonce-signed streaming controller completely immune to **IDOR** and **Path Traversal** attacks.
* **MIME Magic Bytes Verification:** Deep binary file inspection validates actual file headers (Magic Bytes) rather than trusting file extensions, neutralizing malicious file upload attempts.
* **HMAC-SHA256 Webhook Signatures & Replay Protection:** All IPN callbacks are cryptographically signed (`X-Astrova-Signature`) with a strict 5-minute timestamp window (`X-Astrova-Timestamp`) to eliminate spoofing and replay attacks.
* **Transient Sliding Rate Limiter:** Protects checkout and proof-submission endpoints against spam and brute-force abuse using transient-based rate limiting with cryptographic IP salting.
* **Forensic Immutable Audit Trail:** Every payment submission, status change, and admin verification action is recorded in an **Append-Only** audit log for complete financial accountability.

---

## ⚙️ WooCommerce Installation & Setup

### 1. Purchase & Download
1. Obtain your official commercial license and plugin package from the **[Astrova Official Store](https://astrova.online/product/astrovapay-woocommerce-payment-gateway/)**.
2. Upload the `astrova-pay.zip` package via **WordPress Admin → Plugins → Add New → Upload Plugin**, or extract it into `/wp-content/plugins/`.
3. Click **Activate** on **Astrova Pay**.

### 2. License Activation
1. Open the **Astrova Pay → License** settings panel.
2. Enter your registered **Email Address**, **License Key**, and **Active Domain** issued by **Astrova** to unlock full gateway capabilities and updates.

### 3. Gateway Configuration
1. Go to **WooCommerce → Settings → Payments → Astrova Pay**.
2. Enter your **Merchant Wallet Number** (Vodafone Cash / InstaPay IPA) and **Account Holder Name**.
3. Configure optional parameters such as receipt upload requirements, allowed file sizes, and manual/auto review modes.
4. Click **Save changes**.

---

## 🔌 Universal API Developer Guide

**Astrova Pay** provides a direct REST API for custom web applications, SaaS platforms, **Laravel**, **SMM Matrix**, **SMM Panels**, and **Node.js**.

### 1. API Endpoints & Base URLs

| Resource | Endpoint URL |
| :--- | :--- |
| **API Base Server** | `https://www.astrova.online` |
| **Create Checkout Session (`POST`)** | `https://www.astrova.online/wp-json/astrova/v1/checkout/session` |
| **Verify Session Status (`GET`)** | `https://www.astrova.online/wp-json/astrova/v1/checkout/session/{session_id}` |
| **Hosted Checkout Page** | `https://www.astrova.online/pay/{session_id}` |
| **Merchant Portal & API Keys** | `https://www.astrova.online/astrova-portal/#licenses-apigateway` |

---

### 2. Authentication & API Credentials

Generate your API credentials from the **Astrova Merchant Portal**:
* **Public Key (`pk_live_...`):** Identifies your merchant account.
* **Secret Key (`sk_live_...`):** Signs API requests and verifies incoming webhooks (**Never expose in frontend code**).

#### Supported Authentication Headers:
1. **Standard Bearer Token:**
   ```http
   Authorization: Bearer sk_live_YOUR_SECRET_KEY
   ```
2. **High-Security HMAC Signature:**
   ```http
   X-Astrova-Public-Key: pk_live_YOUR_PUBLIC_KEY
   X-Astrova-Timestamp: 1730376000
   X-Astrova-Signature: <hmac_sha256(timestamp + "." + json_body, secret_key)>
   ```

---

### 3. Automated Payment Lifecycle

```text
[Your Website / Store / SMM Platform]
       │
       │ 1. Create Checkout Session (POST /checkout/session)
       ▼
[Astrova Pay Server (www.astrova.online)]
       │
       │ 2. Returns Hosted Payment URL (checkout_url)
       ▼
[Redirect Customer to Hosted Checkout] ──► [Pays via InstaPay / E-Wallet & Uploads Proof]
                                                       │
                                                       ▼
                                         [Instant Merchant Verification]
                                                       │
       ┌───────────────────────────────────────────────┘
       │ 3. Sends Encrypted Webhook (X-Astrova-Signature)
       ▼
[Your Webhook Endpoint] ──► [Verifies Signature & Credits User Balance Instantly ✅]
```

---

### 4. Create Checkout Session (`POST`)

#### Request Headers:
```http
Content-Type: application/json
Authorization: Bearer sk_live_YOUR_SECRET_KEY
```

#### Request JSON Payload:
```json
{
  "order_id": "TRX-948210",
  "amount": 250.00,
  "currency": "EGP",
  "customer_name": "Customer Full Name",
  "customer_phone": "01000000000",
  "customer_email": "customer@yourdomain.com",
  "return_url": "[https://yourdomain.com/payment/success](https://yourdomain.com/payment/success)",
  "cancel_url": "[https://yourdomain.com/payment/failed](https://yourdomain.com/payment/failed)",
  "webhook_url": "[https://yourdomain.com/api/astrova-webhook](https://yourdomain.com/api/astrova-webhook)"
}
```

#### Success Response (`HTTP 200 OK`):
```json
{
  "success": true,
  "session_id": "cs_live_9f81a7b489a2b63892",
  "checkout_url": "[https://www.astrova.online/pay/cs_live_9f81a7b489a2b63892](https://www.astrova.online/pay/cs_live_9f81a7b489a2b63892)",
  "amount": 250.00,
  "currency": "EGP",
  "expires_at": "2026-10-31 14:00:00"
}
```
> **Next Step:** Redirect the customer's browser directly to `checkout_url`.

---

### 5. Ready-to-Use Integration Examples

<details>
<summary><strong>🎯 SMM Matrix (Laravel / ViserLab Architecture)</strong></summary>

#### Step 1: Create Gateway Controller
Create `app/Http/Controllers/Gateway/AstrovaPay/ProcessController.php`:

```php
<?php

namespace App\Http\Controllers\Gateway\AstrovaPay;

use App\Http\Controllers\Controller;
use App\Http\Controllers\Gateway\PaymentController;
use App\Models\Deposit;
use Illuminate\Http\Request;
use Illuminate\Support\Facades\Http;
use Illuminate\Support\Facades\Log;

class ProcessController extends Controller
{
    private string $apiEndpoint = '[https://www.astrova.online/wp-json/astrova/v1/checkout/session](https://www.astrova.online/wp-json/astrova/v1/checkout/session)';

    /**
     * Initiate Deposit & Redirect User to Hosted Checkout
     */
    public static function process($deposit)
    {
        $secretKey = env('ASTROVA_SECRET_KEY');
        $user =$deposit->user;

        try {
            $response = Http::withToken($secretKey)
                ->timeout(15)
                ->post('[https://www.astrova.online/wp-json/astrova/v1/checkout/session](https://www.astrova.online/wp-json/astrova/v1/checkout/session)', [
                    'order_id'       => $deposit->trx,
                    'amount'         => round($deposit->final_amo, 2),
                    'currency'       => 'EGP',
                    'customer_name'  => $user->fullname ?? $user->username,
                    'customer_phone' => $user->mobile ?? '',
                    'customer_email' => $user->email ?? '',
                    'return_url'     => route('user.deposit.history'),
                    'cancel_url'     => route('user.deposit.index'),
                    'webhook_url'    => route('ipn.astrovapay'),
                ]);

            if ($response->successful() && isset($response['checkout_url'])) {$send['redirect'] = true;
                $send['redirect_url'] =$response['checkout_url'];
            } else {
                $send['error'] = true;
                $send['message'] =$response['message'] ?? 'Failed to connect to Astrova Pay gateway.';
            }
        } catch (\Exception $e) {$send['error'] = true;
            $send['message'] = 'Payment initialization error: ' .$e->getMessage();
        }

        return json_encode($send);
    }

    /**
     * Webhook / IPN Handler for Instant Balance Crediting
     */
    public function ipn(Request $request)
    {
        $secretKey = env('ASTROVA_SECRET_KEY');
        $signature =$request->header('X-Astrova-Signature');
        $timestamp =$request->header('X-Astrova-Timestamp');
        $rawPayload =$request->getContent();

        if (empty($signature) \vert{}\vert{} empty($timestamp)) {
            Log::warning('AstrovaPay IPN: Missing signature headers');
            return response()->json(['error' => 'Missing headers'], 400);
        }

        // Prevent Replay Attacks (5-minute window)
        if (abs(time() - (int)$timestamp) > 300) {
            Log::warning('AstrovaPay IPN: Timestamp expired');
            return response()->json(['error' => 'Expired timestamp'], 400);
        }

        // Verify HMAC-SHA256 Signature
        $expectedSignature = hash_hmac('sha256', "{$timestamp}.{$rawPayload}", $secretKey);
        if (!hash_equals($expectedSignature,$signature)) {
            Log::error('AstrovaPay IPN: Invalid HMAC signature detected!');
            return response()->json(['error' => 'Invalid signature'], 401);
        }

        $payload = json_decode($rawPayload, true);
        if (!$payload \vert{}\vert{} !isset($payload['event'])) {
            return response()->json(['error' => 'Invalid payload'], 400);
        }

        if ($payload['event'] === 'checkout.completed') {
            $trx =$payload['data']['order_id'] ?? null;
            $deposit = Deposit::where('trx',$trx)->where('status', 2)->first(); // 2 = Pending

            if ($deposit) {
                PaymentController::userDataUpdate($deposit);
                Log::info("AstrovaPay IPN: Successfully credited Deposit TRX #{$trx}");
                return response()->json(['status' => 'success', 'message' => 'Deposit approved']);
            }
        }

        return response()->json(['status' => 'ignored']);
    }
}
```

#### Step 2: Register IPN Route (`routes/web.php` or `routes/api.php`):
```php
Route::post('ipn/astrovapay', [App\Http\Controllers\Gateway\AstrovaPay\ProcessController::class, 'ipn'])
    ->name('ipn.astrovapay')
    ->withoutMiddleware([\App\Http\Middleware\VerifyCsrfToken::class]);
```
</details>

<details>
<summary><strong>⚡ General SMM Panels (SmartPanel / PerfectPanel / Native PHP)</strong></summary>

#### 1. Initiate Payment (`initiate_payment.php`):
```php
<?php
$secretKey = 'sk_live_YOUR_SECRET_KEY';$apiUrl    = '[https://www.astrova.online/wp-json/astrova/v1/checkout/session](https://www.astrova.online/wp-json/astrova/v1/checkout/session)';

$orderId   = 'DEP_' . uniqid();
$amount    = (float)$_POST['amount'];
$userEmail =$_SESSION['user_email'] ?? 'user@yourdomain.com';
$userName  =$_SESSION['username'] ?? 'SMM User';

$payload = json_encode([
    'order_id'       => $orderId,
    'amount'         => $amount,
    'currency'       => 'EGP',
    'customer_name'  => $userName,
    'customer_email' => $userEmail,
    'return_url'     => '[https://yourdomain.com/addfunds?status=success](https://yourdomain.com/addfunds?status=success)',
    'cancel_url'     => '[https://yourdomain.com/addfunds?status=cancel](https://yourdomain.com/addfunds?status=cancel)',
    'webhook_url'    => '[https://yourdomain.com/webhook/astrovapay.php](https://yourdomain.com/webhook/astrovapay.php)',
]);

// Save pending transaction in database
$stmt =$db->prepare("INSERT INTO payments (transaction_id, user_id, amount, status) VALUES (?, ?, ?, 'pending')");
$stmt->execute([$orderId, $_SESSION['user_id'],$amount]);

$ch = curl_init($apiUrl);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
curl_setopt($ch, CURLOPT_POST, true);
curl_setopt($ch, CURLOPT_POSTFIELDS,$payload);
curl_setopt($ch, CURLOPT_HTTPHEADER, [
    'Content-Type: application/json',
    'Authorization: Bearer ' . $secretKey,
]);

$response = curl_exec($ch);
curl_close($ch);

$result = json_decode($response, true);
if (isset($result['checkout_url'])) {
    header('Location: ' . $result['checkout_url']);
    exit;
} else {
    die('Payment session creation failed: ' . ($result['message'] ?? 'Verify API credentials'));
}
```

#### 2. Webhook Receiver (`webhook/astrovapay.php`):
```php
<?php
$secretKey = 'sk_live_YOUR_SECRET_KEY';$signature = $_SERVER['HTTP_X_ASTROVA_SIGNATURE'] ?? '';$timestamp = $_SERVER['HTTP_X_ASTROVA_TIMESTAMP'] ?? '';$rawBody   = file_get_contents('php://input');

if (empty($signature) \vert{}\vert{} empty($timestamp)) {
    http_response_code(400);
    exit('Missing signature headers');
}

// 1. Verify HMAC Signature
$expected = hash_hmac('sha256',$timestamp . '.' . $rawBody,$secretKey);
if (!hash_equals($expected,$signature)) {
    http_response_code(401);
    exit('Invalid HMAC Signature');
}

// 2. Replay Attack Prevention
if (abs(time() - (int)$timestamp) > 300) {
    http_response_code(400);
    exit('Request expired');
}

$data = json_decode($rawBody, true);

// 3. Process Completed Checkout
if (isset($data['event']) &&$data['event'] === 'checkout.completed') {
    $orderId  =$data['data']['order_id'];
    $amount   = (float)$data['data']['amount'];
    $refNum   =$data['data']['reference_number'] ?? '';

    $stmt =$db->prepare("SELECT * FROM payments WHERE transaction_id = ? AND status = 'pending'");
    $stmt->execute([$orderId]);
    $payment =$stmt->fetch();

    if ($payment) {
        $userId =$payment['user_id'];

        $updateUser =$db->prepare("UPDATE users SET balance = balance + ? WHERE id = ?");
        $updateUser->execute([$amount,$userId]);

        $updatePay =$db->prepare("UPDATE payments SET status = 'completed', reference_number = ?, updated_at = NOW() WHERE id = ?");
        $updatePay->execute([$refNum,$payment['id']]);

        http_response_code(200);
        echo json_encode(['status' => 'success', 'credited' => $amount]);
        exit;
    }
}

http_response_code(200);
echo json_encode(['status' => 'ignored']);
```
</details>

<details>
<summary><strong>💻 General Laravel Applications (Service Class)</strong></summary>

```php
<?php

namespace App\Services;

use Illuminate\Support\Facades\Http;
use Illuminate\Http\Request;

class AstrovaPayService
{
    private string $baseUrl = '[https://www.astrova.online/wp-json/astrova/v1](https://www.astrova.online/wp-json/astrova/v1)';
    private string $secretKey;

    public function __construct()
    {
        $this->secretKey = config('services.astrovapay.secret_key');
    }

    public function createSession(array $orderData): string
    {
        $response = Http::withToken($this->secretKey)
            ->timeout(12)
            ->post("{$this->baseUrl}/checkout/session", [
                'order_id'       => $orderData['order_id'],
                'amount'         => $orderData['amount'],
                'currency'       => 'EGP',
                'customer_name'  => $orderData['customer_name'],
                'customer_phone' => $orderData['customer_phone'] ?? '',
                'customer_email' => $orderData['customer_email'] ?? '',
                'return_url'     => route('checkout.success'),
                'cancel_url'     => route('checkout.cancel'),
                'webhook_url'    => route('astrovapay.webhook'),
            ]);

        if (! $response->successful()) {
            throw new \Exception('Failed to create checkout session: ' . $response->body());
        }

        return $response->json('checkout_url');
    }

    public function verifyWebhookSignature(Request $request): bool
    {
        $signature =$request->header('X-Astrova-Signature');
        $timestamp =$request->header('X-Astrova-Timestamp');
        $rawPayload =$request->getContent();

        if (empty($signature) || empty($timestamp) \vert{}\vert{} abs(time() - (int)$timestamp) > 300) {
            return false;
        }

        $expected = hash_hmac('sha256', "{$timestamp}.{$rawPayload}", $this->secretKey);
        return hash_equals($expected,$signature);
    }
}
```
</details>

<details>
<summary><strong>🟩 Node.js / Express Integration</strong></summary>

```javascript
const express = require('express');
const crypto = require('crypto');
const axios = require('axios');

const app = express();
const ASTROVA_API_BASE = '[https://www.astrova.online/wp-json/astrova/v1](https://www.astrova.online/wp-json/astrova/v1)';
const ASTROVA_SECRET_KEY = process.env.ASTROVA_SECRET_KEY; // sk_live_...

// 1. Create Checkout Session
app.post('/api/create-checkout', async (req, res) => {
    try {
        const { orderId, amount, customerName, customerPhone } = req.body;

        const response = await axios.post(`${ASTROVA_API_BASE}/checkout/session`, { order_id: orderId, amount: amount, currency: 'EGP', customer_name: customerName, customer_phone: customerPhone, return_url: '[https://yourdomain.com/order-success](https://yourdomain.com/order-success)', cancel_url: '[https://yourdomain.com/order-cancel](https://yourdomain.com/order-cancel)', webhook_url: '[https://yourdomain.com/api/astrova-webhook](https://yourdomain.com/api/astrova-webhook)' }, { headers: { 'Authorization': `Bearer ${ASTROVA_SECRET_KEY}`,
                'Content-Type': 'application/json'
            },
            timeout: 12000
        });

        res.json({ checkoutUrl: response.data.checkout_url });
    } catch (error) {
        res.status(500).json({ error: error.response?.data || error.message });
    }
});

// 2. Verify & Process Incoming Webhook
app.post('/api/astrova-webhook', express.raw({ type: 'application/json' }), (req, res) => {
    const signature = req.headers['x-astrova-signature'];
    const timestamp = req.headers['x-astrova-timestamp'];
    const rawBody = req.body.toString('utf8');

    if (!signature || !timestamp) {
        return res.status(400).send('Missing signature headers');
    }

    if (Math.abs(Math.floor(Date.now() / 1000) - parseInt(timestamp, 10)) > 300) {
        return res.status(400).send('Timestamp expired');
    }

    const expectedSignature = crypto
        .createHmac('sha256', ASTROVA_SECRET_KEY)
        .update(`${timestamp}.${rawBody}`)
        .digest('hex');

    if (!crypto.timingSafeEqual(Buffer.from(signature), Buffer.from(expectedSignature))) {
        return res.status(401).send('Invalid signature');
    }

    const payload = JSON.parse(rawBody);

    if (payload.event === 'checkout.completed') {
        const { order_id, amount, reference_number } = payload.data;
        console.log(`Payment confirmed for Order #${order_id} (${amount} EGP) - Ref:${reference_number}`);
        // Fulfill order or credit balance in your database
    }

    res.status(200).json({ received: true });
});
```
</details>

### 6. Mandatory Developer Security Guidelines
1. **Protect Your Secret Key:** Store `sk_live_...` strictly in server-side environment variables (`.env`). Never commit it to version control or expose it in client-side code.
2. **Timing-Attack Safe Comparison:** Always use `hash_equals()` in PHP or `crypto.timingSafeEqual()` in Node.js when validating `X-Astrova-Signature`.
3. **Idempotency & Double-Credit Prevention:** Always verify that the local order status is still `pending` before crediting user balances or fulfilling orders.
4. **CSRF Exemption:** Exclude your webhook endpoint from CSRF token verification (e.g., `VerifyCsrfToken` in Laravel) so Astrova servers can deliver IPN callbacks reliably.

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
Yes. Astrova Pay supports licensing and Universal REST API / Webhook integration for custom-built web applications (Laravel, SMM Matrix, SMM Panels, Node.js, and native PHP).
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
* **Compatibility:** Full WooCommerce HPOS & Checkout Blocks (`@woocommerce/blocks-checkout`) integration, plus Universal REST API & Webhook support for Custom Sites.
* **Security:** Fortified receipt storage with MIME Magic Bytes verification, Anti-IDOR / Path Traversal immune secure file streamer, HMAC-SHA256 IPN signatures, and transient sliding rate limiter.
* **Auditing:** Bank-grade financial state machine and immutable append-only forensic audit trail.
* **Localization:** 100% Egyptian Arabic localization and RTL-native UI.

---

## 📄 License

**Proprietary Commercial Software**  
This software is exclusively developed, owned, and maintained by **Astrova** (`https://astrova.online`). Unauthorized copying, redistribution, modification, reverse engineering, or commercial deployment without an active license key issued by **Astrova** is strictly prohibited.

<div align="center">
  <br />
  <table>
    <tr>
      <td align="center">
        <a href="https://astrova.online/product/astrovapay-woocommerce-payment-gateway/" target="_blank">
          <br />
          &nbsp;&nbsp;&nbsp;&nbsp;<strong>💳 PURCHASE COMMERCIAL LICENSE — ASTROVA PAY</strong>&nbsp;&nbsp;&nbsp;&nbsp;
          <br /><br />
        </a>
      </td>
    </tr>
  </table>
  <br />
  <p>Developed & Engineered by <strong><a href="https://astrova.online">Astrova</a></strong></p>
  <p><sub>Copyright © 2026 Astrova. All Rights Reserved.</sub></p>
</div>
