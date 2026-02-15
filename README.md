# Civic Ease – Smart Civic Help Assistant  
### AI-Based Conversational Guide for Public Services & Government Support  

**Course:** Artificial Intelligence – Real-World Applications and Implications  
**Subject:** CRS – Artificial Intelligence  
**Student:** Aditya Jitendra Kumar Sahani  
**Grade:** 11  
**School:** Aspee Nutan Academy  
**Student ID:** 1000414  

---

## 1. Live Chatbot Access

Interact with the deployed Civic Ease Assistant here:

🔗 **[https://bot.dialogflow.com/628051f6-68ae-4ece-92a7-46606dde7ae8]**

---

## 2. Project Overview

**Civic Ease** is an AI-powered chatbot built using **Google Dialogflow ES** to simplify access to government and civic services. It acts as a 24/7 digital helpdesk for citizens by providing instant, clear, and structured information about public services, documentation, and local governance procedures.

The chatbot reduces confusion, long queues, and misinformation by guiding users step-by-step through common civic tasks.

This project meets the “Distinguished” rubric criteria by implementing **19 intents** and **10 custom entities**, including slot-filling and contextual conversations.

### It supports queries related to:

- Government Document Applications (Aadhar, PAN, Passport, Voter ID)
- Municipal Services (Water Bill, Property Tax, Garbage Complaints)
- Public Grievances & Complaints
- Traffic & Transport Services
- Electricity & Utility Payments
- Birth & Death Certificates
- Public Welfare Schemes
- Emergency Helplines
- Nearest Government Offices
- Online Service Portals

---

## 3. Target Users

| User Group | Purpose |
|------------|----------|
| Citizens | Quick access to public services |
| Senior Citizens | Simple step-by-step guidance |
| Students | Help with ID documents & certificates |
| Rural Users | Clear explanation of government schemes |
| Visitors / Migrants | Assistance with registrations & services |

---

## 4. Key AI Features & Design

- **Platform:** Developed using Google Dialogflow Essentials (ES)
- **Intent Recognition:** 19 distinct intents for different civic services
- **Entity Extraction:** 10 custom entities for structured data capture
- **Slot-Filling:** Collects required information before responding
- **Contextual Memory:** Supports follow-up questions in conversations
- **Rich Responses:** Suggestion chips and quick replies
- **Static Knowledge Base:** Structured government links and procedures

---

## 5. List of Intents (19 Total)

| Intent Name | Purpose |
|-------------|----------|
| Welcome | Greets the user |
| Fallback | Handles unknown queries |
| Goodbye | Ends session politely |
| Apply Document | Guides application for a document |
| Track Application | Provides tracking steps |
| Municipal Services | Information about civic services |
| Pay Utility Bill | Guides online bill payment |
| File Complaint | Helps file a civic complaint |
| Check Scheme Eligibility | Explains welfare schemes |
| Traffic Services | License and vehicle services |
| Nearest Office Location | Provides office details |
| Emergency Contacts | Police, ambulance, fire numbers |
| Birth/Death Certificate | Application procedure |
| Property Tax Info | Payment and due dates |
| Public Transport Info | Bus/metro guidance |
| Senior Citizen Services | Pension and welfare info |
| Digital Portal Help | How to use government portals |
| Required Documents Info | Lists required documents |
| Status & Deadlines | Processing time details |

---

## 6. List of Custom Entities (10 Total)

| Entity Name | Examples |
|-------------|----------|
| @doc_type | Aadhar, PAN, Passport, Voter ID |
| @service_type | water bill, electricity bill, property tax |
| @complaint_type | garbage issue, road damage |
| @scheme_type | scholarship, pension scheme |
| @transport_type | driving license, vehicle registration |
| @utility_type | electricity, water, gas |
| @office_type | municipal office, RTO |
| @application_stage | new, renewal, correction |
| @location_area | city name, ward number |
| @certificate_type | birth certificate, death certificate |

---

## 7. End-to-End Test Scenarios

### 1️⃣ New Applicant Scenario
Hi → How to apply for Passport? → What documents are required? → Where is the office? → Thanks!

### 2️⃣ Utility Payment Scenario
I want to pay electricity bill → Online → (Bot provides portal link)

### 3️⃣ Complaint Filing Scenario
There is a garbage problem → (Bot asks location) → Sector 5 → (Bot provides complaint link)

### 4️⃣ Scheme Eligibility Scenario
Am I eligible for pension? → (Bot explains criteria) → How to apply?

### 5️⃣ Emergency Scenario
Emergency help → (Bot provides emergency numbers)

---

## 8. Deployment Instructions

1. Open Dialogflow ES Console
2. Create a new agent named **Civic Ease**
3. Add all 19 intents and 10 entities
4. Configure slot-filling for required intents
5. Enable Web Demo Integration
6. Copy and share the generated link

---

## 9. Future Improvements

- Live Database Integration for real-time updates
- Multi-language Support (Hindi, Gujarati, etc.)
- Voice Input Integration
- Location Detection for personalized services
- WhatsApp or Telegram Integration

---

## License

This project is created for educational and academic submission purposes under the WACP AI coursework.
