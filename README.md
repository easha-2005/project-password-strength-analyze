# project-password-strength-analyze
🧾 Title:
Password Strength Analyzer 

👩‍💻 Domain:
Cybersecurity – Password Auditing & Ethical Hacking

📝 Internship Project Phase (2 Weeks)
Duration: 2 Weeks
Tools Used: Python, zxcvbn, datetime module, file handling

🧠 Introduction
In today’s digital world, users often create passwords that are weak, predictable, or reused across platforms. This project addresses the risk of such passwords by analyzing their strength and generating a custom wordlist based on common user details like name, birth date, and pet names. These wordlists simulate real-world attack vectors used in dictionary or brute-force attacks and raise awareness about password security.

📌 Abstract
The goal of this project is to:

Analyze the strength of any given password using the zxcvbn library.

Collect personal user data to generate a custom password wordlist.

Show how attackers might use common details to crack passwords.

Educate users on the importance of strong, complex, and unique passwords.

This project supports both password education and ethical hacking training scenarios.

🧰 Tools Used
Tool	Purpose
Python 3	Programming base
zxcvbn	Password analysis and scoring
datetime	Timestamping events
File I/O	Saving .txt wordlists

✅ Page 2:
🛠️ Steps Involved in Building the Project
Password Input:
The user inputs a password to check its strength.

Analysis via zxcvbn:
The zxcvbn Python module returns:

A score from 0 (weak) to 4 (strong)

Estimated crack time in different attack models

Suggestions to improve the password

User Data Input:
Users enter personal info such as:

Name

Date of birth

Pet’s name

Custom Wordlist Generation:
The script generates permutations of the data:

Reversed strings

Common suffixes like 123, 2025, @123

Leetspeak replacements (e.g., a → @, i → 1)

Upper/lowercase variations

Saving the Wordlist:
The output wordlist is saved as custom_wordlist.txt and can be used with cracking tools like Hydra or John the Ripper in simulations.

📌 Sample Output
yaml
Copy
Edit
Password Score: 2  
Estimated Crack Time: 3 hours  
Feedback: Too short. Add another word or two. Avoid common phrases.
Wordlist Saved: custom_wordlist.txt
✅ Conclusion
This project highlights how weak and predictable passwords can be exploited using simple scripts. The password analyzer gives users instant feedback, while the wordlist generator shows how attackers can construct guesses using publicly known or leaked personal data.

By combining these features, this tool serves as an educational and penetration-testing resource. It promotes awareness of strong password practices and ethical hacking techniques.

