# 📷 WhatsApp Image Messaging API

Easily send image messages via WhatsApp using Maytapi's powerful API.

## 🚀 Features

- Send image messages using a URL
- Send image messages from Base64 encoded data
- Include optional captions
- Handles API errors gracefully

## 📦 Installation

```bash
npm install axios
```
## 🔧 Usage Example
```javascript
const WhatsAppAPI = require('./index');

const api = new WhatsAppAPI({
  productId: "YOUR_PRODUCT_ID",
  phoneId: "YOUR_PHONE_ID",
  apiToken: "YOUR_API_TOKEN"
});

api.sendImageMessage({
  to: "1234567890",
  imageUrl: "https://example.com/image.jpg",
  caption: "Check out this image!"
})
.then(response => {
  console.log("Message sent:", response);
})
.catch(error => {
  console.error("Error:", error);
});
```
## 🔐 Authentication
To use the API, you'll need:

- Product ID
- Phone ID
- API Token
##🧪 Methods
sendImageMessage({ to, imageUrl, caption }): Send an image from a URL.

sendImageFromBase64({ to, base64Data, caption }): Send an image from Base64 data.

## 🧠 Error Handling
Provides detailed error messages via console for easier debugging.

📄 License
MIT License
##🤝 Support
For issues or questions, please open a GitHub issue.
