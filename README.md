# Professional Profile - Software Tester

## ✨ About Me
**Name**: Bogdan-Irinel  
**Desired Role**: Software Tester  
**Experience**: Passionate about software testing and ensuring application quality, with a keen eye for detail and a continuous desire to improve user experiences. Experienced in writing test cases and reporting bugs accurately to support development teams.  

**Technical Skills**:
- Manual and exploratory testing.  
- Writing and executing test cases.  
- Reporting and tracking bugs.  
- Familiarity with tools such as Jira, TestRail, and Postman.  

**Objective**:  
To contribute to the creation of high-quality software by identifying and addressing issues, while continuously developing my technical and collaborative skills.

---

## 🛠️ Portfolio

### 📋 Test Cases

#### 1. Altex Search - Nonexistent Product
**Description**:  
Verify the functionality of the "Caută produsul dorit" search form when a nonexistent product is entered.

**Preconditions**:  
- None.  

**Steps to Reproduce**:  
1. Open the [Altex website](https://altex.ro/).  
2. Click on the "Caută produsul dorit" search form.  
3. Enter the term "zxcvbnm".  

**Expected Result**:  
The search form should display a message for nonexistent products.  

---

#### 2. Altex Search - Autocomplete
**Description**:  
Verify the autocomplete functionality of the "Caută produsul dorit" search form when three or more characters are entered.

**Preconditions**:  
- The user must enter at least three characters.  

**Steps to Reproduce**:  
1. Open the [Altex website](https://altex.ro/).  
2. Click on the "Caută produsul dorit" search form.  
3. Enter the term "mas".  

**Expected Result**:  
The search form should display relevant autocomplete data.  

---

### 🐞 Reported Bugs

#### 1. Broke at a Click of a Button
**Priority**: P1  
**Severity**: Critical  

**Description**:  
Out of the three links used for sorting transactions, only one ("Date-Time") is functional.

**Steps to Reproduce**:  
1. Visit [Banking Project](https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login).  
2. Click the "Customer Login" button.  
3. Click the "---Your Name---" dropdown menu.  
4. Select a client (e.g., "Hermoine Granger").  
5. Click the "Login" button.  
6. The balance is $5096.  
7. Click the "Transactions" button.  
8. Click the "Reset" button.  
9. All transactions are erased without any warning.  
10. Click the "Back" button.  
11. The balance is now $0; all money from the account has disappeared.  

**Expected Result**:  
The "Reset" button should reset the calendar sorting only.  

**Actual Result**:  
The "Reset" button erases all transactions and money from the account without any warning.  

---

#### 2. Customer, Accounts, and Money - Erased
**Priority**: P1  
**Severity**: Critical  

**Description**:  
The system incorrectly allows the deletion of non-empty accounts.

**Steps to Reproduce**:  
1. Visit [Banking Project](https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login).  
2. Click the "Customer Login" button.  
3. Click the "---Your Name---" dropdown menu.  
4. Select "Hermoine Granger" as the client.  
5. Click the "Login" button.  
6. The balance is $5096.  
7. Click the "Logout" button.  
8. Click the "Home" button.  
9. Click the "Bank Manager Login" button.  
10. Click the "Customers" button.  
11. Click the "Delete" button in the "Hermoine Granger" row.  
12. Click the "Home" button.  
13. Click the "Customer Login" button.  
14. Click the "---Your Name---" dropdown menu.  
15. Select "Hermoine Granger."  
16. The customer, accounts (both empty and non-empty), and money are erased.  

**Expected Result**:  
The deletion of a non-empty account should not be allowed.  

**Actual Result**:  
The deletion of a non-empty account is permitted.  

---

## 📞 Contact
- **Email**: bogdan.irinel@example.com  
- **LinkedIn**: [linkedin.com/in/bogdan-irinel](https://linkedin.com/in/bogdan-irinel)  

---

This document serves as an example from my professional portfolio. I aspire to work as part of a team dedicated to software quality, ensuring high standards of performance and reliability.
