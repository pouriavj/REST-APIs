# REST-APIs

A Node.js project demonstrating all main HTTP methods (**GET**, **POST**, **PUT**, **PATCH**, and **DELETE**) with the [Secrets API](https://secrets-api.appbrewery.com).  
The app uses **Express**, **EJS**, and **Axios** to interact with the API and render responses dynamically.  

This is a full-stack project combining **Back-end + Front-end**, created as part of a web development course.  

---

## 🚀 Features

- Demonstrates complete RESTful API operations  
- Server-side integration using **Axios**  
- Form-based requests for testing API endpoints  
- Dynamic rendering with **EJS** templates  

---
## 🔑 Authentication

This project requires a **Bearer Token** for authorization.  
Replace the value of `yourBearerToken` in `index.js` with your own token:

```js
const yourBearerToken = "your-token-here";
```

---

## 📸 Screenshot

![REST API Screenshot](https://github.com/pouriavj/REST-APIs/blob/main/REST-APIs.jpg?raw=true)  

---

## ⚙️ How to Run

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   node index.js
   ```
3. Open http://localhost:3000 in your browser.
(You can change the port in `index.js` by modifying `const port = 3000;`)

---

## 🛠️ Built With

- [Node.js](https://nodejs.org/)  
- [Express.js](https://expressjs.com/)  
- [EJS](https://ejs.co/) – templating engine  
- [Axios](https://axios-http.com/) – for HTTP requests  
- [Body-parser](https://www.npmjs.com/package/body-parser) – to handle form submissions  
- HTML5 / CSS3  


