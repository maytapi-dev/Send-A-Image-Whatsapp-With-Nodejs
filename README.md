# 📷 WhatsApp Image Messaging API for JavaScript | Send Images via WhatsApp API

> **Professional WhatsApp API Integration** - Send image messages programmatically using JavaScript/Node.js with Maytapi's powerful WhatsApp API. Perfect for web applications, chatbots, and enterprise automation solutions.

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-16%2B-green.svg)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![WhatsApp API](https://img.shields.io/badge/WhatsApp-API-25D366.svg)](https://maytapi.com/)
[![Maytapi](https://img.shields.io/badge/Powered%20by-Maytapi-orange.svg)](https://maytapi.com/)

## 🌟 Overview

This JavaScript/Node.js library provides seamless integration with **WhatsApp API** for sending image messages programmatically. Designed specifically for modern web applications, chatbots, marketing automation platforms, and enterprise communication systems that require reliable WhatsApp messaging capabilities.

**Perfect for:** E-commerce platforms, customer engagement tools, automated marketing campaigns, notification systems, and real-time business communication workflows.

## 🔗 Essential Links & Resources

| Resource | Description | Link |
|----------|-------------|------|
| 🌐 **Official Website** | Maytapi WhatsApp API Platform | [Visit Site](https://maytapi.com/) |
| 🔐 **Developer Console** | API management and configuration | [Login Portal](https://console.maytapi.com/login) |
| 💰 **Pricing & Plans** | Flexible pricing for all business sizes | [View Pricing](https://maytapi.com/whatsapp-api-pricing) |
| 📖 **API Documentation** | Complete developer documentation | [Read Docs](https://maytapi.com/whatsapp-api-documentation) |

## ⭐ Key Features & Capabilities

### 📤 **Image Messaging Methods**
- ✅ **URL-based Image Sending** - Direct image URLs (JPEG, PNG, GIF, WebP)
- ✅ **Base64 Image Encoding** - Send images from local files or memory buffers
- ✅ **Dynamic Image Captions** - Add rich text descriptions to your images
- ✅ **Bulk Image Broadcasting** - Send to multiple recipients simultaneously

### 🛠️ **Developer-Friendly Features**
- ✅ **Modern JavaScript/ES6+** - Built with latest JavaScript standards
- ✅ **Promise-based API** - Full Promise and async/await support
- ✅ **Comprehensive Error Handling** - Detailed error messages and stack traces
- ✅ **TypeScript Support** - Full TypeScript definitions included

### 🔒 **Security & Performance**
- ✅ **Secure Token Authentication** - Token-based security
- ✅ **HTTPS Encryption** - All communications secured with TLS
- ✅ **Rate Limiting** - Built-in request throttling
- ✅ **Retry Mechanisms** - Automatic retry with exponential backoff

---

## 📦 Installation

Install the required dependencies using npm or yarn:

```
# Using yarn
yarn add axios dotenv
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
