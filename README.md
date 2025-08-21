# 🛠️ Workshop Reminder Automation with n8n  

This workflow automates sending **workshop confirmation emails** and **reminder emails** using **n8n** and **Google Sheets**.  

---

## 🔗 Workflow Steps:
1. **Google Sheet Trigger** → Detects new registration or row update.  
2. **Get Rows** → Retrieves participant details (Name, Workshop, Date, Time, Meeting Link, Materials).  
3. **Send Confirmation Email** → Sends immediate confirmation email upon registration.  
4. **IF Node (Date Check)** → Compares the current time with the reminder time (e.g., 5 hours before the workshop).  
5. **Send Reminder Email** → If the condition is met, sends a reminder email with all details and links.  

---

## ✉️ Email Templates:
- **Confirmation Email** → Sent instantly after registration.  
- **Reminder Email** → Sent 5 hours before the workshop.  

---

## ✅ Benefits:
- Fully automated email communication.  
- Reduced manual effort for workshop organizers.  
- Personalized emails with workshop details.  
