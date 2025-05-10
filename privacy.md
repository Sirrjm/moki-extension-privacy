1. Introduction
This Privacy Policy describes how Moki Helper (the "Extension"), an internal tool, handles your information when you use it to assist with Shopify backoffice tasks. This Extension is intended for use by authorized team members on designated Shopify stores.

2. Information We Collect, Process, and Store
To provide its functionalities, the Extension requires access to and may store the following types of information:
API Credentials (Stored Locally):
Google Gemini API Key: Provided by you, stored locally using chrome.storage.sync. Used solely to make API calls to Google Gemini services for AI content generation (product descriptions, SEO summaries, image alt text, filenames) on your behalf.
Google Custom Search API Key & CX ID: Provided by you, stored locally using chrome.storage.sync. Used solely to make API calls to Google Custom Search for image suggestion features on your behalf.
Shopify Admin API Access Token & Store Domain: Provided by you, stored locally using chrome.storage.sync. Used solely to make authenticated GraphQL API calls to your configured Shopify store for data retrieval (products, SKUs, variants, customers, orders, product media) and to update product image details (alt text, filenames).
We do not have access to these API keys; they are stored only in your browser's local, synchronized storage and sent directly to the respective Google or Shopify API endpoints by the Extension operating on your computer.
Shopify Store Data (Processed, Not Stored by Extension Long-Term, except via Chat Links):
Product Information: When using AI content generation or image optimization features, the Extension reads product titles, existing descriptions, vendor details, and image data (URLs/GIDs) from the active Shopify product admin page. This information is processed and sent to the relevant external APIs (Gemini, Shopify) to perform the requested actions. The generated content is then used to populate fields on the Shopify page.
SKU/Barcode, Customer, and Order Data: When using the respective search features, the Extension sends your search queries to your Shopify store via the Shopify Admin API and displays the results. This data is fetched on demand and not persistently stored by the Extension itself, except as noted below for chat.
Internal Chat Communications (Stored in Firebase):
Chat Messages: Text messages, and structured data representing links to Shopify customers or orders that you create and send using the internal team chat feature, are transmitted to and stored in a Firebase Realtime Database project configured for your team's use.
Sender Information: Your chosen display name (currently "MokiUser" or a future authenticated name/ID) and a timestamp are stored with each chat message in Firebase.
This chat data is intended for internal team collaboration and is stored on the Firebase platform under an account managed by our team/organization.
Firebase Authentication Information (Future):
For planned user authentication features for the chat, we will use Firebase Authentication, which may involve collecting email addresses or other identifiers as provided during the authentication process.
Firebase Storage (Future):
For planned chat file attachment features, files you upload will be stored in Firebase Storage under an account managed by our team/organization.

3. How We Use Your Information
The information handled by the Extension is used exclusively for the following purposes:
To enable the core functionalities of the Extension as described (AI content generation, image suggestions, SKU/Customer/Order search, image detail updates, internal team chat).
To authenticate your requests to external services (Google APIs, Shopify API) using the API keys you provide.
To store and retrieve chat messages for your team's internal communication via Firebase.
To store your configured API keys and settings locally for your convenience across browsing sessions.

4. Data Sharing and Third Parties
We only share data with third-party services as strictly necessary for the Extension to function:
Google (Gemini API, Custom Search API, Firebase Authentication): Your provided Google API keys, relevant product data (for Gemini/Search), and authentication identifiers (for Firebase Auth) are sent to Google's respective API endpoints. Please refer to Google's Privacy Policy for how they handle data.
Shopify (Admin API): Your Shopify Admin API Access Token and relevant data queries/mutations are sent to your configured Shopify store's Admin API endpoint. You are interacting with your own store's data.
Firebase (Realtime Database, Storage - Latter is Future): Chat messages and future file attachments are stored on Google's Firebase platform, within a project designated for your team's use of this internal tool.
We do not sell, rent, or otherwise share your API keys or the content of your internal chat messages with any other unrelated third parties.

5. Data Security
API keys and configuration settings are stored locally in your browser using chrome.storage.sync. Chat data is stored in Firebase, which employs industry-standard security measures. While we strive to use acceptable means to protect information, please remember that no method of transmission over the Internet or method of electronic storage is 100% secure and guaranteed. You are responsible for the security of your own API keys.

6. Data Retention
Locally Stored API Keys: Remain stored in your browser's chrome.storage.sync until you clear them via the extension's popup or uninstall the extension.
Chat Messages in Firebase: Chat messages are stored in the Firebase Realtime Database. Data retention policies for this Firebase project are managed by our team/organization. (You should define this internally - e.g., "messages are retained for X days/months" or "indefinitely until manually cleared").

7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the extension or via an internal announcement. You are advised to review this Privacy Policy periodically for any changes. Changes are effective when they are posted.

8. Contact Us
If you have any questions about this Privacy Policy, please contact us:
Kaelus.dreamer@gmail.com
