# 🎬 Movie Ticket Booking System

A console-based C++ application that simulates a movie ticket booking system. It offers a smooth user experience for selecting movies, showtimes, and seat categories, while also handling user registration and payment processing.

---

## 📌 Features

- 🎥 View available movies and their showtimes  
- 🎟️ Book tickets with unique seat numbers  
- 💳 Optional card payment processing (with validation)  
- 🪪  DTCard Registration system with auto-generated card ID  
- 📞 Contact support information  
- 🎨 Colored console UI for better user interaction (uses ANSI escape codes)  

---

## 🛠️ Technologies Used

- **C++** (Standard C++ Libraries)  
- Console color manipulation using ANSI escape codes  
- Random seat assignment using `set`  
- Input validation for contact and payment details  

---

## 🧾 How to Use

### Compile the Program

You can compile the C++ program using `g++`:

```bash
g++ -o MovieBooking MovieTicketBooking.cpp
```
---

## 🖥️ Features Walkthrough

### 📽️ Movie Selection

Choose from a list of current movies:

- AMARAN  
- DEVARA  
- LUCKY BHASKAR  
- KALKI 2898 AD  
- SARIPODHAA SANIVAARAM  

Each movie has multiple showtimes to select from.

---

### 🎟️ Ticket Booking

- Enter number of tickets  
- Input name and contact number  
- Choose seating class:  
  - **Normal Class**: ₹200 per ticket  
  - **Gold Class**: ₹700 per ticket  

---

### 💳 Payment Options

Choose to pay by **card** or **offline**:

- Card payments require:
  - Cardholder name  
  - 12-digit card number  
  - Valid expiry in `MM/YYYY` format  
  - 3-digit CVV  
- Offline payment option available at the theater counter.

---

### 🪪 DTCard Registration

Register for a DTCard by providing:

- Name  
- Mobile number (validated)  
- Email ID (validated for `@`)  

A unique 7-digit card number is auto-generated upon successful registration.

---

### ⚠️ Input Validations

- 📱 Contact number must be **10 digits**  
- 📧 Email must contain **@**  
- 💳 Card number: max **12 digits**  
- 🗓️ Expiry date: must be in **MM/YYYY** format and not expired  
- 🔒 CVV: must be **3 digits**

---

### 📸 Sample Output

```
 ----------------------------------
         MOVIE BUZZ
 ----------------------------------
         Welcome Customer!

         <1> Movie Timings
         <2> Contact Us
         <3> DTCard Registration
         <4> Exit

         Enter Your Choice:
```

---

### 📞 Contact Us

For more information, download our official app or reach us at:

```
01234567896523
```

---

### 📂 Project Structure

```
movie-ticket-booking-system/
├── MovieTicketBooking.cpp   # Main C++ source code
└── README.md                # Project documentation
```

---

### 🚀 Future Enhancements

- 📁 Add file storage for booking history  
- 🛠️ Admin panel for movie management  
- 🖥️ GUI version using frameworks like Qt or SFML  

---

### 📄 License

This project is open-source and free to use for learning and educational purposes.

---

### 🙋‍♀️ Author

**K.Kavya**  
🎓 Student, SRM University AP  
💻 Passionate about software development and building useful tools with C++ and web technologies.

---

⭐ *Feel free to fork, star, or contribute to the repository!*

