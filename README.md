Metrocar Funnel Analysis

Overview

This project aims to analyze the customer funnel of Metrocar, a ride-sharing app (similar to Uber/Lyft), to identify areas for improvement and optimization within the user journey. Using SQL for data collection and Pandas for data analysis and visualization, we will explore the key stages of the customer funnel to uncover insights that will drive better business decisions. The primary goal is to address stakeholder questions, providing actionable recommendations based on the analysis.

🚗 About Metrocar

Metrocar operates as a platform that connects riders with drivers through a mobile application. Acting as an intermediary, Metrocar facilitates the ride-hailing process by offering a seamless, user-friendly interface for both riders and drivers.

Key Features:

	•	User-friendly mobile app: Metrocar enables users to request a ride by entering their location and destination.
	•	Driver network: Drivers accept ride requests and transport users to their destinations.
	•	Automatic payment: Users are charged automatically after the ride through the app.

📶 Metrocar’s Funnel

The customer funnel consists of several stages, each of which presents potential points of user drop-off. Analyzing these stages allows Metrocar to identify areas for improvement, optimize the user journey, and reduce churn. The main stages include:

	1.	App Download: A user downloads the Metrocar app from the App Store or Google Play Store.
	2.	Signup: The user creates an account, providing essential information (e.g., name, email, payment info).
	3.	Request Ride: The user opens the app, enters their pickup and destination, and requests a ride.
	4.	Driver Acceptance: A nearby driver receives the request and accepts it.
	5.	Ride: The driver picks up the user, who rides to their destination.
	6.	Payment: The fare is automatically charged, and a receipt is sent via email.
	7.	Review: The user rates the driver and may leave feedback on their ride experience.

Like any customer funnel, each stage can experience drop-offs, which can hinder the user from completing the entire process. For example, users may download the app but not complete the signup, or they may cancel rides before the driver arrives. Identifying these issues through funnel analysis can help us target key areas for improvement.

🔎 Business Questions

To provide insights and recommendations, the following business questions need to be addressed:

	1.	Funnel Optimization: Which stages of the funnel experience the highest drop-offs, and how can they be improved?
	2.	User Drop-off: Are there specific points where users fail to complete their first ride? What are the causes?
	3.	Platform Insights: Metrocar supports iOS, Android, and web. Based on platform performance, where should Metrocar allocate its marketing budget for the upcoming year?
	4.	Age Group Performance: How do different age groups perform at each funnel stage? Which age group(s) should Metrocar target as their primary customer base?
	5.	Surge Pricing Analysis: If Metrocar adopts surge pricing, how does ride request volume vary throughout the day, and when would surge pricing be most effective?
	6.	Conversion Rates: Which stage of the funnel has the lowest conversion rate, and what can be done to improve it?

🧑‍💻 The Dataset: This dataset is inspired by publicly available datasets for Uber/Lyft. The data for this dataset was generated specifically for this project. Connect to the Metrocar database

Copy the following URL to use with sqlalchemy and Pandas: postgresql://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar
