## 🔧 Prerequisites

- **JDK 17**
- **Maven 3.9**
- **MySQL 8**

---

## 🛠️ Technologies Used

- Spring MVC  
- Spring Security  
- Spring Data JPA  
- Maven  
- JSP  
- Tomcat  
- MySQL  
- Memcached  
- RabbitMQ  
- Elasticsearch

---

## 🗄️ Database Setup

This project uses **MySQL** as the primary database.

A MySQL **dump file** is provided at:

- `src/main/resources/db_backup.sql`

Additionally, database connection details for **build/deployment** are managed via the `buildspec.yaml` file is provided at:

- `aws-files/buildspec.yaml`

### 📥 Importing the Database

Use the following command to import the dump into your MySQL database:

```bash
mysql -u <username> -p accounts < src/main/resources/db_backup.sql
