# 🩸 BloodBridge: Optimizing Lifesaving Resources Using RDS & EC2

**BloodBridge** is a cloud-based blood donation and management platform designed to streamline donor-recipient matching, blood inventory tracking, and emergency request management. By leveraging AWS cloud infrastructure, the platform ensures high availability, scalability, and secure data handling during critical times.

---

## 🚀 Features

- **Donor-Recipient Matching:** Smart matching system to connect patients with eligible blood donors quickly.
- **Blood Inventory Tracking:** Real-time monitoring of available blood units by blood group and location.
- **Emergency Request Management:** High-priority alerts and requests handling for urgent blood requirements.
- **Secure Cloud Database:** Robust data management using AWS RDS (Relational Database Service).
- **Scalable Hosting:** Hosted on AWS EC2 (Elastic Compute Cloud) for reliable performance.

---

## 🛠️ Tech Stack

- **Backend:** Python
- **Database:** AWS RDS 
- **Cloud Infrastructure:** AWS EC2, AWS RDS
- **Environment Management:** Python Virtual Environment (`venv`)

---

## 📁 Repository Structure

```text
├── app/                  # Application core logic, routes, and models
├── migrations/           # Database migration files
├── config.py             # Configuration settings for Flask/AWS
├── init_db.py            # Script to initialize the database
├── requirements.txt      # Python dependencies
└── run.py                # Main entry point to run the application
