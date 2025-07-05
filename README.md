# Bus-Ticket-Booking
# 🚌 Bus Ticket Booking System

<div align="center">
  <img src="https://img.shields.io/badge/MERN-Stack-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="MERN Stack">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" alt="Cloudinary">
</div>

<div align="center">
  <h3>🎯 Your Ultimate Bus Ticket Booking Solution</h3>
  <p><em>A modern, full-stack web application for seamless bus ticket booking experience</em></p>
</div>

---

## 🌟 Features

### 🎨 **User Experience**
- **🏠 Modern Landing Page** - Beautiful, responsive design with Tailwind CSS
- **🔍 Smart Search** - Find buses by route, date, and preferences
- **💺 Interactive Seat Selection** - Visual seat map with real-time availability
- **💳 Secure Payment Integration** - Multiple payment options
- **📱 Responsive Design** - Optimized for all devices

### 🛠️ **Technical Features**
- **🔐 JWT Authentication** - Secure user authentication and authorization
- **☁️ Cloud Storage** - Cloudinary integration for image management
- **📊 Real-time Updates** - Live bus tracking and seat availability
- **📧 Email Notifications** - Automated booking confirmations
- **📈 Admin Dashboard** - Complete bus and booking management

### 🚀 **Performance**
- **⚡ Fast Loading** - Optimized React components
- **🔄 Real-time Data** - Live updates using WebSocket
- **📦 Efficient State Management** - Redux for state management
- **🎯 SEO Optimized** - Better search engine visibility

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="center" width="200px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="60" height="60" alt="MongoDB">
      <br><strong>MongoDB</strong>
      <br><em>Database</em>
    </td>
    <td align="center" width="200px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="60" height="60" alt="Express.js">
      <br><strong>Express.js</strong>
      <br><em>Backend Framework</em>
    </td>
    <td align="center" width="200px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="60" height="60" alt="React">
      <br><strong>React</strong>
      <br><em>Frontend Library</em>
    </td>
    <td align="center" width="200px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="60" height="60" alt="Node.js">
      <br><strong>Node.js</strong>
      <br><em>Runtime Environment</em>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg" width="60" height="60" alt="Tailwind CSS">
      <br><strong>Tailwind CSS</strong>
      <br><em>Styling Framework</em>
    </td>
    <td align="center">
      <img src="https://res.cloudinary.com/demo/image/upload/v1/logo" width="60" height="60" alt="Cloudinary">
      <br><strong>Cloudinary</strong>
      <br><em>Cloud Storage</em>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" width="60" height="60" alt="Redux">
      <br><strong>Redux</strong>
      <br><em>State Management</em>
    </td>
    <td align="center">
      <img src="https://jwt.io/img/pic_logo.svg" width="60" height="60" alt="JWT">
      <br><strong>JWT</strong>
      <br><em>Authentication</em>
    </td>
  </tr>
</table>

---

## 🚀 Quick Start

### 📋 Prerequisites

Make sure you have the following installed:

```bash
🔹 Node.js (v14 or higher)
🔹 MongoDB (v4.4 or higher)
🔹 npm or yarn
🔹 Git
```

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bus-ticket-booking.git
   cd bus-ticket-booking
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Setup**
   
   Create `.env` files in both backend and frontend directories:
   
   **Backend `.env`:**
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/bus-booking
   JWT_SECRET=your-super-secret-jwt-key
   CLOUDINARY_NAME=your-cloudinary-name
   CLOUDINARY_API_KEY=your-api-key
   CLOUDINARY_API_SECRET=your-api-secret
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-email-password
   ```
   
   **Frontend `.env`:**
   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   REACT_APP_CLOUDINARY_URL=your-cloudinary-url
   ```

5. **Start the Application**
   
   **Backend:**
   ```bash
   cd backend
   npm run dev
   ```
   
   **Frontend:**
   ```bash
   cd frontend
   npm start
   ```

🎉 **That's it!** Your application should now be running at `http://localhost:3000`

---

## 📁 Project Structure

```
bus-ticket-booking/
├── 📁 backend/
│   ├── 📁 config/
│   │   ├── 📄 database.js
│   │   └── 📄 cloudinary.js
│   ├── 📁 controllers/
│   │   ├── 📄 authController.js
│   │   ├── 📄 busController.js
│   │   └── 📄 bookingController.js
│   ├── 📁 middleware/
│   │   ├── 📄 auth.js
│   │   └── 📄 upload.js
│   ├── 📁 models/
│   │   ├── 📄 User.js
│   │   ├── 📄 Bus.js
│   │   └── 📄 Booking.js
│   ├── 📁 routes/
│   │   ├── 📄 auth.js
│   │   ├── 📄 buses.js
│   │   └── 📄 bookings.js
│   ├── 📁 utils/
│   │   ├── 📄 emailService.js
│   │   └── 📄 helpers.js
│   └── 📄 server.js
├── 📁 frontend/
│   ├── 📁 src/
│   │   ├── 📁 components/
│   │   │   ├── 📄 Header.jsx
│   │   │   ├── 📄 SearchForm.jsx
│   │   │   ├── 📄 BusList.jsx
│   │   │   └── 📄 SeatMap.jsx
│   │   ├── 📁 pages/
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 SearchResults.jsx
│   │   │   ├── 📄 BookingPage.jsx
│   │   │   └── 📄 Dashboard.jsx
│   │   ├── 📁 redux/
│   │   │   ├── 📄 store.js
│   │   │   └── 📄 slices/
│   │   ├── 📁 utils/
│   │   │   ├── 📄 api.js
│   │   │   └── 📄 helpers.js
│   │   └── 📄 App.js
│   ├── 📄 package.json
│   └── 📄 tailwind.config.js
├── 📄 README.md
└── 📄 .gitignore
```

---

## 🎨 Screenshots

<div align="center">
  
### 🏠 Home Page
*Beautiful landing page with search functionality*

### 🔍 Search Results
*Interactive bus listing with filters*

### 💺 Seat Selection
*Visual seat map with real-time availability*

### 💳 Payment Page
*Secure payment integration*

### 📊 Admin Dashboard
*Complete management interface*

</div>

---

## 🌈 Color Palette

Our application uses a vibrant and modern color scheme:

<div align="center">
  <table>
    <tr>
      <td align="center" bgcolor="#3B82F6" width="100px" height="60px">
        <strong style="color: white;">Primary</strong><br>
        <code style="color: white;">#3B82F6</code>
      </td>
      <td align="center" bgcolor="#10B981" width="100px" height="60px">
        <strong style="color: white;">Success</strong><br>
        <code style="color: white;">#10B981</code>
      </td>
      <td align="center" bgcolor="#F59E0B" width="100px" height="60px">
        <strong style="color: white;">Warning</strong><br>
        <code style="color: white;">#F59E0B</code>
      </td>
      <td align="center" bgcolor="#EF4444" width="100px" height="60px">
        <strong style="color: white;">Danger</strong><br>
        <code style="color: white;">#EF4444</code>
      </td>
    </tr>
    <tr>
      <td align="center" bgcolor="#8B5CF6" width="100px" height="60px">
        <strong style="color: white;">Purple</strong><br>
        <code style="color: white;">#8B5CF6</code>
      </td>
      <td align="center" bgcolor="#06B6D4" width="100px" height="60px">
        <strong style="color: white;">Cyan</strong><br>
        <code style="color: white;">#06B6D4</code>
      </td>
      <td align="center" bgcolor="#84CC16" width="100px" height="60px">
        <strong style="color: white;">Lime</strong><br>
        <code style="color: white;">#84CC16</code>
      </td>
      <td align="center" bgcolor="#F97316" width="100px" height="60px">
        <strong style="color: white;">Orange</strong><br>
        <code style="color: white;">#F97316</code>
      </td>
    </tr>
  </table>
</div>

---

## 🔗 API Endpoints

### 🔐 Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `GET /api/auth/profile` - Get user profile

### 🚌 Buses
- `GET /api/buses` - Get all buses
- `GET /api/buses/search` - Search buses by route and date
- `POST /api/buses` - Add new bus (Admin only)
- `PUT /api/buses/:id` - Update bus (Admin only)
- `DELETE /api/buses/:id` - Delete bus (Admin only)

### 🎫 Bookings
- `POST /api/bookings` - Create new booking
- `GET /api/bookings` - Get user bookings
- `GET /api/bookings/:id` - Get specific booking
- `PUT /api/bookings/:id` - Update booking status
- `DELETE /api/bookings/:id` - Cancel booking

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **🍴 Fork the repository**
2. **🔧 Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **💾 Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **🚀 Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **🔄 Open a Pull Request**

### 📝 Contribution Guidelines

- Follow the existing code style and conventions
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

---

## 🐛 Known Issues

- **Mobile responsiveness** - Some pages need optimization for smaller screens
- **Real-time updates** - WebSocket connection occasionally drops
- **Payment gateway** - Testing mode limitations

## 📈 Future Enhancements

- **🎯 Advanced Filtering** - More search and filter options
- **📱 Mobile App** - React Native mobile application
- **🌐 Multi-language Support** - Internationalization
- **🔔 Push Notifications** - Real-time booking updates
- **📊 Analytics Dashboard** - Advanced reporting features
- **🤖 AI Chatbot** - Customer support automation

---


---

## 📞 Support

Having trouble? We're here to help!

- **📧 Email**: support@busticketbooking.com
- **💬 Discord**: [Join our community](https://discord.gg/busticketbooking)
- **📖 Documentation**: [Full Documentation](https://docs.busticketbooking.com)
- **🐛 Issues**: [Report a Bug](https://github.com/yourusername/bus-ticket-booking/issues)

---

## 🙏 Acknowledgments

- **React Team** for the amazing frontend library
- **MongoDB** for the robust database solution
- **Tailwind CSS** for the beautiful styling framework
- **Cloudinary** for seamless image management
- **All Contributors** who helped make this project better

---

<div align="center">
  <h3>⭐ Star this repo if you found it helpful!</h3>
  <p>Made with ❤️ by  <a href="https://github.com/yourusername">Priyam Khan</a></p>
  
  <img src="https://img.shields.io/github/stars/yourusername/bus-ticket-booking?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/yourusername/bus-ticket-booking?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/watchers/yourusername/bus-ticket-booking?style=social" alt="GitHub watchers">
</div>

---

<div align="center">
  <sub>Built with 🚌 for seamless travel experiences</sub>
</div>
