🌱 EcoRetail - Sustainable Retail Platform
A full-stack web application built for the Walmart Sparkathon Hackathon under the theme:
“Retail with Purpose: Building a Sustainable and Responsible Future.”

🎯 Project Overview
EcoRetail empowers retailers to take the lead in sustainability by offering innovative tools and features:

🌍 Sustainable Sourcing Dashboard: Track suppliers and calculate sustainability scores

🚚 Green Logistics Tracker: Visualize CO₂ emissions saved through eco-friendly transport

🤖 AI-powered Waste Reduction: Personalized suggestions to reduce operational waste

🔄 Circular Economy Marketplace: Connect businesses to exchange reusable materials

🚀 Key Features
🔹 Frontend (React + Tailwind CSS)
Responsive and eco-conscious UI design

Real-time dashboards with interactive charts

Sustainability metrics and KPIs at a glance

Seamless user experience optimized for all devices

🔹 Backend (Node.js + Express + MongoDB)
RESTful APIs with CRUD operations

MongoDB database with well-defined schemas

Modular and scalable backend architecture

Basic mock authentication for role-based access

## 📁 Project Structure

```
ecoretail/
├── frontend/          # React application
├── backend/           # Node.js/Express server
├── README.md         # This file
└── .env.example      # Environment variables template
```

## 🛠️ Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### 1. Clone and Install Dependencies

```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 2. Environment Setup

```bash
# Copy environment template
cp .env.example .env

# Edit .env file with your MongoDB connection string
# MONGODB_URI=mongodb://localhost:27017/ecoretail
# or for Atlas: MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/ecoretail
```

### 3. Start the Application

```bash
# Terminal 1: Start backend server
cd backend
npm start

# Terminal 2: Start frontend development server
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 🔧 Available Scripts

### Backend
- `npm start` - Start production server
- `npm run dev` - Start development server with nodemon
- `npm test` - Run tests

### Frontend
- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run tests

## 📊 Database Schemas

### Users
- Authentication data
- Role-based access (retailer, admin)

### Suppliers
- Company information
- Sustainability metrics
- Certification data

### Logistics
- Transport routes
- Emissions data
- Green alternatives

### Marketplace
- Material listings
- Reuse opportunities
- Transaction tracking

## 🎨 Design Features

- **Eco-friendly Color Palette**: Greens, earth tones, and clean whites
- **Responsive Design**: Works on all device sizes
- **Data Visualizations**: Charts, progress bars, and metrics
- **Modern UI**: Clean, intuitive interface with Tailwind CSS

## 🔮 Future Enhancements

- Real-time data integration with external APIs
- Advanced AI/ML for waste reduction suggestions
- Blockchain for supply chain transparency
- Mobile application
- Advanced analytics and reporting

## 🚀 Deployment Options

### Frontend
- Vercel (recommended)
- Netlify
- AWS S3 + CloudFront

### Backend
- Heroku
- AWS EC2
- Google Cloud Platform
- DigitalOcean

### Database
- MongoDB Atlas (recommended)
- AWS DocumentDB
- Self-hosted MongoDB

## 🤝 Contributing

This project was built for the Walmart Sparkathon hackathon. For questions or contributions, please refer to the project documentation.

## 📄 License

This project is created for educational and hackathon purposes.

---

**Built with ❤️ for a sustainable future** 🌱 # ecoretail
#   e c o r e t a i l 
 
 
