###### _*Last updated: June 18, 2026*_

### PRIVACY POLICY

#### 🏁 What is `verygood`
It is a browser extension that exports your session credentials and browser context from supported platforms 
(LinkedIn, Instagram, Facebook) to a webhook endpoint that you configure.

#### 🪣 Data collection
When you enable a platform and configure a webhook, the extension collects:
- **Session cookies** from supported platforms (e.g. JSESSIONID, csrftoken)
- **Request headers** (e.g. CSRF tokens)
- **Browser context**: user agent, platform, language, timezone, hardware concurrency, device memory, screen
dimensions, color depth, pixel ratio, WebGL vendor/renderer, connection type, and preferences

#### 💽 Data usage
- All collected data is sent via HTTPS POST <ins>**exclusively to the webhook URL you configure**</ins>
- The extension developer <ins>**does not receive, store, access, or process any of your data**</ins>
- No analytics, tracking pixels, or third-party services are used
- No data is sold or shared with third parties

#### 🎛️ User full control
- You choose which platforms to enable or disable
- You configure your own webhook destination
- No data is collected or transmitted until you set a webhook and enable a platform
- You can stop all data collection at any time by toggling off platforms or uninstalling the extension
- All settings are stored locally in your browser via `chrome.storage.local`

#### 🌐 External communication
Only the domain `vickydb.tech` can update your webhook URL and user identifier via the browser extension messaging API. This 
only occurs when you are an active user on that site. No other external site can communicate with the extension.

#### ⚠️ Security notice
- You are solely responsible for the security of your webhook endpoint
- Never accept a webhook configuration from a source you do not trust
- Anyone with control over your webhook URL can receive your session credentials

#### 🔄 Changes
We may update this policy from time to time. Changes will be reflected by the "Last updated" date above.

#### 📫 Contact
For questions or concerns, reach out at: `vickydebondi@gmail.com`

### TERMS OF USE
- You agree to use this extension only for your own accounts and data
- You are responsible for how you use the exported credentials
- The extension is provided "as is" without warranty of any kind
- The developer is not liable for any damages arising from the use or misuse of this extension or the data it exports
- Violation of any platform's terms of service using exported credentials is your sole responsibility
