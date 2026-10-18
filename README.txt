WhatsApp Leads Manager — prototype

What it does:
- Imports a user-selected WhatsApp chat .txt export.
- Uses offline keyword rules to categorize message text.
- Shows detected date range and message count for imported chat records.
- Exports a CSV file that opens in Excel.
- Does not require a WhatsApp API, paid AI API, account login, or server.

Important limitations:
- This is a web prototype, NOT an Android APK.
- It cannot automatically read WhatsApp's private database or fetch all chats.
- WhatsApp export formats vary. Phone number extraction is best-effort; exported files may not include the other participant's phone number.
- Ad attribution is marked Unknown unless a campaign marker appears in the message text. Ordinary exports generally do not preserve reliable Meta ad referral metadata.
- Categorization is keyword-based, not a generative AI model.
- Data is processed locally in the browser and is not uploaded to a server.

To use:
1. Open index.html in a modern browser.
2. Export a WhatsApp chat as .txt without media.
3. Select the .txt file and tap Import & Categorize.
4. Search/filter and tap Download Excel CSV.
