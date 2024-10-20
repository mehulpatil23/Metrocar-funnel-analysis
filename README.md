Metrocar-funnel-analysis:
This project aims to analyze the customer funnel of Metrocar, a ride-sharing app (similar to Uber/Lyft), to identify areas for improvement and optimization. We will use SQL for data collection and Pandas for further analysis and visualisation. The stakeholders have asked several business questions that can uncover valuable insights for improving specific areas of the customer funnel. Your task is to conduct a funnel analysis and present your analysis and recommendation. Explain your reason for your recommendation based on insights retrieved from the data. 

🚗 About Metrocar:
Metrocar's business model is based on a platform that connects riders with drivers through a mobile application. Metrocar acts as an intermediary between riders and drivers, providing a user-friendly platform to connect them and facilitate the ride-hailing process.

📶 Metrocar’s Funnel:
The customer funnel for Metrocar typically includes the following stages:
App Download: A user downloads the Metrocar app from the App Store or Google Play Store.
Signup: The user creates an account in the Metrocar app, including their name, email, phone number, and payment information.
Request Ride: The user opens the app and requests a ride by entering their pickup location, destination, and ride capacity (2 to 6 riders).
Driver Acceptance: A nearby driver receives the ride request and accepts the ride.
Ride: The driver arrives at the pickup location, and the user gets in the car and rides to their destination.
Payment: After the ride, the user is charged automatically through the app, and a receipt is sent to their email.
Review: The user is prompted to rate their driver and leave a review of their ride experience.
Similar to other customer funnels, there will be drop-offs at every stage of the funnel, which is why funnel analysis can be helpful in identifying areas for improvement and optimization. For example, Metrocar may analyze the percentage of users who download the app but do not complete the registration process, or the percentage of users who request a ride but cancel before the driver arrives.
 
🔎 Business questions:
You will need to analyze the data and make recommendations based on the following business questions:
What steps of the funnel should we research and improve? Are there any specific drop-off points preventing users from completing their first ride?
Metrocar currently supports 3 different platforms: ios, android, and web. To recommend where to focus our marketing budget for the upcoming year, what insights can we make based on the platform?
What age groups perform best at each stage of our funnel? Which age group(s) likely contain our target customers?
Surge pricing is the practice of increasing the price of goods or services when there is the greatest demand for them. If we want to adopt a price-surging strategy, what does the distribution of ride requests look like throughout the day?
What part of our funnel has the lowest conversion rate? What can we do to improve this part of the funnel?

🧑‍💻 The Dataset:
This dataset is inspired by publicly available datasets for Uber/Lyft. The data for this dataset was generated specifically for this project.
Connect to the Metrocar database

Copy the following URL to use with sqlalchemy and Pandas:
postgresql://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar
