### **OTP Generator - Web Application**  

A simple and stylish **OTP (One-Time Password) Generator** built using **HTML, CSS, and JavaScript**. This project generates a random 4-digit OTP and displays it on the webpage in a user-friendly format.  

---

## **📌 Features**  
✅ **Modern UI** - Clean and responsive design with smooth interaction.  
✅ **Random OTP Generation** - Secure 4-digit OTP generation using JavaScript.  
✅ **User-Friendly Input Field** - Easy-to-use phone number input.  
✅ **Dynamic OTP Display** - OTP appears in a styled green-bordered box.  
✅ **Interactive Button** - Hover effect for a better user experience.  

---

## **🚀 How It Works?**  
1. Enter your phone number in the input field.  
2. Click the **"Get OTP"** button.  
3. A **4-digit OTP** is generated and displayed inside a styled box.  

---

## **🛠️ Technologies Used**  
- **HTML** - Page structure  
- **CSS** - UI styling and layout  
- **JavaScript** - OTP generation and dynamic updates  

---

## **📂 Installation & Usage**  
1. Clone this repository or download the ZIP file.  
   ```sh
   git clone https://github.com/prangowda/otp-generator.git
   ```
2. Open the **index.html** file in a browser.  
3. Use the interface to generate OTPs.  

---

## **📜 Code Explanation**  

The OTP is generated using JavaScript’s `Math.random()`, ensuring a **random 4-digit number**.  
```javascript
function generateOTP(length) {
    let otp = '';
    for (let i = 0; i < length; i++) {
        otp += Math.floor(Math.random() * 10);
    }
    return otp;
}
```
The generated OTP is then displayed dynamically in a styled `<span>` tag when the user clicks the button.  
