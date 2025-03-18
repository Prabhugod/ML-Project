# 📊 Bank Marketing Campaign Dataset

## 📌 Overview
The dataset contains information on **direct marketing campaigns** of a banking institution. These campaigns were conducted via **phone calls**, often requiring multiple contacts to determine if the client would subscribe to a **bank term deposit**.

---

## 📁 Files
- **`train.csv`** – Training dataset  
- **`test.csv`** – Test dataset  
- **`sample_submission.csv`** – Sample submission file (correct format)

---

## 🔹 Features (Input Variables)

### 📅 Last Contact Information
1. **last contact date** – Last contact date  

### 🏡 Demographic Information
2. **age** *(numeric)* – Age of the client  
3. **job** *(categorical)* – Type of job  
4. **marital** *(categorical)* – Marital status: `married`, `divorced`, `single`  
5. **education** *(categorical)* – Education level: `unknown`, `secondary`, `primary`, `tertiary`  
6. **default** *(binary)* – Has credit in default? (`yes`, `no`)  
7. **balance** *(numeric)* – Average yearly balance (in euros)  

### 💳 Loan & Financial Status
8. **housing** *(binary)* – Has a housing loan? (`yes`, `no`)  
9. **loan** *(binary)* – Has a personal loan? (`yes`, `no`)  

### 📞 Contact Information
10. **contact** *(categorical)* – Contact type: `unknown`, `telephone`, `cellular`  
11. **duration** *(numeric)* – Last contact duration (in seconds)  

### 📢 Campaign Details
12. **campaign** *(numeric)* – Number of contacts performed during this campaign (includes last contact)  
13. **pdays** *(numeric)* – Days since the client was last contacted in a previous campaign (`-1` means never contacted)  
14. **previous** *(numeric)* – Number of contacts before this campaign  
15. **poutcome** *(categorical)* – Outcome of the previous marketing campaign: `unknown`, `other`, `failure`, `success`  

---

## 🎯 Target Variable (Output)
16. **target** *(binary)* – Did the client subscribe to a term deposit? (`yes`, `no`)  

---

This dataset can be used to build **predictive models** for **customer conversion** and **marketing optimization**. 🚀📈
