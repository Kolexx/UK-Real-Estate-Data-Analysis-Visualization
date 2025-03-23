# **UK Real Estate Data Analysis & Visualization**

## **📌 Project Overview**
This project is a **web application** that scrapes real estate listings from [RightMove.co.uk](https://www.rightmove.co.uk), stores the data in an **AWS-hosted MySQL database**, and provides **graphical insights** for property investors. The goal is to help **both private and institutional investors** analyze the UK property market through data-driven insights.

---

## **🚀 Features**
- ✅ **Web Scraping**: Extracts property listings from RightMove.co.uk using `BeautifulSoup`.
- ✅ **Data Storage**: Saves data into an **AWS-hosted MySQL database**.
- ✅ **Flask Web App**: Serves the data and insights via a **user-friendly web interface**.
- ✅ **Data Visualization**: Generates **price distribution graphs** using `Matplotlib`.
- ✅ **Machine Learning (Upcoming)**: Implements a **property rating system** to identify high-potential investments.
- ✅ **Containerization (Upcoming)**: Docker setup for **scalability & cloud deployment**.

---

## **🛠️ Tech Stack**
| Component           | Tech Used |
|--------------------|-----------|
| **Backend**        | Flask (Python) |
| **Scraping**       | BeautifulSoup, Requests |
| **Database**       | MySQL (AWS RDS) |
| **Visualization**  | Matplotlib, Pandas |
| **Frontend**       | HTML, CSS (Jinja Templates) |
| **Cloud & Hosting**| AWS (RDS, EC2, S3) |
| **Containerization**| Docker (Upcoming) |

---

## **📂 Project Structure**
```
real_estate_analysis/  
│── venv/                   # Virtual environment  
│── templates/              # HTML templates for Flask  
│   ├── index.html          # Main dashboard  
│── static/                 # Static files (CSS, Images, Charts)  
│   ├── price_distribution.png  
│── scraper.py              # Scrapes RightMove data  
│── database.py             # Stores data in MySQL  
│── app.py                  # Flask web application  
│── visualization.py        # Generates graphs  
│── properties.csv          # Sample data file  
│── requirements.txt        # Project dependencies  
│── Dockerfile              # Containerization setup (Upcoming)  
```

---

## **🔧 Setup & Installation**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/real-estate-analysis.git
cd real-estate-analysis
```

### **2️⃣ Create a Virtual Environment & Install Dependencies**
```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

### **3️⃣ Configure Database (MySQL on AWS)**
- Create an **AWS RDS MySQL instance**.
- Update `database.py` with your **DB credentials**.
- Run **database setup script**:
  ```bash
  python database.py
  ```

### **4️⃣ Run the Scraper**
```bash
python scraper.py
```

### **5️⃣ Run the Flask Web App**
```bash
python app.py
```
Access the app in your browser at: `http://127.0.0.1:5000/`

---

## **📊 Sample Visualization**
The project generates property price distribution graphs like this:
![Property Price Distribution](static/price_distribution.png)

---

## **🔮 Future Improvements**
- 🚀 **Machine Learning Property Rating System**
- 🌍 **Deploy to AWS using EC2 & S3**
- 🐳 **Docker & Kubernetes for Scalability**



