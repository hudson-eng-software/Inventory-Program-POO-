# 🛒 Product Management System in Java

This project is a **simple Java program** that allows you to register a product, update its stock quantity (add or remove units), and display the updated product data.

---

## 🏷️ Badges
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![OOP](https://img.shields.io/badge/Paradigm-OOP-blue?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Dev Hudson](https://img.shields.io/badge/Dev-Hudson-green?style=for-the-badge&logo=java&logoColor=white)

---

## 📌 Features
- 📥 **Register a product** (name, price, and stock quantity).  
- ➕ **Add products to stock**.  
- ➖ **Remove products from stock**.  
- 📊 **Display updated product information**.  

---

## 📂 Project Structure
```java
src/
├── application/
│ └── Program.java
└── entities/
└── Product.java
```

# 

```java

- `Program.java`: contains the main logic (input handling and operations).  
- `Product.java`: class representing the product and its operations.  
````
---

## 🖥️ Example Usage
```java
Enter product data:
Name: Notebook
Price: 1200.00
Quantity in stock: 10

Product data: Notebook, $1200.00, 10 units, Total: $12000.00

Enter the number of products to be added in stock: 5
Updated data: Notebook, $1200.00, 15 units, Total: $18000.00

Enter the number of products to be removed from stock: 3
Updated data: Notebook, $1200.00, 12 units, Total: $14400.00
```

#

---

## 🚀 How to Run
1. Clone this repository:
```bash
   git clone https://github.com/your-username/java-product-system.git
```
2. Compile the files:
````java
javac application/Program.java entities/Product.java
````
3. Run the program
```java
java application.Program
````
Program : Dr.Nelio Alves - Udemy Class
