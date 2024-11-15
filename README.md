# KINGS-GYM 🏋️
# **Gym Management App** 🏋️

## **About the App**

This application is a **real-life project** developed specifically for a gym owner to manage all aspects of their gym business efficiently. The app is designed to handle memberships, trainers, sales, inventory, and finances, providing a complete solution tailored to the needs of a gym. 

It also includes a separate, simplified version for trainers to ensure streamlined operations while maintaining data security.

---

## **Features**

### **1. Gym Owner App**
The gym owner's app includes full control over all operations:

#### **Membership Management**
- Add, edit, and delete member profiles.
- Track membership durations, renewal dates, and single-session attendees.
- Assign categories to members (e.g., Gym + Cardio, Boxing).

#### **Trainer Management**
- Add trainers with details like photo, ID card, salary, and assigned categories.
- Manage trainer contracts with durations (3, 6, or 12 months).
- Track trainer salaries and their due dates.

#### **Inventory Management**
- Add, edit, or delete products from the inventory.
- Real-time stock updates: Sales reduce inventory levels automatically.
- Track all sold products with filtering options by year and month.

#### **Sales Management**
- Record product sales and associate them with inventory.
- View detailed sales reports filtered by year and month.

#### **Custom Categories**
- Create, edit, and delete categories for members and trainers.
- Newly added categories appear in member and trainer forms for easy assignment.

#### **Financial Management**
- Track all revenues from memberships, single-session attendees, and product sales.
- Manage expenses like trainer salaries, rent, maintenance, and other monthly costs.
- View monthly breakdowns of revenues vs. expenses with detailed reports.
- Interactive charts for visual financial insights.

#### **Search and Filters**
- Search for members and trainers with advanced filters (e.g., member vs. trainer, male vs. female).

#### **Authentication System**
- Secure login with email verification.
- Reset password functionality.
- Role-based access control to differentiate between gym owners and trainers.

#### **Additional Features**
- **Splash Screen**: Engaging splash screen for initial app loading.
- **Dark Theme**: Default dark mode for the entire app.

---

### **2. Trainer App**
The trainer app provides limited features for streamlined use:
- **Add Members**: Simple form for adding new members to the system.
- **Renew Subscriptions**: Update subscription durations for existing members.
- **Sell Products**: Record product sales with automatic inventory adjustments.

---

## **Technical Details**

- **Frontend**: Built using Flutter for a smooth and responsive UI.
- **Backend**: Firebase for secure and real-time data handling:
  - **Firestore**: Database to store members, trainers, sales, and financial data.
  - **Firebase Storage**: For storing trainer/member images and ID cards.
  - **Firebase Authentication**: Handles login, email verification, and password reset.
- **State Management**: BLoC/Cubit for predictable and maintainable state handling.

---

## **App Overview**

### **Gym Owner Version**
- Designed to cover every aspect of gym management.
- Provides full access to memberships, sales, inventory, and financial details.
- Exclusive features ensure the owner can monitor and control all aspects of the business.

### **Trainer Version**
- Focused on essential tasks:
  - Adding new members.
  - Renewing memberships.
  - Selling products.
- Ensures privacy and security by limiting access to sensitive data.

---

## **Screens and Functionalities**

### **1. Members**
- Add new members with subscription details.
- Track subscription durations and renewal dates.
- Filter by category, gender, or membership type.

### **2. Trainers**
- Add trainers with details like:
  - Profile photo.
  - National ID card.
  - Contract duration and salary.
  - Assigned categories.
- Manage trainer contracts and salaries with detailed reports.

### **3. Inventory**
- Add, edit, and delete products.
- Automatically reduce stock levels when products are sold.
- Track all sold items with filters by date (year and month).

### **4. Sales**
- Record sales and link them to inventory.
- View detailed sales reports with filtering options.
- Understand monthly sales trends.

### **5. Financial Overview**
- Track revenues from memberships and product sales.
- Track expenses like trainer salaries and monthly costs.
- Detailed monthly reports with revenue vs. expense breakdowns.
- Interactive charts for financial visualization.

### **6. Categories**
- Add, edit, and delete categories for trainers and members.
- Use these categories across the app to organize trainers and members effectively.

### **7. Search and Filters**
- Advanced search for members and trainers.
- Filter by type (member or trainer), gender, and more.

---

## **How Data is Managed**

- **Firestore**: All members, trainers, inventory, and sales data is stored securely.
- **Firebase Storage**: Images (e.g., trainer/member photos and ID cards) are stored efficiently.
- **Data Synchronization**: All changes reflect in real-time across connected features (e.g., sales affect inventory stock).

---

## **Notes**
- The gym owner app includes complete control of all functionalities.
- The trainer app has limited access to specific features to maintain privacy and security.

---

## **Future Enhancements**
- Add notifications for subscription and salary due dates.
- Enable report export (PDF or Excel) for financial summaries.
- Implement support for multiple gym branches.
