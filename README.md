**Name:** JEEVA PRIYA R
- **Company:** CODTECH IT SOLUTIONS
- **ID:** CT08DS2944
- **Domain:** ETHICAL HACKING
- **Duration:** JUNE 25th, 2024 to JULY 25th, 2024
- **Mentor:** Neela Santhosh Kumar




# Overview of the Project

## Project Name: PASSWORD STRENGTH CHECKER
![image](https://github.com/user-attachments/assets/38d7060b-5d7e-47cc-8d00-0d7c05651dad)


## Objective
The Password Strength Checker is a Python tool designed to evaluate the strength of user passwords based on several criteria, ensuring they meet security best practices. The goal is to help users create stronger passwords, enhancing their overall cybersecurity posture.

## Key Activities
- **Length Check**: Ensures the password is at least 12 characters long.
- **Lowercase Check**: Verifies the presence of at least one lowercase letter.
- **Uppercase Check**: Verifies the presence of at least one uppercase letter.
- **Digit Check**: Verifies the presence of at least one numeric digit.
- **Special Character Check**: Verifies the presence of at least one special character (e.g., !@#$%^&*()).
- **Common Pattern Check**: Checks for the presence of common patterns or sequences (e.g., "1234", "abcd", "qwerty").
- **Repeated Character Check**: Ensures the password does not contain any character repeated more than twice in a row.
- **Wordlist Check**: Compares the password against a list of common passwords to ensure it is not easily guessable.

## Technology Used
- **Python**: The primary programming language used to develop the tool.
- **Regular Expressions (re)**: Used for pattern matching within passwords.
- **File Handling**: Used to read the wordlist of common passwords.

## Key Insights
- **Password Length**: Longer passwords are inherently more secure due to the increased number of possible combinations.
- **Character Variety**: Including a mix of uppercase, lowercase, digits, and special characters significantly enhances password strength.
- **Avoiding Common Patterns**: Simple sequences and common words are easily guessed by attackers, making it crucial to avoid them.
- **Repetition Avoidance**: Repeated characters can make a password easier to crack.
- **Use of Common Passwords**: Avoiding commonly used passwords is essential as they are often the first targets for attackers.

## How to Use
1. Clone the repository or download the script.
2. Ensure you have Python installed on your system.
3. Place your wordlist file (`top_10000_passwords.txt`) in the same directory as the script.
4. Run the script in your terminal or command prompt:
    ```sh
    python password_strength_checker.py
    ```
5. Follow the on-screen prompts to enter passwords and receive feedback on their strength.

## Future Enhancements
- Add a graphical user interface (GUI) for a more user-friendly experience.
- Implement real-time password strength feedback as the user types.
- Enhance the wordlist to include more common passwords for improved security.
- Provide suggestions for creating stronger passwords based on the failed criteria.

---

This project aims to empower users with the knowledge and tools needed to create strong, secure passwords, thereby improving their overall cybersecurity.
