

👵 CareMate - Elderly Care & Assistance Platform  

CareMate is a modern web application designed to connect elderly individuals with trusted caregivers and essential healthcare services.  
It combines location-based services, real-time emergency support, and interactive features to enhance safety, independence, and quality of life for the elderly.  

Live Demo: 👉 [Your Deployment Link Here]  

---

✨ Features  

CareMate delivers an all-in-one elderly care assistant experience:  

· 🗺️ **Caregiver Marketplace** – Browse, filter, and book caregivers by rating, experience, specialty, or proximity.  
· 📍 **Interactive Maps** – Powered by Leaflet.js & OpenStreetMap. Shows nearby hospitals, vaccination centers, and caregivers with custom emoji markers.  
· 🚨 **Emergency Services Locator** – Real-time hospital availability, AI-driven emergency response recommendations, and nearest service suggestions.  
· 💬 **Chatbot Assistant** – Integrated chatbot connected to a prompt generator for quick answers and guidance.  
· 📊 **Caregiver Profiles** – Detailed profiles with experience, specialties, ratings, and user reviews.  
· ✅ **Smart Booking Flow** – Pop-up confirmation with caregiver details and real-time booking acknowledgment.  




Screenshots attached:
<img width="1920" height="1080" alt="Screenshot (182)" src="https://github.com/user-attachments/assets/706df21f-4bcd-44c8-9df5-35e1fff16b64" />
<img width="1920" height="1080" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/d1d2ba41-d662-4e76-9cb4-12ce50747ce2" />
<img width="1920" height="1080" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/d1f80829-b717-465c-ac1f-959075f58f65" />
<img width="1920" height="1080" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/6f0c802e-cd7c-4d71-a16a-81836b870b22" />
<img width="1920" height="1080" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/d2afcb29-d066-46dc-93ed-84604cd0ef6e" />
<img width="1920" height="1080" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/7de039a3-c39a-4308-b4ec-255d8cf0da9e" />
<img width="1920" height="1080" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/50578c52-53b3-4636-b640-7c7526309f50" />
<img width="1920" height="1080" alt="Screenshot (180)" src="https://github.com/user-attachments/assets/52bcb1bb-79d6-4503-86b2-8b23f031c7bd" />
<img width="1920" height="1080" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/c18445d8-013e-4519-bd34-41edef8e5508" />



---

🛠️ Tech Stack  

· **Frontend**: HTML, CSS, JavaScript  
· **Mapping**: Leaflet.js + OpenStreetMap  
· **Backend**: Node.js, Express.js  
· **Database**: MySQL  
· **Real-Time Features**: Twilio API (video calls & chat)  
· **AI Integration**: Generative AI for chatbot support  
· **Deployment**: Vercel / Render / Railway / Your Hosting  

---

🚀 Getting Started  

Follow these steps to run CareMate locally:  

### Prerequisites  
· Node.js (v18 or higher)  
· MySQL (running locally or on cloud)  
· npm (comes with Node.js)  

### Installation  

1. Clone the repository:  
  
   git clone https://github.com/your-username/caremate.git


### 2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up the database:

   * Create a MySQL database named `elderly_care`.
   * Run the schema provided in `/db/sample_schema.sql`.

4. Configure environment variables:
   Create a `.env` file in the root directory with:

   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=yourpassword
   DB_NAME=elderly_care
   TWILIO_ACCOUNT_SID=your_twilio_sid
   TWILIO_AUTH_TOKEN=your_twilio_token
   GEMINI_API_KEY=your_generative_ai_key
   ```

5. Start the backend server:

   ```bash
   node routes/server.js
   ```

6. Open your browser:
   👉 [http://localhost:3000](http://localhost:3000)

---

📁 Project Structure

```
caremate/
├── public/                 # Static assets (HTML, images, icons)
│   └── index.html
├── src/                    # Frontend source code
│   ├── components/         # Reusable UI components
│   ├── App.jsx             # Root component
│   └── main.jsx            # React entry point
├── routes/                 # Express routes & API logic
│   └── server.js
├── db/                     # Database schemas & queries
│   └── sample_schema.sql
├── package.json            # Project metadata & dependencies
└── README.md               # Documentation
```

---

🧩 Key Implementation Highlights

* **Custom Emoji Markers** for caregivers, hospitals, and vaccination centers on maps.
* **AI-driven Emergency Recommendations** that adapt to real-time availability.
* **Secure Twilio Video Calls** for caregiver-patient communication.
* **Dynamic Filtering** for caregivers (distance, experience, specialty, rating).
* **Booking Confirmation Flow** with real-time updates.

---

🔮 Future Enhancements

· Integrate wearable/IoT health data into the dashboard.
· Add multilingual support for wider accessibility.
· Expand booking with automated caregiver matching.
· Build a mobile-first PWA for offline reminders & emergency access.

---

📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the **Issues** page and submit a PR.

---

📧 Contact

**Saloni More** – [msaloni1412@gmail.com](mailto:msaloni1412@gmail.com)




