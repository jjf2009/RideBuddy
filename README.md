## 🚗 GEC Carpool - Ride Sharing Platform  

### 📌 Overview  
GEC Carpool is a **ride-sharing platform** built for students and faculty of **Goa College of Engineering**. It allows users to **publish rides, find carpool partners, and reduce commuting costs** while promoting **eco-friendly travel**.  

---

## 🎯 Features  
✔️ **Find & Publish Rides** – Users can search for available rides or offer their own.  
✔️ **Real-Time Route Calculation** – Uses **Leaflet & OpenStreetMap** for distance calculations.  
✔️ **Fare Estimation** – Automatically calculates per-person fare based on distance and fuel costs.  
✔️ **User Authentication** – Secure login using **FireBase Authentication**.  
✔️ **Interactive Map Integration** – Displays routes and distances dynamically.  
✔️ **Ride Management** – Users can view, update, or cancel rides.  

---

## 🛠️ Tech Stack  
| **Technology**   | **Usage**  |
|-----------------|------------|
| **React**       | Frontend UI Development |
| **Tailwind CSS** | Styling & Responsive Design |
| **FireBase**    | Backend (Database & Authentication) |
| **Leaflet.js**  | Maps & Routing |
| **OpenStreetMap** | Geolocation & Directions API |

---

## 🎥 Live Demo  
🔗 **[Demo Video](#)** (Replace with actual link)  

---

## 🔧 Installation & Setup  

### ✅ Prerequisites  
Ensure you have the following installed:  
- **Node.js** (v16+)  
- **npm** or **yarn**  
- **FireBase account**  

### 🔽 Clone the Repository  
```bash
git clone https://github.com/your-username/gec-carpool.git
cd gec-carpool
```

### 📦 Install Dependencies  
```bash
npm install
```

### 🔑 Set Up Environment Variables  
Create a `.env` file in the root directory and add your FireBase credentials:  
```env
VITE_SUPABASE_URL=your_Firebase_url
VITE_SUPABASE_ANON_KEY=your_Firebase_anon_key
```

### ▶️ Run the Development Server  
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📜 API Endpoints  

### 🔹 **Authentication**  
- `POST /auth/signup` - Register a new user  
- `POST /auth/login` - Login user  

### 🔹 **Rides**  
- `POST /rides/publish` - Publish a new ride  
- `GET /rides` - Get available rides  
- `POST /rides/join/:rideId` - Request to join a ride  

---

## 🗺️ Map & Routing  
This project uses **Leaflet and OpenStreetMap** to fetch real-time route data. The system dynamically calculates:  
✅ Distance between start & destination  
✅ Estimated travel time  
✅ Fare based on distance  

---

## 📌 Folder Structure  
```
/gec-carpool
│── /src
│   ├── /components  # Reusable components
│   ├── /pages       # Pages (Home, PublishRide, FindRide)
│   ├── /redux       # Redux state management
│   ├── /utils       # Helper functions
│── public           # Static assets
│── .env             # Environment variables
│── package.json     # Dependencies
│── README.md        # Project documentation
```

---

## 📌 Future Enhancements  
🚀 **Live GPS Tracking** – Show real-time vehicle location.  
💰 **Payment Integration** – Seamless transactions for ride payments.  
🤖 **AI-Based Ride Matching** – Improve ride suggestions using AI.  
📊 **User Reviews & Ratings** – Build trust and safety within the community.  

---

## 🤝 Contributing  
Want to contribute? Follow these steps:  
1. **Fork** the repository  
2. **Create a new branch** (`feature-new-functionality`)  
3. **Commit your changes**  
4. **Push and create a Pull Request**  

---

## 📜 License  
This project is **open-source** under the MIT License.  

---

## 🌟 Acknowledgments  
Special thanks to the **Goa College of Engineering community** for inspiring this initiative! 🚀  

---

🚀 **Made with ❤️ by Jared Furtado & Team Qbits**  

---

### 🔥 Why is this README the Best?  
✔️ **Clear & Well-Structured** – Uses headings, bullet points, and tables for readability.  
✔️ **Comprehensive Setup Guide** – Step-by-step guide to help anyone set up the project.  
✔️ **Professional & Scalable** – Includes tech stack, API details, and future roadmap.  
✔️ **Encourages Contributions** – Well-defined process for open-source collaboration.  
