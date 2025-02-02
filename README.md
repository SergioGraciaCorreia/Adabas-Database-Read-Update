# 🖥️ Mainframe Database Interaction: Read and Update Utility - Version 1.0  

**Welcome to the Mainframe Natural Training Project**  
This is a program developed in **Natural**, a programming language for mainframe environments. The program allows users to select and modify data from a company table (`AOCUCOTU`), using two interactive maps and simulated transactions.  

---

## 🛠️ Project Description  
The goal of the program is to enable users to:  
1. Select a record from the `AOCUCOTU` table (companies) in **ascending** or **descending** order.  
2. View the details of the selected record.  
3. Modify specific fields of the record and simulate updates using a **backout transaction** (no real changes are made to the database).  

---

## 🎮 Key Features  
Here are the main features of the program:

### 1. Record Selection  
- Users can choose between **ascending** (`A`) or **descending** (`D`) order to display records.  
- If no order is selected, the first 5 records are displayed by default.  

### 2. Interactive Maps  
- **Map 1 (`SGCM0108`)**: Allows users to select a record by marking it with an `X`.  
- **Map 2 (`SGCM108B`)**: Displays the details of the selected record and allows users to modify specific fields (`CCOA`, `GREC-CCO`, `IPRC-CCO`).  

### 3. Simulated Updates  
- Uses a **backout transaction** to simulate updates without making real changes to the database.  
- After simulating an update, a confirmation message is displayed.  

### 4. Error Handling  
- Validates user input (e.g., ensures only one record is selected, checks for valid order selection).  
- Displays error messages for invalid inputs or actions.  

---

## 🎮 How to Use  
1. **Start the program**: The first map (`SGCM0108`) is displayed.  
2. **Select an order**: Choose between ascending (`A`) or descending (`D`) order, or press Enter to display the first 5 records.  
3. **Select a record**: Mark a record with an `X` and press Enter to view its details on the second map (`SGCM108B`).  
4. **Modify fields**: Update the fields (`CCOA`, `GREC-CCO`, `IPRC-CCO`) as needed.  
5. **Simulate an update**: Press `PF4` to simulate the update and see a confirmation message.  
6. **Exit**: Press `PF3` at any time to exit the program.  

---

## ⚙️ System Requirements  
- **Environment**: Mainframe with Natural programming language support.  
- **Resources**: The program is designed to run in a terminal-based mainframe environment.  

---

## 📂 Code Structure  
- **Main Logic**: The program is structured into subroutines for handling each map and performing actions like record selection, validation, and simulated updates.  
- **Maps**:  
  - `SGCM0108`: For record selection.  
  - `SGCM108B`: For displaying and modifying record details.  
- **Variables**: Key variables include `CCOK` (company code), `CCOA` (company name), `GREC-CCO` (group code), and `IPRC-CCO` (priority code).  

---

## 🎨 Credits  
- **Developed by**: Sergio Gracia Correia.  
- **Purpose**: This project was created as part of a training program to demonstrate skills in Natural programming and mainframe environment interaction.  
- **Inspiration**: The program showcases how to handle user input, simulate transactions, and interact with databases in a constrained environment.  

---

 
