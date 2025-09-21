# Integration and Automation Flow: Shopify → Zapier → Keap

---

## 📌 Project Description

This project demonstrates an **automation flow between Shopify, Zapier, and Keap (formerly Infusionsoft)** to streamline eCommerce operations. It captures Shopify purchase events, passes them through **Zapier Zaps**, and syncs customer/order data into **Keap CRM** for automation, tagging, and follow-up sequences.  

---

## ⚙️ Tools and Platforms Used

- **Shopify** → eCommerce store, product orders, and customer data.  
- **Zapier** → Middleware automation platform connecting Shopify and Keap.  
- **Keap (Infusionsoft)** → CRM system for customer records, tagging, and automation workflows.  

---

## 🔄 Integration Workflow

1. **Customer Purchase in Shopify**  
   - Triggers a Shopify event (new order, subscription, or product purchase).  

2. **Zapier Automation**  
   - Zapier captures the order event.  
   - Key data extracted: customer email, product purchased, subscription info.  
   - Data is transformed and mapped to Keap fields.  

3. **Keap CRM Actions**  
   - Customer is created or updated in Keap.  
   - Appropriate tags applied (e.g., *New Customer*, *Subscribed to X Product*).  
   - Automation campaigns triggered (emails, onboarding sequences, reminders).  

---

## 📸 Screenshots & Walkthrough

### Zapier Setup
![Zapier Setup](https://i.imgur.com/wdl2uPD.png)

### Shopify → Zapier Trigger
![Shopify Trigger](https://i.imgur.com/LVpNUOF.png)

### Keap → Zapier Action
![Keap Record](https://i.imgur.com/NMH9BjI.png)

### Keap Automation Setup (Edit view)
![Keap Automation Edit](https://i.imgur.com/OOdJWYe.png)

### Keap Automation Setup (Reporting view)
![Keap Automation Reporting](https://i.imgur.com/WiRddtj.png)

---

## ✅ Key Benefits

- Automated customer syncing between **Shopify** and **Keap**.  
- Eliminates manual data entry.  
- Ensures customers are enrolled in the right campaigns immediately.  
- Scalable for subscriptions, one-time products, and upsells.  

---

## 🚀 How to Reproduce

1. Set up a **Shopify store** with at least one product.  
2. Create a **Zapier account** and connect Shopify + Keap.  
3. Build a Zap:  
   - **Trigger** → "New Order in Shopify"  
   - **Action** → "Create/Update Contact in Keap"  
4. Map Shopify order fields (email, name, product) to Keap fields.  
5. Test the Zap and confirm data flows into Keap correctly.  
6. Set up **Keap automation campaigns** (e.g., onboarding, follow-up, reminders).  

---

✨ *This project is part of my Marketing Technology portfolio, showcasing real-world CRM automation use cases.*  
