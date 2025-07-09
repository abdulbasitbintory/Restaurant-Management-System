# 🍽️ Restaurant Management System  
*A Java-based desktop application for managing restaurant operations developed during a Programming 1 course*

## 📌 Overview  
This is a **desktop-based restaurant management system** built using Java Swing and file-based storage. Designed for academic requirements, it provides core functionality for managing restaurant operations, including authentication, menu items, orders, staff, and billing. The application features a drag-and-drop UI design created in NetBeans IDE.

---

## 🚀 Key Features  

### 🔐 Authentication Module  
- Hardcoded login credentials (for demonstration purposes)  
- Simple username/password verification  
- Role-based access control (basic implementation)

### 📋 Core Modules  
| Module | Functionality |
|-------|---------------|
| **Item Management** | Add/Edit/Delete menu items with pricing |
| **Order Management** | Create and track customer orders |
| **Labour Management** | Manage staff information |
| **Billing System** | Generate bills and track payments |

### 🛠️ Technical Highlights  
- **File-Based Storage**: Uses `.txt` files for persistent data storage  
- **Swing GUI**: Drag-and-drop interface built with NetBeans Form Editor  
- **Modular Architecture**: Separated logic for different restaurant operations  
- **Validation**: Input validation for critical fields  

---

## 🛠️ Tech Stack  
| Technology | Purpose |  
|----------|---------|  
| **Java 8+** | Core programming language |  
| **Swing** | GUI components and layout |  
| **NetBeans IDE** | Development environment and form design |  
| **File I/O** | Data persistence using text files |  

---

## 📁 Project Structure  
```
Restaurant-Management-System/
├── src/                # Java source files
│   ├── Login.java      # Authentication logic
│   ├── Menu.java       # Item management interface
│   ├── Order.java      # Order creation logic
│   └── ...             # Additional module files
├── data/               # File storage directory
│   ├── users.txt       # User credentials
│   ├── items.txt       # Menu items database
│   └── orders.txt      # Order records
├── README.md           # Project documentation  
└── LICENSE             # MIT License (optional)
```

---

## 📦 Installation & Setup  

### Prerequisites  
- Java Development Kit (JDK 8+)  
- NetBeans IDE (recommended for UI editing)  
- Basic knowledge of Java Swing  

### Steps  
1. **Clone the Repository**  
```bash
git clone https://github.com/abdulbasitbintory/Restaurant-Management-System.git
```

2. **Open in NetBeans**  
- File → Open Project → Select project folder  
- Right-click project → Run  

3. **Manual Execution (Optional)**  
```bash
cd Restaurant-Management-System
javac src/*.java  # Compile all Java files
java src.Login   # Launch application
```

---

## 🔐 Authentication  
**Demo Credentials** (Hardcoded):  
```text
Username: abdul  
Password: abdul
```

⚠️ **Security Note**: This is a demonstration-only authentication system. For production use, implement proper password hashing and database integration.

---

## 📷 Screenshots  

### 1. Menu Interface  
![Menu](https://i.ibb.co/Y7kn3cQ/2-menu.png)

### 2. Order Creation  
![Create Order](https://i.ibb.co/5c5vpwv/3-create-order.png)

### 3. Order Confirmation  
![Order Confirmation](https://i.ibb.co/qJgRYCL/4-order-confirmation.png)

---

## 🧪 How to Use  

1. **Login**  
   - Use demo credentials to access the system  

2. **Navigate Modules**  
   - Use top menu bar to switch between:  
     - Item Management  
     - Order Management  
     - Labour Management  
     - Billing System  

3. **Data Persistence**  
   - All changes are automatically saved to `.txt` files in `/data/`

---

## 🛡️ Security Considerations  
- **File-Based Storage**: Suitable only for academic/demo purposes  
- **Hardcoded Credentials**: Not secure for production environments  
- **No Encryption**: Data is stored in plain text format  

---

## 📈 Future Enhancements  
- [ ] Implement database integration (MySQL/PostgreSQL)  
- [ ] Add password hashing with BCrypt  
- [ ] Include role-based access control (Admin/Staff)  
- [ ] Add reporting functionality (PDF receipts)  
- [ ] Implement inventory management  
- [ ] Add multi-language support  

---

## 💡 Contributing  
Contributions are welcome! Please follow these steps:  
1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Submit a pull request  

---

## 📄 License  
This project is licensed under the [MIT License](LICENSE).  

---

## 📬 Contact  
Abdul Basit Bin Tariq  
📧 Email: abdulbasitnotmain@gmail.com  
🌐 GitHub: [github.com/abdulbasitbintory](https://github.com/abdulbasitbintory)  

---

## 🙌 Acknowledgments  
- NetBeans IDE for GUI development  
- Java Swing documentation  
- University Programming 1 course materials  

---

**🍽️ Streamline Your Restaurant Operations with This Academic Project**
```

---

### ✅ To Use This README:
1. **Replace** all screenshot links with actual file paths if hosting locally.  
2. **Update** contact details and acknowledgments.  
3. **Add** a `LICENSE` file if using MIT license.  
4. **Customize** the "Future Enhancements" section based on your roadmap.  

This README includes:  
- Technical architecture  
- Code examples  
- Installation steps  
- Security notes  
- Contribution guidelines  
- Visual documentation  
- Roadmap for future features  

