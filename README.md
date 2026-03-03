# 🛒 AI-Powered Price Comparison using CrewAI & Streamlit

## 🚀 Overviews
This project is an **AI-powered product price comparison tool** built using **CrewAI** and **Streamlit**.  
It helps users **search for products across e-commerce platforms**, **clean the data**, **compare prices**, and **display the best deal**.

## 🎯 Features
✅ **Multi-agent system** for accurate price fetching and comparison.  
✅ **Smart filtering** to remove incorrect/duplicate data.  
✅ **Currency conversion** based on user location.  
✅ **User-friendly Streamlit UI** for interactive product searches.  
✅ **Final Report Generation** for easy decision-making.  

---

## 📜 How It Works

### **1️⃣ Search Agent (Product Price Finder)**
- Uses **Serper API** & **Scraping** to fetch product prices from multiple e-commerce websites.  
- Filters out **irrelevant search results**.

### **2️⃣ Data Cleaning Agent**
- Removes **duplicate & incorrect entries**.  
- Converts **prices into the user's country currency**.  

### **3️⃣ Price Comparison Agent**
- **Sorts and ranks** prices from lowest to highest.  
- Highlights the **most trusted website** offering the best deal.  

### **4️⃣ Final Report Agent**
- Generates a structured **price comparison report**.  
- Recommends the **best deal with reasoning**.  

---

## 🛠️ Installation & Setup

### **1️⃣ Install Dependencies**
Run the following command:  
```bash
pip install -r requirements.txt
```

### **2️⃣ Set Up API Keys**
Create a `.env` file and add:
```makefile
OPENAI_API_KEY=your_openai_api_key
SERPER_API_KEY=your_serper_api_key
```

### **3️⃣ Run the Application**
To start the Streamlit app, use:
```bash
streamlit run app.py
```

---

## 📌 Example Search

**User searches for:**  
🛒 **Product**: _Lenovo Earbuds LP40_  
🌍 **Country**: _Pakistan_

### **🔍 The system returns:**
- **Amazon:** $19.99 ✅
- **eBay:** $21.50 ❌
- **AliExpress:** $17.99 ✅ (Best Deal)

---

## 🔥 Technologies Used

- **CrewAI** (Multi-agent AI framework)
- **OpenAI GPT API** (For AI-powered decision-making)
- **SerperDev API** (Google search integration)
- **Streamlit** (Frontend UI)

