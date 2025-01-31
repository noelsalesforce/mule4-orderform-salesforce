# mule4-orderform-salesforce

### Order Form > IDP > Salesforce 
- Flow: Processes an order form pdf and updates the opportunity stage and fills out corresponding fields in the opportunity record if the total amount from the pdf matches the opportunity amount

### IDP Action
- Action Prompt: Extract all the keys and values from this order form in a json format. Format phone numbers in the (xxx)xxx-xxxx format. Format dates in the mm/dd/yyyy format. If it's a dollar value, just return the amount.  
<img width="861" alt="Screenshot 2025-01-31 at 1 28 10 PM" src="https://github.com/user-attachments/assets/dd2c8ff9-4147-4889-a0ea-1c6d4705a767" />

### Salesforce Connector operation
- Query
- Upsert
