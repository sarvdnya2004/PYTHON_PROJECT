# **Random Password Generator**

## **Overview**
This project is a Python-based random password generator designed to create secure and customizable passwords. The program generates random passwords of user-defined lengths, with additional features to include numbers and uppercase letters for enhanced security.

---

## **Features**
- Generate multiple passwords in a single execution.
- User-defined password lengths with a minimum length of 3 characters.
- Automatic inclusion of:
  - Random numbers within the password.
  - Random uppercase letters for better complexity.
- Ensures all passwords are randomly generated, making them secure.

---

## **How It Works**
1. The user specifies the number of passwords they want to generate.
2. For each password:
   - The user inputs the desired length (minimum of 3 characters).
   - A random password is generated using lowercase letters.
   - Numbers and uppercase letters are randomly added for improved security.
3. The program outputs all the generated passwords.

---

## **Example Usage**
```bash
How many passwords do you want to generate? 2
Generating 2 passwords
Minimum length of password should be 3
Enter the length of Password #1: 6
Enter the length of Password #2: 8
Password #1 = a2Bcde
Password #2 = abcD3efG
