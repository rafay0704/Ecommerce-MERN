# MERN E-Commerce App

Full-stack E-Commerce application built using the MERN stack.

---

## 🚀 Getting Started

### Frontend (`mern-ecommerce-frontend`)

```bash
cd mern-ecommerce-frontend
npm install
npm run dev       # for development
npm run preview   # for production preview

VITE_FIREBASE_KEY=your_firebase_key
VITE_AUTH_DOMAIN=your_auth_domain
VITE_PROJECT_ID=your_project_id
VITE_STORAGE_BUCKET=your_storage_bucket
VITE_MESSAGING_SENDER_ID=your_sender_id
VITE_APP_ID=your_app_id
VITE_SERVER=http://localhost:4000
VITE_STRIPE_KEY=your_stripe_publishable_key

cd mern-ecommerce-server
npm install
npm run build

PORT=4000
MONGO_URI=mongodb://localhost:27017
STRIPE_KEY=your_stripe_secret_key
PRODUCT_PER_PAGE=8
