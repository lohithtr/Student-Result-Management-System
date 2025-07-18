# Student Result Management System

The Student Result Management System is a web-based application designed to simplify and automate the process of managing student academic records. Built using HTML, CSS, JavaScript, PHP, and MySQL, this project enables administrators to efficiently handle student data, manage subject records, publish academic results, and generate individual marksheets through a clean, responsive user interface.
The system includes a secure login-based dashboard that grants access exclusively to authorized administrators. From the dashboard, they can perform key functions such as adding or editing student and subject records, entering scores, and publishing final results. Students’ results can then be viewed in a well-structured and user-friendly format, making the platform an ideal solution for academic institutions aiming to digitize and streamline their result management process.

## ✅ Steps to Run the Project

1. **Install XAMPP**

   * Download and install XAMPP from [https://www.apachefriends.org](https://www.apachefriends.org).
   * This will install Apache (for PHP) and MySQL (for the database).

2. **Start XAMPP Services**

   * Open the XAMPP Control Panel.
   * Click **Start** next to both:

     * Apache
     * MySQL

3. **Download or Clone the Project**

   * **Option 1 (Git)**:

     ```bash
     git clone https://github.com/lohithtr/Student-Result-Management-System.git
     ```
   * **Option 2 (Manual)**:

     * Go to the GitHub repository.
     * Click `Code` → `Download ZIP`.
     * Extract the downloaded ZIP file.

4. **Move Project to XAMPP's htdocs Folder**

   * Copy the entire project folder (e.g., `Student-Result-Management-System`).
   * Paste it into:

     ```
     C:\xampp\htdocs\
     ```

5. **Set Up the MySQL Database**

   * Open your browser and go to:

     ```
     http://localhost/phpmyadmin/
     ```
   * Click **"New"** in the sidebar to create a new database:

     ```
     Database name: srms
     ```
   * Click the newly created `srms` database.
   * Go to the **Import** tab, choose the `srms.sql` file from your project folder, and click **Go**.

6. **Run the Project in Browser**

   * In your browser, go to:

     ```
     http://localhost/Student-Result-Management-System/
     ```
   * You should see the login page.

7. **Login Using Default Admin Credentials**

   ```
   Username: admin
   Password: admin
   ```

8. **(Optional) Update Database Connection Settings**

   * If needed, open:

     ```
     includes/config.php
     ```
   * Update DB name, username, or password as per your local setup.

---

