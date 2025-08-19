🌍 Inspiration
Every year, billions of dollars in unused medications are discarded by:

Pharmacies

Hospitals

Nursing homes

Much of this waste happens simply because of expiration dates. In fact, hospitals alone discard over $800 million worth of usable drugs annually.

At the same time, 1 in 3 Americans skip prescribed medications due to cost. This highlights a serious problem of waste on one side and unmet medical need on the other.

MediBridge was created to bridge this gap.

💡 What It Does
MediBridge connects:

Pharmacies with excess or soon‑to‑expire medications that can be offered at steep discounts.

Nonprofits and clinics that serve vulnerable communities, including health centers, aid organizations, and shelters.

By redistributing surplus medicine, MediBridge reduces waste while improving affordability and access to essential drugs.

🛠️ How We Built It
Frontend: React, HTML, CSS, JavaScript, Tailwind CSS

Authentication: Google OAuth (secure login)

Mapping & Location Services: Mapbox API

Backend: Flask with multiple RESTful endpoints

Database: SQLite (for user, drug, and pharmacy data)

External API: NDC Directory API (for verified drug metadata)

⚙️ How It Works
Users log in via Google Authentication.

They select a role:

Pharmacy: List surplus medications (via NDC code, price, expiration date, etc.). Drug details auto‑populate from the NDC API.

Nonprofit: Search for needed medications and get listings prioritized by proximity.

All data is stored in a secure SQLite database and displayed in a searchable marketplace.

🚀 Features
✅ User authentication with Google OAuth
✅ Role‑based workflows (pharmacy vs nonprofit)
✅ Real‑time drug lookup via NDC Directory API
✅ Location‑based search and map integration with Mapbox
✅ Responsive UI powered by React + Tailwind CSS

🏆 Accomplishments We're Proud Of
Built and deployed a full‑stack web application in under hackathon time constraints.

Successfully integrated Google OAuth and Mapbox API.

Gained practical skills in frontend‑backend integration, session management, and database design.

Strong teamwork with fast adaptability under pressure.

📚 What We Learned
Best practices in Git/GitHub collaboration

End‑to‑end full‑stack debugging

Secure implementation of authentication workflows

Designing REST APIs for scalable integration

🔮 What's Next for MediBridge
We plan to expand the application with:

🔍 Advanced medication search (by radius, brand, dosage forms)

📬 Email/SMS alerts when medications of interest become available

📊 Analytics dashboards for nonprofits & pharmacies

🧱 Scalable backend upgrade to PostgreSQL with cloud deployment

✅ Pharmacy verification & incentive systems to encourage responsible listings
