# Farmer-Empowerment-Platform-with-AI-Driven-Insights

## 💥 Introduction

With a variety of features and services to improve agricultural operations, the planned site seeks to give farmers a comprehensive and integrated platform. It tackles the difficulties farmers encounter while trying to find information and services on schemes, land information, APMC marketplaces, and intelligent farming methods across a variety of platforms. The site expedites access to critical data, including scheme notifications, land details, and APMC history, and streamlines procedures like loan and insurance application by giving each farmer a unique ID and centralizing information.

Additionally, the portal has smart farming features that use artificial intelligence, machine learning, and the internet of things to help farmers with weather forecasting, disease detection, crop recommendations, and yield prediction. The portal has the capacity to reliably forecast future events by utilizing gathered farmer data, which might provide farmers with useful information and tools to enhance agricultural performance and decision-making.

For the front end, it is developed with React; for SMS service and communication, it uses Express, Sockets Server, and Twilio; for the database, it uses MongoDB; and machine learning methods are used for crop forecast, illness detection, and crop recommendation.

## 💡 Why did I build this?

The portal was developed to help farmers overcome the difficulties they encounter in gaining access to essential agricultural services and information. By offering a centralized platform with a distinct farmer ID for accessing schemes, land details, APMC history, and smart farming capabilities, it seeks to expedite decision-making. Enhancing decision-making, providing farmers with useful insights, and improving overall agricultural results are the objectives.

## 🛠️ Local development

That's pretty easy. To ensure that you are able to install everything properly, we would recommend you to have <b>Git</b>, <b>NPM</b> and <b>Node.js</b> installed.

We will first start with setting up the Local Project Environment:

```sh
git clone https://github.com/SharonCoutinho14/Farmer-Empowerment-Platform-with-AI-Driven-Insights
cd Farmer-Empowerment-Platform-with-AI-Driven-Insights
npm run install
```
Now we will add the environment variables in the client/ and server/

**Client**
```sh
cd client
npm install
npm start
```
For server setup, you need to add your MongoDB database URL to /config/mongoose.js.

**Server**
```sh
cd server
npm install
npm start
```

## 🛠️ Features of growfarm

Farmers' digital profiles: Each farmer receives a unique farmer ID after registering on growfarm. Farmer ID assists farmers in obtaining all of their personal data, including farm details, eligibility for schemes, application history for schemes, billing history, loan history, and insurance history.

• **Smart farming (Crop recommendation system):** A farm can receive recommendations for crop seeding based on soil factors such as nitrogen, phosphorus, potassium, and other specifics.

• **Whether broadcast and alert:** Broadcasting and informing farmers of impending poor weather might give them crucial knowledge that will enable them to safeguard their livelihoods and make educated decisions about their farming techniques.

• **Alert and update of new schemes and subsidies:** Farmers may stay informed and take advantage of opportunities by receiving notifications and updates on new schemes and subsidies. This can lead to increased agricultural output, better financial results, and more economic stability for farmers and their communities.

• **Schemes:** Farmers can choose the program they want to apply for and complete the required information using the system's user-friendly interface. Additionally, real-time updates on the application's status and any other pertinent information will be sent via the platform.

• **APMC billing history:** Farmers won't need to keep manual records because they can simply follow their sales and payment history thanks to the digital billing history. Additionally, this functionality will increase accountability and transparency throughout the agricultural supply chain, which will make it simpler to spot any potential problems or anomalies.

• **Farm information:** Once the famer's adhar details have been verified, they can see their farm information on their profile page from ANY ROR. The farmer doesn't need to go to any other gateway after that. They access all information through a single gateway.

## 🧾 Class Diagram

![Class diagram](https://user-images.githubusercontent.com/83646676/227933827-aa99f4fa-dd6e-4195-9757-63b6fdb0257c.png)

## 🧾 ER diagram of farmer portal:

![Farmer portal ER Diagram](https://user-images.githubusercontent.com/83646676/227935603-30440d00-b4b6-417d-8726-2195d0c5ea90.png)

## 🧾 ER diagram of government portal:

![Government portal Er Diagram](https://user-images.githubusercontent.com/83646676/227935683-71373929-2e04-4ba3-b89a-002742eff438.png)

## 💻 Interface design of farmer portal:

### Farmer’s registration form

![Registration](https://user-images.githubusercontent.com/83646676/227987002-147bcf12-5d1a-431a-bad8-9f1df7049864.png)

###  Farmer’s profile page

![FPP](https://user-images.githubusercontent.com/83646676/227987187-29cc2ca0-8526-45dd-bb5e-085bd5932287.png)

### Hourly Weather forecast

![HWF](https://user-images.githubusercontent.com/83646676/227987425-616763f5-ade8-47fe-8a37-9eea8f0ea92d.png)

### APMC billing history at farmer side

![APMC](https://user-images.githubusercontent.com/83646676/227987902-e30ed926-316c-4a10-90c5-65f7f5bbd97c.png)

### dashboard to analysis category wise registered farmers 

![dacwrf](https://user-images.githubusercontent.com/83646676/227988066-48f01abe-9ddc-4ad9-8c24-87fbfd22fc5d.png)

### Find farmer functionality 

![FFf](https://user-images.githubusercontent.com/83646676/227988262-3f58415e-3628-4559-8146-cea0f4eeee58.png)

### Admin side scheme dashboard

![Assd](https://user-images.githubusercontent.com/83646676/227988511-97d3a365-4898-4f94-8bba-555c247a8a40.png)

### Analysis dashboard for particular scheme 

![adfps](https://user-images.githubusercontent.com/83646676/227989156-eaf1e61a-bb40-4dbf-9590-ac39c10ce2b7.png)

### District wise soil analysis 

![DWSA](https://user-images.githubusercontent.com/83646676/227989307-62233f61-dea6-4766-baa7-902c2d74a4c2.png)

### Crop wise area, production and yield analysis 

![CWAPAYA](https://user-images.githubusercontent.com/83646676/227989974-7d4abb1a-8cb1-4c44-afdf-573b84691caa.png)

### Trader side digital bill generator 

![TSDBG](https://user-images.githubusercontent.com/83646676/227990534-78b3f3ce-5795-4f1b-a3c9-02c9de0826b7.png)


### Digital billing history

![Dhh](https://user-images.githubusercontent.com/83646676/227990730-0ec07b40-c74e-455f-9637-d7ac4406fbf8.png)


## 🎬Video demo of Growfarm Ui


https://user-images.githubusercontent.com/83646676/227994431-19456186-d09d-4b97-bc8a-d9c06d3121a7.mp4



https://user-images.githubusercontent.com/83646676/227994493-75e03a9d-4ff7-430f-9019-70d95f614eda.mp4



https://user-images.githubusercontent.com/83646676/227994504-b990925b-2561-4db5-8b1b-ee7792cedc0f.mp4



https://user-images.githubusercontent.com/83646676/227994510-20b4a2d4-59c5-435a-a285-571e75fbd67f.mp4



https://user-images.githubusercontent.com/83646676/227994525-c63d7e5e-6aa3-41aa-855b-f0cfb350f7ea.mp4



https://user-images.githubusercontent.com/83646676/227994536-026f6a4b-ffc6-406e-94b7-ab215755f04f.mp4



https://user-images.githubusercontent.com/83646676/227994553-cc59698a-cd75-4ec5-bd1f-5e0456d3a210.mp4



