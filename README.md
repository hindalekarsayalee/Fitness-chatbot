# AI Fitness Chatbot 💪🤖

A web-based AI-powered chatbot that helps users with fitness guidance, workout routines, diet plans, and motivational quotes through a conversational interface using **IBM Watsonx Assistant**.

---

## 💡 Project Overview

This chatbot acts as a **Fitness Buddy**, allowing users to interact naturally and get personalized suggestions for:
- Diet plans (e.g., weight loss, muscle gain)
- Workout routines (e.g., cardio, yoga, strength training)
- Motivational support
- Progress tracking

Built using:
- **IBM Watsonx Assistant** (for chatbot logic and natural language understanding)
- **HTML + CSS** (for UI)
- Optionally **JavaScript** (for enhanced integration if needed)

---

## 🛠️ Features

- 🔸 Friendly Welcome Interaction  
- 🔸 Smart Diet Plan Suggestions based on goals and diet types  
- 🔸 Tailored Workout Routines (yoga, cardio, etc.)  
- 🔸 Daily Motivation Quotes  
- 🔸 Track Fitness Progress  
- 🔸 Clean and Responsive Web Interface  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   https://github.com/hindalekarsayalee/Fitness-chatbot

2. Open index.html in a browser.

Make sure your Watsonx Assistant is integrated properly:

3. Replace the integration script (in index.html) with your Watson Assistant Embed Code.

- The embed code looks like:

html Copy Edit
<script>
  window.watsonAssistantChatOptions = {
    integrationID: "your-integration-id", 
    region: "your-region", 
    serviceInstanceID: "your-instance-id", 
    onLoad: function(instance) { instance.render(); }
  };
  setTimeout(function() {
    const t = document.createElement('script');
    t.src = "https://web-chat.global.assistant.watson.appdomain.cloud/versions/latest/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
Deploy the page on GitHub Pages or any static hosting platform.

- Screenshot - 

<img width="1912" height="924" alt="Screenshot 2025-08-03 014356" src="https://github.com/user-attachments/assets/384cf60a-31ec-4f81-892b-ad37eea3a258" />

<img width="1919" height="882" alt="Screenshot 2025-08-03 014925" src="https://github.com/user-attachments/assets/ed6639de-66bd-4381-9116-ad6f6caae295" />

- Technologies Used
Layer	Technology
Chat Logic	IBM Watsonx Assistant
UI / Frontend	HTML, CSS
Optional Enhancements	JavaScript
Hosting	GitHub Pages / Local

- Future Scope - 
Add voice interaction support

Track fitness progress over time

Use backend to store user data

Integration with fitness APIs (calorie tracker, steps tracker, etc.)

- Acknowledgment - 
IBM Watsonx Assistant

YouTube tutorial: Fitness Chatbot using Watsonx Assistant

- References - 
IBM Watsonx Assistant Documentation

HTML/CSS Basics

GitHub Pages Deployment Guide
