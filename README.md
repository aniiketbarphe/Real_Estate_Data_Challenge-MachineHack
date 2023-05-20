![The-Great-Real-Estate-Data-Challenge(1)](https://github.com/aniiketbarphe/Real_Estate_Data_Challenge-MachineHack/assets/84449238/8a9e9433-ea61-424c-80e3-0fb59a71b459)

# Real_Estate_Data_Challenge-MachineHack

🏆 Ready to compete and showcase your data science skills? Join our weekly championship on Machine Hack and participate in the "The Great Real Estate Data Challenge"! 

Suppose there is an investment fund planning to invest in properties at hundreds of locations. 🏠 Based on the previous millions of property sales over the past few years, the fund house wants to identify the property which can result in a higher gain on investment. 💰 They can not go by analyzing all the properties one by one. 🤔 So they want the segmentation of properties so that they can look into their target segments. 🎯 So this challenge is going to help them by easily identifying their target properties using advanced AI and Analytics. 🔍

In the first week, you will receive a dataset of real estate properties with locality, estimated price, and selling price for the last 23 years. 📊 The task is to identify the input features in the dataset and use them to predict the sale price of a property. 🔮 After this modelling of input and output features, predict the sale price of all the properties in the test dataset. 💵 Once the sale prices for the test data are predicted, put these properties into 4 segments. 🔢 These segments can be formed according to the gain. 💹 The gain is calculated based on the estimated price and predicted sale price (Gain = (Sale price - Estimated price)/100).

Finally, you need to submit your results as the segment level for each of the properties given in the test data. 📝 For reference, the properties need to be segmented into the following 4 segments according to the gain calculated based on the predicted sale:-

0: Premium Properties 💰🏰
1: Valuable Properties 💎🏡
2: Standard Properties 🏘️💸
3: Budget Properties  🏠💵
This exciting competition 🏆is divided into three rounds to test your knowledge and expertise.

🔍 Round 1: Participants will take an MCQ test to demonstrate their basic understanding of data science and machine learning.

💻 Round 2: Participants will solve small coding problems to showcase their coding skills.

🔥 Round 3: In the final round, participants will take part in the hackathon where they will receive the actual dataset and build models to solve the given problem. This round will showcase their problem-solving skills using machine learning and data analytics.

Join us for this thrilling competition and stand a chance to win exciting prizes!

Train: 553952  × 11
Test: 43954 × 12
 

Target

Segment: It is a categorical feature which is encoded based on the forecast. There are four segments.
Segment 0 (Premium Properties): The segment likely includes high-end properties with large square footage, modern amenities, and upscale finishes.
Segment 1 (Valuable Properties): The segment likely includes smaller apartments that are more affordable for people on a budget.
Segment 2 (Standard Properties): The segment likely includes smaller homes that are affordable for first-time homebuyers.
Segment 3 (Budget Properties): The segment likely includes properties that need some work or repairs to be fully functional.
Sale Price: The actual price at which the property was sold, which may be higher or lower than the estimated value.
Input features

Year: The year in which the property was sold or valued.
Date: The date on which the property was sold or valued.
Locality: The name of the town where the property is located.
Address: The complete address of the property.
Estimated Value: The estimated market value of the property, which is based on factors such as its location, size, and condition.
Property: A categorical feature indicating the type of property. There are six different categories.
Condo
Single-Family
Three Family
Two Family
Four Family
Residential
Residential: A categorical feature which further explains the category in which a certain property falls. There are five different types of categories.
Condominium
Detached House
Triplex
Duplex
Fourplex
num_rooms: A numerical feature which defines the number of rooms (e.g. bedrooms, living rooms, etc.) in the property.
carpet_area: The carpet area of the property, refers to the area of the floor that could be used for the flooring.
property_tax_rate: The rate at which property taxes are assessed on the property, which may vary based on its location and year.

What is the Metric In this competition? How is the Leaderboard Calculated?
The submission will be evaluated using the accuracy metric.
