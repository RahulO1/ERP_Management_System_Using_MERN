# ERP Management System (MERN Stack)

A full-featured **ERP (Enterprise Resource Planning) web application** built with the **MERN stack** (MongoDB, Express, React, Node.js).  
It helps mid-sized companies manage core business operations like **Products, Customers, Suppliers, Sales Orders, Purchase Orders, Invoices, and Inventory** with role-based access and secure authentication.

---

## 🚀 Features
- **User Authentication & Roles**: JWT-based login, role-based access (Admin, Sales, Purchase, Inventory).
- **Product Management**: CRUD operations with search, filter, and pagination.
- **Customer & Supplier Management**: Directory with add/edit/delete.
- **Sales & Purchase Orders**: End-to-end workflow tracking.
- **Inventory & GRN**: Goods Receipt Notes linked to purchase orders.
- **Invoice Generation**: Export invoices to PDF (jsPDF).
- **Dashboard & Reports**: Charts and metrics with Chart.js / Recharts.
- **Responsive UI**: Works on desktop, tablet, and mobile.

---

## 🛠️ Tech Stack
**Frontend:**
- React.js, React Router v6  
- Redux Toolkit / Context API  
- Axios  
- Material-UI / Bootstrap  

**Backend:**
- Node.js, Express.js  
- JWT + bcrypt for authentication  
- Mongoose (MongoDB ODM)  

**Database:**
- MongoDB (Atlas / Local)  

**Enhancements:**
- react-toastify (alerts)  
- Formik + Yup / React Hook Form (validation)  
- Chart.js / Recharts (analytics)  
- Swagger / Postman (API docs)  
- Jest + React Testing Library (testing)  

Deployment: **Vercel (Frontend)** + **Render/Heroku (Backend)**  

---

## 📂 Project Modules
- **Users** → Register, Login, Role-based access (Admin, Sales, Purchase, etc.)
- **Products** → CRUD operations, stock management, reorder levels
- **Customers & Suppliers** → Contact and record management
- **Sales Orders** → Create, update, and track orders
- **Purchase Orders** → Supplier-linked purchase workflows
- **GRN (Goods Receipt Notes)** → Inventory updates linked to purchase orders
- **Invoices** → Generate, download, and share PDF invoices
- **Dashboard** → Metrics, reports, and analytics

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<RahulO1>/ERP_Management_System_Using_MERN.git
