# Online_Disaster_Information_Management_System
A web-based disaster information system built with ASP.NET and SQL Server. Supports user, relief, and disaster data management by NDMA and institutes. Allows public access to verified disaster and relief updates, ensuring transparency and efficient communication.




## 📌 Project Overview
This project is a web-based disaster information management system developed using ASP.NET and SQL Server. It enables the **National Disaster Management Authority (NDMA)** and registered **Rehabilitation Institutes** to manage disaster and relief data, while allowing the public to access verified information.

---

## 🎯 Key Features

### 👤 User Roles:
- **NDMA Admin**
- **Rehabilitation Institute**
- **General User**

### ✅ Functional Requirements

- **User Management**
  - NDMA can manage website users.

- **Disaster & Relief Management**
  - NDMA and Institutes can add and update disaster and relief info.

- **Institute Registration**
  - Institutes can register and get approved by NDMA.

- **Relief Reporting**
  - Institutes can report relief efforts and share updates.

- **Disaster Reporting**
  - Institutes can report disaster events.

- **Public Communication**
  - Institutes can post public awareness messages.

- **User Registration**
  - General users can sign up and access verified information.

- **Information Access**
  - General users can view disaster and relief information.

---

## 🛠️ Tech Stack

| Layer            | Technology Used           |
|------------------|---------------------------|
| Frontend         | ASP.NET Web Forms         |
| Backend          | C#                        |
| Database         | SQL Server                |
| Server           | IIS / Localhost           |
| Styling          | Bootstrap (Optional)      |

---

## 🗃️ Database Design (Overview)

- **Users Table** – Stores login credentials and user roles.
- **Institutes Table** – Stores registered institute information.
- **Disasters Table** – Contains disaster type, location, and date.
- **Relief Table** – Includes relief type, beneficiaries, and status.
- **Messages Table** – For institute-public communication.

---

## 🧪 Installation & Setup

1. Clone the repository.
2. Open the solution in **Visual Studio**.
3. Restore NuGet packages (if applicable).
4. Set up the **SQL Server** database using the provided `.sql` script.
5. Configure the connection string in `web.config`.
6. Run the project using IIS Express or your preferred method.

---

## 📈 Future Enhancements

- SMS/Email Alerts to Users
- Real-time Disaster Mapping
- Multilingual Support
- Mobile-Friendly UI

---

## 👥 Contributors

- Muhammad Junaid Qazi  
- [Add more if applicable]

---

## 📄 License

This project is for academic and research use. Feel free to modify and extend for non-commercial purposes.
