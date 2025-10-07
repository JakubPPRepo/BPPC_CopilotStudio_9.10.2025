How to register Copilot connector from ServiceNow "Application Registries"

ServiceNow part:



1. Navigate to "Application Registries" and click on "New"
  <img width="1873" height="379" alt="image" src="https://github.com/user-attachments/assets/54710b24-8a55-4020-a75a-a77ee23b978f" />

2. Select "Create an OAuth API endpoint for external clients":
  <img width="709" height="260" alt="image" src="https://github.com/user-attachments/assets/fc33cc71-4ad3-4b12-a046-6c459ce8ca4c" />

3.Now it's time to fill the highlated fields:
  - Name
  - Redirect URL: https://global.consent.azure-apim.net/redirect
  - Then click on Submit button
  <img width="1134" height="394" alt="image" src="https://github.com/user-attachments/assets/22b490ee-ea76-4548-9cf4-67e124538a57" />

4. Select your new created connection from list, now we can see there is client secret- now we're ready to jump to Copilot Studio
   <img width="509" height="203" alt="image" src="https://github.com/user-attachments/assets/58d690a7-2795-4ef6-b2ee-fbd0e9c9f9e2" />



Copilot Studio part:
1. Jump to your Copilot Agent, then go to Knwoledge tab:
  <img width="884" height="697" alt="image" src="https://github.com/user-attachments/assets/5cba8718-fb3c-4e75-9539-f7c060a9a8cb" />

2. Select ServiceNow connector:
   <img width="1004" height="531" alt="image" src="https://github.com/user-attachments/assets/dbacbd79-11f7-45b2-8864-3c8b0d219ecc" />

3. Choose "Create new connection":
   <img width="356" height="254" alt="image" src="https://github.com/user-attachments/assets/070f4031-913f-4f7d-92a3-7b28414fab88" />

4. Fill all 3 mandatory fields:
     - Instance Name - it's your dev.....// find it on https://developer.servicenow.com/
     - Client Id & Client secret- take it from here:
       <img width="532" height="132" alt="image" src="https://github.com/user-attachments/assets/bfe76794-0a5c-4df5-8e08-99afce8d30e5" />

       







