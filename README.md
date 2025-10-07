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

4. Choose "Create new connection":
   
   <img width="356" height="254" alt="image" src="https://github.com/user-attachments/assets/070f4031-913f-4f7d-92a3-7b28414fab88" />

5. Fill all 3 mandatory fields:
     - Instance Name - it's your dev.....// find it on https://developer.servicenow.com/
     - Client Id & Client secret- take it from here:
       
       <img width="532" height="132" alt="image" src="https://github.com/user-attachments/assets/bfe76794-0a5c-4df5-8e08-99afce8d30e5" />

       

6. Click "Connect" button, then we should see a following pop-up:
   
   <img width="604" height="677" alt="image" src="https://github.com/user-attachments/assets/4feec80b-28f0-4bc2-a7dd-3355fee75501" />

7. No worries, now let's look at the link:
   
    <img width="574" height="69" alt="image" src="https://github.com/user-attachments/assets/313720c9-df0f-4ea2-8d08-d444e26bf25a" />
    
8. Now we know that unitedstates-002 is our redirect_uri- that's why we need to update this parameter in ServiceNow:

       <img width="406" height="54" alt="image" src="https://github.com/user-attachments/assets/70026ff6-e765-4100-a234-9c9c98dcc7da" />


9. After click on "Update" in ServiceNow, get back to CopilotStudio, try once again:
    If you update the connector in ServiceNow without errors, the login window should look like this:
   
       <img width="595" height="667" alt="image" src="https://github.com/user-attachments/assets/90489239-92d4-4d6a-a686-93e6ee14c155" />

11. Login with your login and password to development instance
12. In last step you can add the tables that you want use further in topics:

        <img width="994" height="739" alt="image" src="https://github.com/user-attachments/assets/692ea95b-00a5-431c-be5f-c5c3b5e1ae87" />


    

   





