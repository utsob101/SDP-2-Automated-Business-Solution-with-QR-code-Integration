# Automated Business Solution with QR Code Integration  

## Prerequisites  

Before running this Python script, follow these steps to set up your environment.  

### Environment Setup  

Ensure you have the following libraries installed. Use the terminal for a better experience:  

1. **tkinter** – For building the Graphical User Interface (GUI).  
2. **qrcode** – For generating QR codes.  
3. **fpdf** – For creating PDF files.  
4. **gspread** – For interacting with Google Sheets.  
5. **google.oauth2.service_account** – For Google authentication.  
6. **pandas** – For data analysis and manipulation.  
7. **matplotlib.pyplot** – For data visualization (graphs & charts).  
8. **datetime** – For working with dates and times.  
9. **pymysql** – For connecting to a MySQL database.  
10. **requests** – For sending HTTP requests (useful for API calls).  

To install these libraries, run the following command in your terminal:  

```bash
pip install tkinter qrcode fpdf gspread pandas matplotlib pymysql requests
```

For Google authentication, set up your credentials properly.  

### MySQL Workbench Setup  

1. Download and install **MySQL Workbench**.  
2. During installation, create a password for your MySQL root user.  
3. In your Python script, update the following lines with your credentials:  

   - **Line 106:**  
     ```python
     password="your_mysql_password"
     ```  
   - **Line 107:**  
     ```python
     database="your_database_name"
     ```  

   ⚠ **Make sure you remember the password you set during installation.**  

## Final Step  

Once everything is set up correctly, you should be able to run the script successfully.  

🎉 Congratulations! You're ready to go! 🚀  
