# wecord_flutter_Solution_challenge2020
!. Our solution mainly consists of a Flutter based mobile app. We wanted our solution to reach the masses, that's why we picked flutter as our framework of choice because of its cross-platform capabilities.

For the backend, we mostly relied on Firebase, as it was easier to integrate with the flutter app, without any hassle to manage & create instances of our server.

For sign-up & authentication, we used Firebase auth. If you're a medical volunteer, we'll ask you to upload an image of your medical ID card and we're using firebase ml kit for verification.

For storing the different types of data including user data, posts for the forum, ambulances, insights for the heatmap, doctors, appointments etc. we chose Cloud Firestore because of its robust features and ability to query & filter out documents with ease.

Screenshot 2022-03-30 184344

For verifying the medical volunteer ID Card Image, we used Firebase ML Kit, specifically the text recognition service.

To enable image posting in forums, and to store the volunteer image we used firebase cloud storage.

For handling payments, we used Razorpay SDK, which allowed us to accept payments for doctor appointment booking using Google Pay.

Adding video-calling for doctors and users was a challenging part, we ended up using agora WebRTC SDK to enable that feature within the app.

For the symptom-based disease recognition system, we looked up a lot for a reliable resource and ended up using prepaid service from ApiMedic.

For the Google Assistant Action, we used actions SDK with Google Actions builder tool, along with that for hosting an instance for webhooks, we used GCP.
