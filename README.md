# 🔐 Password Generator (Python)

A customizable password generator that creates multiple secure passwords based on user-defined lengths. The program uses randomization, character substitution, and uppercase transformations to increase password complexity and ensure stronger security. It includes input validation and modular functions for clean, maintainable code.

---

## 🚀 Features

- Generate multiple passwords in a single run  
- User-defined password lengths  
- Automatic length correction (minimum 3 characters)  
- Random lowercase alphabet generation  
- Automatic replacement of:  
  - **Numbers** in the first half of the password  
  - **Uppercase letters** in the second half  
- Modular function-based structure  
- Ensures each password is unique and unpredictable  

---

## 🧠 How It Works

1. User enters how many passwords they want to generate  
2. User specifies the length for each password  
3. For each password:
   - A random sequence of lowercase letters is generated  
   - Random positions are replaced with digits  
   - Other random positions are replaced with uppercase letters  
4. All passwords are displayed to the user  

---

## 🛠️ Technologies Used

- **Python**
- **Random Module**
- **String Manipulation**
- **Input Validation**
- **Functional Programming Concepts**
