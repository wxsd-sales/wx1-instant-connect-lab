# Backend Preparation

One of the objectives of this lab is to demonstrate how Webex Connect can retrieve and update relevant business information from backend systems such as databases, CRMs or EMRs.

Let's set this up using mockAPI.io:

## Create a new Project

1. Open a browser and navigate to: https://mockapi.io

   Sign-in/sign-up as needed to log in.

1. Select **New Project**:

   ![New Project](images/new_project.png)

   and give it a name, for example: `My First Project`
   
   You can leave the **API Prefix** blank:

   !![Project Name](images/project_name.png)

## Create a New resource

1. Choose **New Resource**, and give it a name of your choice:

   ![New Resource](images/new_resource.png)

1. Fill in the **Schema** section as shown below:


   ![Resource Schema](images/resource_schema.png)

1. Click on **Create**.

## Populate database records

You can ask mockAPI to create sample data automatically.

1. Select the gray bar under your resource and drag to indicate how many records you would like created.  Select something close to: `20`

   ![Sample Data](images/sample_data.png)

1. Click on **Data**.

   You will see all the records that have been created. 
   
1. For this lab, you need to update the first record with the WhatsApp mobile number you will use later, here's an example:

   ```js
   {
       "name": "Lab Customer",
       "avatar": "https://cloudflare-ipfs.com/ipfs/Qmd3W5DuhgHirLHGVixi6V76LhCkZUz6pnFt5AJBiyvHye/avatar/465.jpg",
       "mobileNumber": "34639793462",
       "address": "01490 Edna Bridge",
       "city": "Barcelona",
       "country": "Spain",
       "email": "labcustomer@domain.com",
       "videoCallScheduled": false,
       "id": "1"
   }
   ```
   **IMPORTANT**: `mobileNumber` must include country code, and must **NOT** include '`+`'

1. Click on the small resource name link:

   ![Endpoint API](images/endpoint_api.png)

   This will open a browser tab and display the returned JSON data from your mock API resource.

   Note the URL, as this is the **Endpoint API** that you will use later in the lab.
   
   It should look something like:
   
   `https://xxxxxxxxxxxxxxxxxxxxxxxx.mockapi.io/ciscoliveEMEA2024`



















