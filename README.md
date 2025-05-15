# ParkEase-v2 🚗

**ParkEase** is a smart parking management web application that helps users easily find and book parking slots at nearby locations.  
It minimizes the hassle of searching for parking in busy areas by showing real-time availability of slots and parking locations.

---

## 🌟 Features

- 🔍 View nearby parking locations on a map  
- 📊 Check the number of available slots in real-time  
- 📝 Book a parking slot in advance  
- ⏰ Time-based reservations to avoid overbooking  
- 🧾 Booking history and receipt generation  

---

## 📦 Tech Stack

- **Frontend**: React.js / TailwindCSS / JavaScript / TypeScript  
- **Backend**: Node.js / Express.js  
- **Database**: MySQL  
- **Authentication**: JWT (JSON Web Tokens)  
- **Maps API**: Geolocation API  

---

## ✅ Prerequisites

Ensure the following are installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)
- [MySQL](https://www.mysql.com/)

---

## 🚀 Installation

Clone the repository and install project dependencies:

```bash
# Clone this repository
git clone https://github.com/your-username/park-ease.git

# Navigate to the project directory
cd park-ease

# Install all dependencies
npm install
```

---

## 🛠️ Environment Setup

Before running the application, configure your environment variables:

1. Open the `.env` file located in the project root.
2. Set the following variables:

```env
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=5000
JWT_SECRET=your_jwt_secret_key
```

> ⚠️ Replace the values with your local MySQL credentials and desired JWT secret key.

---

## 🗄️ Database Setup

Create the database using MySQL Workbench or terminal:

```sql
CREATE DATABASE your_database_name;
```

Make sure the name matches the `DB_NAME` value in your `.env` file.

Then, run the following command to set up tables and initial data:

```bash
npm run setup-db
```

---

## ▶️ Running the Application

To start the project:

### 1. Run the frontend in one terminal:

```bash
npm run dev
```

### 2. Run the backend in a separate terminal:

```bash
npm run server
```

---

Happy Parking! 🅿️✨
