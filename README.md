# **Driving and Vehicle License Department (DVLD) System**
## **About**
A comprehensive desktop application built using **C#**, **WinForms**, and **SQL Server**, designed to manage all operations of a government Driving & Vehicle License Department. The system follows a **three‑tier architecture** (Presentation, Business Logic, Data Access) to ensure scalability and maintainability.

---

## **Features Overview**

### **User Management**
- Add, edit, and delete system users  
- Assign permissions and roles  
- Change login credentials  
- Freeze or activate accounts  

---

### **People Management**
Maintain complete citizen records including:
- National ID  
- Full name  
- Date of birth  
- Address  
- Phone number  
- Email  
- Nationality  
- Personal photo  

---

### **Driver License Management**
Issue, renew, and manage all license classes:
- Motorcycle  
- Regular  
- Commercial  
- Agricultural  
- Bus  
- Heavy truck  

---

### **New License Applications**
Full workflow for new license issuance:
- Application form & fees  
- Eligibility verification (age requirements)  
- Vision test scheduling & results  
- Theoretical test scheduling & results  
- Practical test scheduling & results  
- License issuance with validity tracking  

---

### **International License**
- Issue international driving permits  
- Available only for holders of valid regular licenses  
- Fee processing  
- Renewal & validity tracking  
- Auto‑cancellation of previous international licenses  

---

### **Test Management**
Manage all driving test types:
- Vision tests  
- Theoretical knowledge tests  
- Practical driving tests  
- Retake scheduling  

---

### **Driver Information**
- License history  
- Test history  
- License status  
- Personal details  

---

### **License Detainment**
- Record detainment reasons  
- Apply fines  
- Track detainment dates  
- Process license release  

---

### **License Replacement**
- Handle lost or damaged license replacement  
- Fee processing  
- Eligibility verification  
- Issue replacement with same validity  

---

## **Architecture**
The system follows a **three‑tier architecture**:

- **Presentation Layer:** WinForms UI (`DVLD` project)  
- **Business Layer:** Business logic & rules (`DVLD_Business`)  
- **Data Access Layer:** SQL operations (`DVLD_DataAccess`)  

---

## **Database Structure**
Includes tables for:
- People  
- Drivers  
- License applications  
- License classes  
- Tests & appointments  
- Users & permissions  
- Detainment records  

---

## **Technologies Used**
- C#  
- .NET Framework  
- Windows Forms  
- SQL Server  
- ADO.NET  
---

## **📥 Installation**
1. Clone the repository  
2. Open the solution in Visual Studio  
3. Restore the database backup (`DVLD.bak`)  
4. Update the connection string  
5. Build and run the application  

---

## **🔐 Default Login**
```
Username: Alia_1
Password: 12
```

---
