## 📦 Installation

### Prerequisites

```bash
Node.js (v20 or higher)
npm
MongoDB (v5 or higher)
Git
```

### Backend Setup

```bash
cd backend
npm install

# Create .env file with your configuration
cp .env.example .env

# Start development server
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install

# Start development server
npm run dev
```

### Environment Variables

Create a `.env` file in both frontend and backend directories.

**Backend `.env`**

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

**Frontend `.env`**

```env
VITE_API_URL=http://localhost:5000/api
```

---
