# Ketlo Banking Application

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=white)

---

A **full-stack payment app** integrated with Razorpay for secure, real-time transactions. Features include payment processing, transaction logs, webhook handling, and a responsive UI. Ideal for e-commerce, SaaS, and fintech platforms needing a reliable and scalable payment solution.

---

## 🚀 Features

- **Secure Payment Processing** with Razorpay
- **Transaction Logs** for complete payment history
- **Webhook Handling** for real-time updates
- **Responsive UI** with TailwindCSS & Next.js
- **JWT Authentication** for secure sessions
- **Express Validator** for robust input validation
- **Scalable Architecture** with Node.js, Express, MongoDB, and Mongoose

---

## 🛠️ Tech Stack

| Frontend         | Backend         | Database    | Payment Gateway | Auth      | Validation        | Styling      |
|------------------|----------------|-------------|-----------------|-----------|-------------------|--------------|
| Next.js          | Node.js        | MongoDB     | Razorpay        | JWT       | express-validator | TailwindCSS  |
| React            | Express.js     | Mongoose    |                 |           |                   |              |

---

## 📦 Installation

1. **Clone the Repository**
 ```bash
 git clone https://github.com/techySPHINX/FundCraft
 cd FundCraft
 ```

2. **Install Dependencies**

 - **Backend**
   ```bash
   cd backend
   npm install
   ```

 - **Frontend**
   ```bash
   cd ../frontend
   npm install
   ```


3. **Set Up Environment Variables**

- **Frontend `.env`**
  ```
  NEXT_PUBLIC_BASE_URI=http://localhost:1234/api/v1
  NEXT_PUBLIC_RAZORPAY_KEY_ID=<razorpay_key>
  ```

- **Backend `.env`**
  ```
  MONGO_URI=<mongodb URI>
  PORT=1234
  RAZORPAY_KEY_ID=<razorpay_key>
  RAZORPAY_KEY_SCREATE=<razorpay_screate>
  FRONTEND_URI=http://localhost:3000
  ```

4. **Run the Application**

- **Start Backend**
 ```bash
 cd backend
 npm run dev
 ```

- **Start Frontend**
 ```bash
 cd ../frontend
 npm run dev
 ```



---

## 📝 Usage

- Visit `http://localhost:3000`
- Register or log in
- Initiate payments, view transaction logs, and get real-time updates

---

## 💡 Why FundCraft?

- **Modern Tech Stack:** Latest technologies for performance & scalability
- **Security First:** End-to-end encryption, secure payment flows
- **Developer Friendly:** Clean, modular codebase, easy documentation

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or new features.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐️ Show Your Support

If you like this project, please give it a ⭐️ on GitHub and share it with others!

