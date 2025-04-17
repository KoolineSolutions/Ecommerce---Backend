
# 🛍️ E-commerce Backend Server

This is the backend for a modern e-commerce web application. It handles user authentication, product management, orders, payments, and more.

> 🔗 This works together with the frontend available in a separate repo. For full functionality, both should be running.

---

## 🚀 How to Run (Beginner Friendly)

### 1. Clone the Repository

```bash
git clone https://github.com/KoolineSolutions/Ecommerce---Backend.git
cd <backend-folder> (Hint: Folder with package.json file)
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Variables Setup

Add the following in config.env file in backend/config:

```env
PORT=4000
DATABASE_URI=mongodb://localhost:27017/EcommerceStore

JWT_SECRET=kooline-solutions@vaji
JW_TOKEN_EXPIRES_TIME=259200

SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
EMAIL_SERVICE=email
EMAIL_SENDER=your_email@gmail.com
EMAIL_APP_PASSWORD=your_email_hashed_password

CLOUDINARY_NAME=your_cloudinary_folder_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

STRIPE_PUBLISHER_KEY=your_stripe_publisher_key
STRIPE_SECRET=your_stripe_secret
```

> ⚠️ Replace placeholders like `your_email@gmail.com`, API keys, and secrets with your actual values.

### 4. Start the Server

```bash
npm start
```

The backend will start on:  
[http://localhost:4000](http://localhost:4000)

---

## 🧠 How It Works

- MongoDB is used to store all data.
- Stripe is integrated for payment processing.
- Cloudinary is used for storing images.
- JWT handles user sessions securely.
- Nodemailer enables email sending features.

---

## ❓Need Help?

Want help with full setup or custom development?

👉 [Get support or request a quote](https://www.kooline.software/contact)

---

Make it yours. Launch your online store with confidence!
