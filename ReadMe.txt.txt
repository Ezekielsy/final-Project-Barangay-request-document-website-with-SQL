🧑‍💻 SA CLASSMATE NA PC (INSTALLATION)
🧩 STEP 4: INSTALL XAMPP

Download:

https://www.apachefriends.org


Install → Start Apache + MySQL

🧩 STEP 5: ILAGAY ANG FILES

1️⃣ Extract barangay_system.zip
2️⃣ Copy folder
3️⃣ Paste sa:

C:\xampp\htdocs\

🧩 STEP 6: IMPORT DATABASE

1️⃣ Open:

http://localhost/phpmyadmin


2️⃣ Create database:

barangay_db


3️⃣ Click Import
4️⃣ Choose barangay_db.sql
5️⃣ Click Go

🧩 STEP 7: AYUSIN config.php

📄 barangay_system/db/config.php

<?php
$conn = mysqli_connect("localhost","root","","barangay_db");
if (!$conn) {
  die("Database connection failed");
}
?>


⚠ Siguraduhin database name pareho

🧪 STEP 8: TEST

Open browser:

http://localhost/barangay_system


✔ Request form works
✔ Track works
✔ Admin page works

🧠 PANG DEFENSE LINE

“The system is portable and can be deployed on any computer using XAMPP by transferring both the source files and database.”

🔥 OPTION 2 (ADVANCED)

✔ GitHub (version control)
✔ Online hosting (000webhost)

Sabihin mo kung gusto mo yun, gagabayan kita step-by-step 😄