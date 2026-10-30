# https-noadspro.github.noads-privacy-policy.html
NoAds Pro - Privacy Query
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Privacy Policy - NoAds Pro</title>
  <style>
    :root {
      --bg: #090D16;
      --card-bg: #111827;
      --border: #1F2937;
      --text-main: #F3F4F6;
      --text-sub: #9CA3AF;
      --emerald: #10B981;
    }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text-main);
      line-height: 1.6;
      margin: 0;
      padding: 40px 20px;
    }
    .container {
      max-width: 760px;
      margin: 0 auto;
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 32px 28px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    }
    h1 {
      color: #FFFFFF;
      font-size: 1.8rem;
      margin-bottom: 4px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .badge {
      background: rgba(16, 185, 129, 0.15);
      border: 1px solid var(--emerald);
      color: var(--emerald);
      font-size: 0.75rem;
      padding: 2px 8px;
      border-radius: 9999px;
      font-weight: 700;
      text-transform: uppercase;
    }
    .date {
      color: var(--text-sub);
      font-size: 0.85rem;
      margin-bottom: 24px;
    }
    h2 {
      color: var(--emerald);
      font-size: 1.15rem;
      margin-top: 28px;
      border-bottom: 1px solid var(--border);
      padding-bottom: 8px;
    }
    p, li {
      color: #D1D5DB;
      font-size: 0.95rem;
    }
    ul {
      padding-left: 20px;
    }
    .highlight-box {
      background: rgba(16, 185, 129, 0.08);
      border-left: 3px solid var(--emerald);
      padding: 12px 16px;
      margin: 16px 0;
      border-radius: 0 8px 8px 0;
    }
    a {
      color: var(--emerald);
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<div class="container">
  <h1>NoAds Pro <span class="badge">Privacy Policy</span></h1>
  <div class="date">Effective Date: October 31, 2026</div>

  <div class="highlight-box">
    <strong>Core Principle:</strong> Your data never leaves your device. NoAds Pro executes all DNS filtering and tracking prevention locally through an on-device Android loopback interface.
  </div>

  <h2>1. Zero Data Collection & Logging</h2>
  <p>NoAds Pro does not collect, record, track, transmit, or monetize your network traffic, browsing habits, or personal information:</p>
  <ul>
    <li><strong>No DNS Query Logging:</strong> Your domain resolution logs exist exclusively in volatile memory on your device to populate the Activity Log and are never sent to external servers.</li>
    <li><strong>No User Profiling:</strong> We do not collect your name, phone number, IMEI, Android ID, or Advertising ID.</li>
    <li><strong>Support Emails:</strong> If you contact developer support, your email address is used solely to reply and assist with your inquiry.</li>
  </ul>

  <h2>2. Device & Android Permissions</h2>
  <p>NoAds Pro utilizes permissions strictly to provide local firewall functionality:</p>
  <ul>
    <li><strong>Android VpnService:</strong> Used solely to create a local virtual sinkhole on your device to intercept and block ads, trackers, and telemetry before they load. No third-party VPN tunnel or remote proxy is employed.</li>
    <li><strong>Query All Packages (Apps Management):</strong> Used locally to list installed applications, allowing you to configure Shielded, Quarantine, or Bypass rules per application. This inventory never leaves your phone.</li>
    <li><strong>Network Connectivity State:</strong> Used to monitor Wi-Fi/Mobile data switches and execute latency checks for upstream DNS resolvers.</li>
  </ul>

  <h2>3. Third-Party Upstream DNS & Google Play Billing</h2>
  <ul>
    <li><strong>Upstream Providers:</strong> When encrypted upstream resolution is active (AdGuard, Mullvad, or Cloudflare), queries reach the chosen DoH/DoT endpoints according to their respective privacy policies. NoAds Pro injects no intermediate telemetry.</li>
    <li><strong>Subscription Payments:</strong> In-app purchases and the 3-day free trial are processed entirely by Google Play Billing. We never receive or store your financial data or payment credentials.</li>
  </ul>

  <h2>4. Data Retention & Deletion</h2>
  <p>Because NoAds Pro stores zero data on remote servers, there is no remote data to modify or delete. Local on-device statistics can be completely erased at any time via the <em>Reset Statistics</em> button in the Settings menu.</p>

  <h2>5. Contact & Inquiries</h2>
  <p>If you have any questions regarding this Privacy Policy, please contact:</p>
  <ul>
    <li><strong>Developer:</strong> NoAds Pro Developer</li>
    <li><strong>Email:</strong> <a href="mailto:modihima2012@gmail.com">modihima2012@gmail.com</a></li>
  </ul>
</div>

</body>
</html>
