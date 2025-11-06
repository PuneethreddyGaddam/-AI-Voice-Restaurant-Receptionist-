# -AI-Voice-Restaurant-Receptionist-
AI-powered voice assistant for restaurants. Lets customers call to book a table or place a pickup order. Uses ElevenLabs voice agent + Make.com to collect details, save reservations to Google Calendar, and send confirmation emails. Helps restaurants respond faster and reduce missed calls.
# AI Voice Restaurant Receptionist

This project is an AI voice assistant made for restaurant use. Customers can call the AI and easily **book a table** or **place an order for pickup**. The goal is to help restaurants respond faster, reduce missed calls, and provide a smoother experience for guests.

The system uses an **ElevenLabs voice agent** to speak with customers and gather details like name, date, time, and number of people. All data is sent to **Make.com**, where it is processed. The booking is then added to **Google Calendar**, and the customer receives a confirmation email with the full details. Pickup orders can also be forwarded to the restaurant.

---

## ✅ Features

- AI voice answers customer calls  
- Takes reservations & pickup orders  
- Saves bookings to Google Calendar  
- Sends confirmation emails automatically  
- Uses EDT timezone for scheduling  
- No backend coding required — workflow built in Make.com  

---

## 🛠 Tech Stack

- ElevenLabs Voice Agent  
- Make.com  
- OpenAI (o4-mini)  
- Google Calendar  
- Gmail / Email  
- Webhooks  

---

## 📞 How It Works

1. Customer calls the AI  
2. ElevenLabs collects reservation or order details  
3. Data is sent to Make.com through webhook  
4. Date/time is formatted (EDT)  
5. System checks Google Calendar availability  
6. Booking is created if the slot is open  
7. Confirmation email is sent to customer  
8. AI replies to caller with the result  

---

## 📂 Files

- `Ai Voice Agent.blueprint.json`  
  → Make.com scenario blueprint  

---

## 📍 Restaurant Info

**Pakwan Indian Cuisine**  
7102 Abercorn Street  
Savannah, GA 31406  
📞 +1 (912) 349-4261  

---

## 🔗 Voice Agent Link

You can test the voice agent here:  
https://elevenlabs.io/app/talk-to?agent_id=agent_4501k81v340afew9z5bxyzr7xn0b

---

## ⚙️ Requirements

- ElevenLabs account  
- Make.com account  
- Google API access (Calendar + Gmail)  
- OpenAI API key  

---

## 🚀 Setup

1. Import the blueprint into Make.com  
2. Add your API keys (Google + OpenAI)  
3. Link ElevenLabs webhook to Make  
4. Update Calendar & Email modules  
5. Turn on scenario → done ✅  

---

## 🔮 Future Improvements

- Send reservation + pickup order details directly to **Clover kitchen printer**  
- Sync orders automatically with Clover POS  
- SMS confirmations + reminder notifications  
- Add order + reservation storage in Google Sheets  
- Multi-location support for restaurants  
- Support for cancellations & changes directly through AI  
- Send detailed order receipts via email or SMS  
- Add menu item upselling + special requests  



If you have any questions or want to improve this project, feel free to explore, fork, and build on top of it!
