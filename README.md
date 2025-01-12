# OTP Verification System 🔐  

This project is a Python-based **OTP (One-Time Password) Verification System** designed to provide secure authentication by generating and sending a 6-digit OTP to the user's email address and verifying the input.

---

## 📋 **Features**  
- **Email-based OTP delivery**: Sends a randomly generated OTP via Gmail's SMTP server.  
- **Secure authentication**: Uses environment variables to handle email credentials safely.  
- **Multiple verification attempts**: Allows up to three attempts for OTP entry.  
- **Error handling**: Ensures a smooth user experience by managing exceptions effectively.

---

## ⚙️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - `os`: For managing environment variables.  
  - `smtplib`: For sending emails via SMTP.  
  - `random`: For generating the OTP.  
  - `email.mime`: For formatting email content.  

---

## 🚀 **How It Works**  
1. **Setup**:  
   - Set up Gmail credentials as environment variables:  
     ```bash
     export EMAIL="your_email@gmail.com"
     export EMAIL_PASSWORD="your_app_password"
     ```  
   - Replace `your_email@gmail.com` and `your_app_password` with your Gmail and App Password respectively.  

2. **OTP Generation**:  
   - The system generates a random 6-digit OTP using Python's `random.randint` function.  

3. **Email Sending**:  
   - The OTP is sent to the provided email using Gmail's SMTP server with a custom subject and body.  

4. **Verification**:  
   - The user is prompted to enter the OTP.  
   - The system verifies the entered OTP with the generated one, allowing up to 3 attempts.  

5. **Access Control**:  
   - If the OTP matches, access is granted. Otherwise, access is denied after three incorrect attempts.

---

## 🖥️ **Usage**  
1. Clone this repository:  
   ```bash
   git clone <repository-link>
   cd otp-verification-system
   ```  

2. Install Python (if not already installed).  

3. Run the script:  
   ```bash
   python otp_verification_system.py
   ```  

---

## 🔗 **GitHub Link**  
Explore the complete code here: [GitHub Repository Link]((https://github.com/shriyanshmishra/OTP_Verification))  

---

## 🙌 **Contributions**  
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.  

---

## 📩 **Contact**  
If you have any questions or feedback, feel free to reach out:  
- Email: amitsdmishra10@gmail.com 
- LinkedIn: (https://www.linkedin.com/in/shriyansh-s-mishra-802522202/)
 
