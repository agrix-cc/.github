# AgriX

AgriX is a Progressive Web Application (PWA) designed to minimize post-harvest agricultural wastage in Sri Lanka by streamlining the supply chain. Unlike typical e-commerce platforms, AgriX is a B2B solution that connects farmers, sellers, cold storage providers, and transport services in real-time, enabling efficient coordination of logistics, product listings, and transactions to better match supply with demand.

---

## Table of Contents
- [About](#about)
- [Key Features & Innovations](#key-features--innovations)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributors](#contributors)
- [License](#license)

---

## About
As part of an Agile-driven team project, AgriX reflects a strong understanding of Agile methodologies, real-world problem solving in the agricultural domain, and full-stack development best practices. The platform is built to:
- Minimize post-harvest wastage
- Enable real-time B2B coordination
- Streamline logistics and transactions in agriculture

---

## Key Features & Innovations
- **Route-based rental price calculation using Google Maps API**
- **Real-time chat integration with Socket.IO**
- **Personalized user reports based on sales data**
- **Secure payment gateway using Stripe**
- **JWT-based user authentication**
- **Image storage using AWS S3 Bucket**
- **Automated end-to-end testing using Cypress**
- **Prioritized development using the MoSCoW method for effective task management**

---

## Tech Stack
- **Front-End:** React.js
- **Back-End:** Node.js, Express.js
- **Database:** MySQL
- **Hosting & Storage:** AWS, S3 Bucket
- **APIs:** Google Maps API, Stripe
- **Tools:** Cypress, Socket.IO, JWT

---

## Project Structure
```
/
  agrix-client/   # React frontend (PWA)
  agrix-server/   # Node.js/Express backend
```

---

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- MySQL
- npm

### Setup
1. **Clone the repositories**
   ```bash
   git clone https://github.com/agrix-cc/agrix-client.git
   git clone https://github.com/agrix-cc/agrix-server.git
   ```
2. **Install dependencies**
   ```bash
   cd agrix-client
   npm install

   cd ../agrix-server
   npm install
   ```
3. **Configure environment variables**
   - Copy `.env-copy` in `agrix-server` to `.env` and fill in your database and other secrets.
4. **Run the applications**
   - **Frontend:**
     ```bash
     cd agrix-client
     npm start
     ```
     Runs at [http://localhost:3000](http://localhost:3000)
   - **Backend:**
     ```bash
     cd agrix-server
     npm run devStart
     ```
     Runs at [http://localhost:5050](http://localhost:5050) (or as configured)

---

## Contributors
- [Hannan Munas](https://github.com/HannanLK)
- [Dilanka Yasuru](https://github.com/dilankayasuru)
- [Pamuditha Gangana](https://github.com/PamudithaGa)
- [Kisara Jayathissa](https://github.com/Kisaraj)

---

## License
This project is licensed under the MIT License.
