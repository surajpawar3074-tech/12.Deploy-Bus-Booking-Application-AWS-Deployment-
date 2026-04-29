# 12.Deploy-Bus-Booking-Application-AWS-Deployment-

## Project Overview
This project demonstrates a **cloud-based bus booking web application** deployed on AWS.  
Users can book bus tickets, and all booking data is stored in a MySQL database hosted on AWS RDS.

---

## Objective
To develop and deploy a **scalable web application** for booking bus tickets using AWS cloud infrastructure.

---

## Technologies Used

- :contentReference[oaicite:0]{index=0} – Backend runtime  
- :contentReference[oaicite:1]{index=1} – Web framework  
- :contentReference[oaicite:2]{index=2} – Database  
- AWS RDS – Managed database service  
- :contentReference[oaicite:4]{index=4} – Hosting server  
- :contentReference[oaicite:5]{index=5} – Process manager  
- HTML, CSS – Frontend  

---

## System Architecture

User → Browser → EC2 (Node.js App) → RDS (MySQL)

---

## Features

- ✅ Book bus tickets  
- ✅ Store booking details in database  
- ✅ Retrieve booking data  
- ✅ Cloud-based deployment  
- ✅ Always-running server using PM2  

---

## Deployment Steps

1. Created EC2 instance  
2. Installed Node.js  
3. Developed backend using Express.js  
4. Connected application to RDS MySQL  
5. Opened port **3000** in security group  
6. Used PM2 to keep server running  

---

1. EC2 Instance Running

<img width="1394" height="461" alt="Screenshot 2026-04-29 190150" src="https://github.com/user-attachments/assets/dbaa70af-c735-4f04-92a5-c03457347807" />

2. RDS Database Created

<img width="1563" height="642" alt="Screenshot 2026-04-29 190320" src="https://github.com/user-attachments/assets/c1dabf68-dced-4bfa-99c2-8dbe1e0dd70a" />

3. EC2 → RDS Connection (Terminal Proof)

<img width="1477" height="648" alt="Screenshot 2026-04-29 190457" src="https://github.com/user-attachments/assets/90605e58-f5b2-4c82-a717-3215e59f5af9" />

4. OUTPUT
•	Booking API working 
•	Data stored in database 
•	Public URL accessible 


<img width="1492" height="686" alt="Screenshot 2026-04-29 190626" src="https://github.com/user-attachments/assets/c74e7e1a-917c-474d-a7eb-7c2d45e4de7d" />


## CONCLUSION
Successfully built and deployed a full-stack cloud-based application with high availability and real-world architecture.
