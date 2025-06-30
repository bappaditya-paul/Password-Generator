# Password-Generator
.A simple Python-based password generator that lets users choose the number of letters, symbols, and numbers. It uses `random` to generate secure passwords, with both ordered (easy) and shuffled (hard) versions. Ideal for beginners learning loops, lists, and randomness in Python.

:

🔐 Password Generator
-> Password Generator is a Python-based tool that allows users to create secure, randomized passwords tailored to their specific requirements. By specifying the number of letters, symbols, and numbers, users can generate strong passwords suitable for various applications, enhancing both personal and professional security practices.

🚀 Features
(1) Customizable Password Structure
    (i) Users can define the exact number of letters, symbols, and digits in the password.

(2) Secure Randomization
   (i) Uses Python’s built-in random module to ensure high entropy in password creation.

(3) Two Generation Modes
    (i) Easy Mode (commented out): Characters are added in a fixed order (less secure).
    (ii) Hard Mode: Characters are randomized using random.shuffle() for stronger security.

(4) Educational Value
   (i) Ideal for beginners learning:
  (ii)List operations and string manipulation
  (iii)User input handling with input()
  (iv)Use of random.choice() and random.shuffle()
  (v)Basic control structures and logic in Python

🛠️ How It Works
   i) The user is prompted to enter how many letters, symbols, and numbers they want in their password.
   ii)The program selects characters randomly from predefined lists for each category.
   iii) In hard mode, the selected characters are shuffled to ensure randomness.
   iv)The final password is assembled and displayed.

📚 Use Case
This project is perfect for learning core programming concepts in a practical, security-focused application. Whether you're a beginner exploring Python or an educator teaching randomness and logic, this script provides a clear and functional example.

