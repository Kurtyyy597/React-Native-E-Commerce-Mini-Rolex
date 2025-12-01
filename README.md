 🕒 Rolex E-Commerce (React Native)

A fully interactive mini e-commerce application built in **React Native**, featuring luxury Rolex watches.  
This project showcases UI/UX design, state management, form validation, order calculation logic, modals, and light/dark theme switching.

This is NOT a simple UI — it is a complete purchase simulation with order summary, VAT, vouchers, delivery fee, timestamps, and more.

---

⭐ Features

 🛍️ **Product Catalog**
- 10 Rolex watch models
- Includes name, price, description, and image
- Image updates automatically based on selection
- Highlighted selected card with glow effect

 🌙 **Light / Dark Mode**
- Dynamic theming with full color palette switching
- Changes background, text, cards, and buttons in real-time

 📝 **Smart Form Validation**
Validates:
- Full name (min length)
- Age (numeric only)
- Address (min length)
- Phone number (**Philippine format: 09XXXXXXXXX**)
- Item name, price, quantity
- Automatic error messages per field

 🧮 **Dynamic Price Calculation**
Includes:
- Subtotal (price × quantity)  
- Delivery fee toggle  
- Voucher (10% off)  
- VAT computation (10%)  
- Final Grand Total (formatted)

 ⏳ **Order Processing Simulation**
- 5-second loading animation
- Auto scroll to receipt
- ActivityIndicator with countdown

 🧾 **Order Summary + Receipt**
Displays:
- Watch name + image  
- Customer information  
- Delivery & voucher status  
- VAT breakdown  
- Timestamp  
- Order ID  
- Final total  
- “Buy Again” feature  

 🔔 **Modal Confirmation**
A modal pops up showing:
- Selected watch
- Customer info
- Pricing breakdown
- Confirm order button
- Choose another watch button

📱 **Fully Responsive**
- Optimized for all screen sizes  
- Uses `ScrollView`, `KeyboardAvoidingView`, and `Pressable`  
- Auto scroll to top/bottom when needed

---

 🗂️ **Tech Stack**

- **React Native**
- **TypeScript / JavaScript**
- **Expo**
- **React Native Navigation (ScrollViews & Modals)**
- **Custom Light/Dark Theme System**
- **State Management (useState + useRef)**
