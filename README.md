# Lymelyt Admin Panel

## 🌟 Project Background
Lymelyt is a dynamic platform designed to connect talented artists with audiences and clients seeking unique performers. Supporting five key genres—Dancer, Musician, Vocalist, Comedian, and Performer—the app enables artists to showcase their skills, from hip-hop dance and jazz vocals to stand-up comedy and theatrical performances.

The platform simplifies talent discovery for event organizers and entertainment enthusiasts, offering an intuitive interface that empowers artists to reach broader audiences.

### **Admin Panel**
This repository contains the **Admin Panel** for Lymelyt, designed to manage user activity, content moderation, payments, support center and overall platform administration.

---

## 📦  Project Architecture
This repository follows a well-structured architecture to ensure scalability, maintainability, and clarity in the codebase
```
📂 src
├── 📂 assets                # Static assets such as fonts, images, and styles
│   ├── 📂 fonts             # Custom fonts used in the application
│   ├── 📂 images            # Image assets categorized by features
│   └── 📂 styles            # Global styles, theme files, and CSS/SCSS files
│
├── 📂 components            # Reusable UI components shared across the application
│   ├── 📂 dashboard-header     # Header section for the dashboard
│   ├── 📂 dashboard-footer     # footer section for the dashboard
│   ├── 📂 sidebar              # Sidebar navigation components
│   ├── 📂 popup                # Pop-up modals and overlays
│   ├── 📂 ui                   # Common UI elements like buttons, cards, etc.
│   ├── 📂 client-testimonials  # displaying client reviews component
│   └── …                      # More components
│
├── 📂 constants             # Constant values,configuration settings
│
├── 📂 features              # Feature-specific modules with their own state and components
│   ├── 📂 chat              # Chat feature implementation
│   ├── 📂 comments-table    # Comment management table
│   ├── 📂 support-center    # Support center-related features
│   └── …                    # More feature-based implementations
│
├── 📂 hooks                 # Custom React hooks for reusable logic
│
├── 📂 layouts               # Page layout components (e.g., dashboard layout, auth layout)
├   ├── 📂 public-layout    
│   ├── 📂 private-layout    
│
├── 📂 pages                 # Application pages
│   ├── 📂 auth              # Authentication pages (Login, Signup, Forgot Password Reset Password)
│   ├──├── 📂 login
│   ├──├── 📂 signup
│   ├──├── 📂 forget
│   ├──├── 📂 reset
│   ├── 📂 dashboard         # Main dashboard page
│   ├── 📂 error             # Error pages (404, Maintenance)
│   ├── 📂 user-management   # User management pages
│   └── …                    # More pages 
│
├── 📂 routes                # Frontend Routes 
├── ├── 📂 private           
├── ├── 📂 public 
├── 📂 services              # API interaction and business logic
│   ├── 📂 authentication    # API interactions for authentication
│   ├── 📂 socket            # WebSocket connection handlers
│   ├── 📂 user-management   # API interactions for user data management
│   └── …                    # More API services
│
├── 📂 store                 # Root store configuration and global state management
│
├── 📂 utils                 # Utility functions and helper methods
│   ├── 📂 interfaces         # TypeScript interfaces and types
│   ├── 📂 enums              # TypeScript enums
│   └── 📂 validations        # Schema definitions for form validation and API responses
```

---

## 🛠️ Technologies Used

- **TypeScript** – Core Programming
- **React 19** – Core framework
- **Vite** – Development environment
- **Redux Toolkit & Redux Persist** – Global State management
- **Redux Saga** – Side effect management
- **React Router** – Routing
- **Axios** – API calls
- **Shadcn UI** – UI components
- **React Hook Form** – Form handling
- **Tailwind CSS** – Styling
- **Socket.io Client** – Real-time communication
- **Zod** – Schema validation
- **ESLint** – Linting & code quality
- **React Infinite Scroll** – Infinite scrolling

---
## 🚀 Live Demo
[Live Link](https://yellow-mud-052b7890f.4.azurestaticapps.net/)

---

## 📸 Screenshots
![Login](https://raw.githubusercontent.com/fleekbiz/lymelyt-demo/main/assets/login.png)
![User Management Module](https://raw.githubusercontent.com/fleekbiz/lymelyt-demo/main/assets/user-managment.png)
![Support Center Module](https://raw.githubusercontent.com/fleekbiz/lymelyt-demo/main/assets/support-center.png)
![Notification Module](https://raw.githubusercontent.com/fleekbiz/lymelyt-demo/main/assets/notification.png)






## 🌍 Connect with Us
📧 Email: mail@fleekbiz.com
🌎 Website: [www.fleekbiz.com](https://fleekbiz.com) 
📞 Phone: (877) 560-5556

