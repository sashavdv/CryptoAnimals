# CryptoAnimals
# Privacy Policy for Crypto Crash Animal Therapy

## Last Updated: [Insert Date]

### 1. **Introduction**
Crypto Crash Animal Therapy ("the Extension") is a Chrome browser extension designed to replace crypto-related terms on Twitter/X with fun animal facts and images. We take your privacy seriously and want to ensure you understand what data (if any) we collect and how we use it.

### 2. **Data Collection and Usage**
- This extension **does not collect, store, or share any personal data**.
- No user browsing history, account details, or personally identifiable information is accessed or stored.

### 3. **Permissions Explained**
To function correctly, the Extension requires the following permissions:
- **`storage` (REMOVED)**: Previously used to store user preferences (now handled via `localStorage`, which does not require permissions).
- **`content_scripts`**: Used to modify webpage content on Twitter/X by replacing crypto-related terms with animal facts and GIFs.
- **`host_permissions` (`https://api.giphy.com/*`) (REMOVED)**: Previously needed to fetch GIFs (now handled using `fetch()` directly in the content script).
- **`host_permissions` (`https://x.com/*`, `https://twitter.com/*`)**: Required to allow the extension to detect and modify crypto-related terms in tweets.

### 4. **Third-Party APIs**
- The Extension uses the **Giphy API** to retrieve random animal GIFs.
- No user data is sent to or stored by Giphy.

### 5. **Security Measures**
- The Extension does not track, collect, or share any browsing activity.
- The Extension does not communicate with external servers beyond fetching GIFs from Giphy.

### 6. **Contact Information**
If you have any questions or concerns about this Privacy Policy, please contact us at [Your Email or Website].

### 7. **Changes to This Privacy Policy**
This Privacy Policy may be updated periodically. Any changes will be reflected here with a new last updated date.

By using this extension, you agree to the terms of this Privacy Policy.

