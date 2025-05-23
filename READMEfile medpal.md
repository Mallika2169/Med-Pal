<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://med-pal.vercel.app">
    <img src="https://ik.imagekit.io/spursy/MedPal/apple-touch-icon.png?updatedAt=1681674938894" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">MedPal</h3>
</div>



MedPal is a personal medical tracker that lets users manage their well-being online by helping them record and monitor their health particulars. The vision behind MedPal is to empower everyone with full control over their medical data.


## Features

- View everything MedPal has to offer collectively in our dashboard<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/MainDashboard.png?updatedAt=1682356243714" alt="Dashboard"/><br/><br/>
- Store and analyze lab vitals in charts for easy insights 📊<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/Charts.png?updatedAt=1682356243168" alt="Charts"/><br/><br/>
- Manage medicine inventory and get daily reminders 💊<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/MedicineManager.png?updatedAt=1682356243236" alt="MedicineManager"/><br/><br/>
- Securely store and access lab reports and prescriptions with web viewer 🗊<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/ReportsViewer.png?updatedAt=1682356243712" alt="ReportsViewer"/><br/><br/>
- Keep track of medical appointments with the integrated calendar 📅<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/AppointmentPage.png?updatedAt=1682356243491" alt="AppointmentPage"/><br/><br/>
- Search for nearby doctors using geolocation 👨‍⚕️<br/><br/>
<img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/DoctorSearch.png?updatedAt=1682356243220" alt="DoctorSearch"/><br/><br/>
- Responsive design for seamless experience on mobile devices 📱<br/><br/>
<p align="center"><img src="https://ik.imagekit.io/spursy/MedPal/Github_Readme/ResponsiveMobile.jpg?updatedAt=1682356243154" alt="ResponsiveMobile"/></p><br/><br/>

## Tech Stack

- <img height="20" src="https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37f-bf92061753e5.png" alt="React" title="React" /><img height="22" src="https://user-images.githubusercontent.com/25181517/183898054-b3d693d4-dafb-4808-a509-bab54cf5de34.png" alt="Bootstrap" title="Bootstrap" /> React with Bootstrap (Front-end)
- <img height="22" src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png" alt="Node.js" title="Node.js" /><img height="22" src="https://user-images.githubusercontent.com/25181517/183859966-a3462d8d-1bc7-4880-b353-e2cbed900ed6.png" alt="Express" title="Express" /> Express and Node.js (Back-end)
- <img height="22" src="https://user-images.githubusercontent.com/25181517/182884177-d48a8579-2cd0-447a-b9a6-ffc7cb02560e.png" alt="mongoDB" title="mongoDB" /> MongoDB (Database)
- <img height="22" src="https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png" alt="Postman" title="Postman" /> Postman (API Testing)
- <img height="22" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code" /> VS Code (Code editor)

## Getting Started

Follow these steps to set up the project on your local machine:


1. Navigate to the project directory

```
cd medpal
```

2. Install dependencies for both the frontend and backend

```
cd client
npm install
cd ../server
npm install
```

3. Create a `.env` file in the backend directory and add the following variables:

```
MONGODB_URI=<your_mongodb_connection_string>
PORT = <your_port_number>
SECRET = <for_bcrypt_hashing>
```

4. Start the frontend and backend servers in separate terminal windows

```
# In the frontend directory
npm start

# In the backend directory
npm run dev
```

Visit `http://localhost:3000` to view the application in your browser.

## Future Improvements
As we continue to develop and improve MedPal, here are some features and improvements we plan to add in the future:
- Push notifications for mobile and browser to remind users of appointments, medicine refills, and other important events.
- Port the application to a mobile app for more seamless integration with users' daily routines.
- Add a "streaks" feature to keep users more engaged and motivated to maintain healthy habits.
- Connect with more authentication services, such as Google and Facebook, to provide more options for users to log in.
- Develop a business model that includes a Pro version with advanced features, as well as partnerships with healthcare providers and insurance companies.

We are always looking for feedback and suggestions from our users, so if you have any ideas or requests for future improvements, please don't hesitate to reach out to us!