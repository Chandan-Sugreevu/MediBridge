# 🚀 MediBridge  
*Connecting surplus medicine to those in need*

## 🌍 Inspiration  
Every year, **billions of dollars** worth of unused medications are discarded by:  
- Pharmacies  
- Hospitals  
- Nursing homes  

Hospitals alone waste over **$800 million** of usable drugs annually. Meanwhile, **1 in 3 Americans skip medications due to cost**.  

MediBridge aims to **bridge the gap** between wasted medications and underserved communities.  

---

## 💡 What It Does  
MediBridge connects:  
- 🏥 **Pharmacies** with excess or soon-to-expire drugs offering steep discounts  
- 🏘️ **Nonprofits & clinics** serving vulnerable populations, including shelters and community health centers  

This reduces waste and improves access to essential medicine, creating **environmental** and **social impact**.  

---

## 🏗️ Tech Stack  

| Frontend     | Backend        | Database | External APIs           | Other              |
|--------------|----------------|----------|------------------------|--------------------|
| React        | Flask (Python) | SQLite   | NDC Directory API       | Google OAuth       |
| Tailwind CSS | REST Endpoints |          | Mapbox API (Location)  |                    |

---

## ⚙️ How It Works  

1. **Login** with Google OAuth  
2. Choose role:  
   - 🏪 **Pharmacy:** List surplus medications by NDC code, price, expiration date, etc.  
   - 🤝 **Nonprofit:** Search for medications by drug name and location; results show nearest pharmacies with availability.  
3. Medication info is fetched from **NDC Directory API** and stored in a secure SQLite database.

---

## 🎉 Features & Accomplishments  

- ✅ Full-stack app deployed with React + Flask  
- 🔐 Secure Google Authentication integration  
- 📍 Location-based medication search via Mapbox API  
- 📈 Practical experience with APIs, databases, and user roles  
- 🤝 Collaborative team effort under hackathon constraints  

---

## 🔧 Future Enhancements  

- 🔎 Advanced filtering (radius, brand, dosage)  
- 📲 Alert system for nonprofits when meds become available  
- 📊 Analytics dashboards for usage insights  
- 🧱 Migrate to scalable PostgreSQL backend  
- ✅ Verification & incentives to improve listing quality  

---

## 📦 Getting Started  

### Requirements  
- Node.js & npm  
- Python 3.9+ and Flask  
- SQLite  

### Quick Setup  
