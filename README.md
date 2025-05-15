MedPal is a personal medical tracker that lets users manage their well-being online by helping them record and monitor their health particulars.
The vision behind MedPal is to empower everyone with full control over their medical data.

Follow these steps to set up the project on your local machine:

1. Navigate to the project directory
cd medpal
2. Install dependencies for both the frontend and backend
cd client
npm install
cd ../server
npm install
3. Create a .env file in the backend directory and add the following variables:
MONGODB_URI=<your_mongodb_connection_string>
PORT = <your_port_number>
SECRET = <for_bcrypt_hashing>

4. Start the frontend and backend servers in separate terminal windows
# In the frontend directory
npm start

# In the backend directory
npm run dev

Visit http://localhost:3000 to view the application in your browser.

Future Improvements
As we continue to develop and improve MedPal, here are some features and improvements we plan to add in the future:

Push notifications for mobile and browser to remind users of appointments, medicine refills, and other important events.
Port the application to a mobile app for more seamless integration with users' daily routines.
Add a "streaks" feature to keep users more engaged and motivated to maintain healthy habits.
Connect with more authentication services, such as Google and Facebook, to provide more options for users to log in.
Develop a business model that includes a Pro version with advanced features, as well as partnerships with healthcare providers and insurance companies.

We are always looking for feedback and suggestions from our users, so if you have any ideas or requests for future improvements, please don't hesitate to reach out to us!
