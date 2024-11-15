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

 # 📱 Screens And Video 🎥

### Registration Module

**Registration Screen:** Enables users to sign up with their email, phone number, and password.  
**Phone Verification:** During registration, users verify their phone number using an OTP sent via Firebase.

|  Login Screen | Register Screen | Verify Email |
|---------|---------|---------|
|![login](https://github.com/user-attachments/assets/07f1ae2a-c826-4bc6-8458-35880cd297b0)|![register](https://github.com/user-attachments/assets/90810714-a9a1-4791-b393-e4fd04967efe)|![send_verify](https://github.com/user-attachments/assets/50a057c0-20c8-416f-9928-af675b9bfa93)|


### Home Module

**Home Screen:** Displays a list of products with search and filter options.  
**Real-time Updates:** Products are updated in real-time, eliminating the need for users to refresh the product list.

|  Dashboard View | Search View |Account View |
|---------|---------|---------|
|![home](https://github.com/user-attachments/assets/7b5688f9-0632-49df-8d9f-27df093ebe13)|![search_filter](https://github.com/user-attachments/assets/49529828-e8cd-4658-b757-44cdb5286953)|![account_info](https://github.com/user-attachments/assets/58a76373-a6ea-4717-abe3-86c90ac42d08)|

### Categories Screens For Members & Trainers
The app includes two separate screens:  
1. **Trainer Categories Screen**: Manage trainer categories with options to add, edit, and delete.  
2. **Member Categories Screen**: Manage member categories for organizing memberships, with similar functionality.


| Categories | Edit&Delete Category | 
|---------|---------|
|![categories](https://github.com/user-attachments/assets/e0e439cf-52f4-4ed7-8b14-95cb16896831)|![edit categories](https://github.com/user-attachments/assets/b1112cd9-1614-4e8b-a063-6b0b760a3a58)|




### Members Module

**Members:** Displays a list of Members , Edit Member , Delete Member , Show Member Details.  

| Add Member View | Display Members For Selected Category | Renew Subscribtion |
|---------|---------|---------|
|![add_member](https://github.com/user-attachments/assets/59d97c58-b4a3-42cf-921f-c9ea76afc26d)|![عرض المشتركين](https://github.com/user-attachments/assets/89198af6-76a7-4411-a1b9-5ee2326bef12)|![تجديد اشتراك](https://github.com/user-attachments/assets/f3eb4aa2-aad7-4020-a654-2293f77060da)|



|  Display Member Details | Edit Member | Delete Member |
|---------|---------|---------|
|![display details](https://github.com/user-attachments/assets/b3c9c87d-c755-45e0-97d5-66e40005e3f4)|![edit member](https://github.com/user-attachments/assets/9b89b349-a4fa-42f6-b57b-6cef88c11566)|![delete member](https://github.com/user-attachments/assets/881935f6-6618-4df8-8728-201a20a4ebce)|



### Trainers Module

**Trainers:** Displays a list of Trainers , Edit Trainer , Delete Trainer , Show Trainer Details.  

| Add Trainer View | Add Trainer View 2| Renew Contract |
|---------|---------|---------|
|![image1](https://github.com/user-attachments/assets/5691b5d5-1a2a-4eaa-8ea4-aa7cdbc7918b)|![image2](https://github.com/user-attachments/assets/e281cb89-00d5-4e72-85f6-63cf7f9d2f27)|![image2 (2)](https://github.com/user-attachments/assets/53a748ff-7860-48ff-afa2-d2595148c50a)|


### **Stock Screen**

Manage your inventory effortlessly with the ability to:  
1. **Add Products**: Add new items to the inventory.  
2. **Edit Products**: Update product details like name, price, or quantity.  
3. **Delete Products**: Remove products that are no longer in stock.  

All changes in the inventory automatically reflect in the **Sales Screen**, ensuring accurate stock tracking.

| Show Stock | Add Product | Edit Product |
|---------|---------|---------|
|![show_stock](https://github.com/user-attachments/assets/70864415-8139-4325-80a0-6e61da10a39a)|![add_product](https://github.com/user-attachments/assets/0476f008-0905-4f43-85a2-157e2a5b33f5)|![edit_product](https://github.com/user-attachments/assets/d68c04a8-22de-4bb8-9e1b-86448034f7e2)|


### **Sales Screen**

Track and manage sales with these features:  
1. **Sell Products**: Sell products and **automatically reduce stock** in the inventory.  
2. **View Sold Products**: Display a list of all sold items with their details.  
3. **Delete Sales Records**: Remove any sales entry if needed.  
4. **Filter by Date**: Choose a specific **month and year** to view products sold during that period.  

|  Sell Product | Show Products| 
|---------|---------|
|![sell_product](https://github.com/user-attachments/assets/019b3fc8-003b-4ea7-937a-b0730619a714)|![show_delete_selled_products](https://github.com/user-attachments/assets/c0326823-3f22-478b-a2cb-ae36211fb379)


































|  Verify Email | Reset Password | 
|---------|---------|
|![reset_password_email](https://github.com/user-attachments/assets/f9899537-d1d1-4d60-ae2b-2a0b72fd8d68)|![email_verification](https://github.com/user-attachments/assets/d3526ee7-5f6d-4275-86b5-76d4fd613c41)|


|  App Icon | Splash Screen |
|---------|---------|
| ![app_icon](https://github.com/user-attachments/assets/675e23a1-348f-4ada-99f2-c15679528e9e)| ![splash](https://github.com/user-attachments/assets/017d74ad-4f02-4000-8361-1557afbb132b)|

---






### Payment Stripe

|  Product Details Screen | Saved Card | Add Card View |
|---------|---------|---------|
| ![product_details](https://github.com/AhmedBelal31/Footwear-Store-Client/assets/131663660/5bc18b2c-2ee0-4c22-9d84-4b752a4bb424)|![save_card](https://github.com/AhmedBelal31/Footwear-Store-Client/assets/131663660/f0c27ff2-d4ac-4cb2-9a83-fc0462ac75bc)|![buy_product](https://github.com/AhmedBelal31/Footwear-Store-Client/assets/131663660/1b894921-efea-4ea8-9f15-218d6fed30ff)|

---

