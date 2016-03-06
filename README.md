# Vitality - Fitness and Health App 

The application will track activity level, food consumption and calorie flow of the user daily, with capability to predict healthy level of calorie consumption patterns and produce trends of the user life style.

The software application will have a web based backend developed in python, using Django framework, while utilizing mongo DB for data storage. The scope of this project will cover the backend wed application development and data analysis used to infer user consumption patterns. Depending on the time frame, a PhoneGap based client-side interface would be developed to obtain further biodata (i.e accelerometer , IR sensors to track motion and heartrate respectively).

    Product Perspective

Vitality is a web based fitness and health tracker with a database to track user fitness and health data over time across multiple users. The product is extendable to extract client data via a smart phone. The base product will enable user to input data via web browser. 

    Product Functions

The Service enables each user to track daily health habits in the form of Activity Level, Food intake & Water intake by providing a daily diary to enter each user data. The data will then be utilized to identify calorie consumption over the day and check if the user is achieving the daily goals set by the user. The application has a portal to check Body-Mass-Index and Body-Fat-Percentage, thereby providing the ideal physical conditions user should be targeting. These ideal states will then be cascaded to the user in the form of predictions, providing user the ideal calorie intake and exercise calorie output required by the user.
Vitality will utilize an editable food dictionary and exercise dictionary with auto search functionality to input daily data.
User data collected over time will be viewed in graph format against the target level daily, weekly, monthly based on the collection of data. Predictions will be made based on the collection of data for the user to achieve optimum fitness level. ( E.g. If user is not achieving water intake goal, display a TIP to drink more water. If the user is not burning the required level of calories based on BMI, display a REMINDER for the user to workout and suggest a suited workout for the required burnout level.)

    Functional Requirements

> Vitality Web Application
   Vitality web app requires the following user data to be provided for full functionality.

      >  Activity Level – Selected from a number of exercises in the exercise dictionary, or as a new entry added to the exercise dictionary
      > Food Intake – Selected from a number of food items in the food dictionary, or as a new entry added to food dictionary
      > Water Intake – Given as the number of glasses of water consumed. The volume of the glass can be specified and amended as a configuration detail
      > User measurements – User weight, age, height, neck/ waist/ hip perimeter is required to calculate BMI and Body Fat percentage

    Vitality web app will provide the following outputs based on input data.
      > Daily Calorie balance – Given in equation format in the dashboard summary
      > Summary Graphs - Daily/ Weekly/ Monthly trend of user activity/ food intake/ water intake levels given in the format of graphs with goal levels given as reference
      > Daily Tips – Generated based on input data to enhance user health and fitness.

>PhoneGap Mobile app
    Vitality Mobile app will collect data from the mobile phone’s different sensors and infer the following details

      > User physical activity level (Running/ Walking/ Resting/ Sleeping) - Gyroscope/ Compass / Accelerometer / GPS
      > Transportation Mode – Gyroscope/ GPS / Wifi
      > Stress Level – Microphone (speaker dominance)

> Backend Python processing
    The application backend will utilize collected user data to infer the following data

      > Patterns in user activity through the week / month – Most active day/ Least active day
      > Patterns in water /food intake throughout the week – Unhealthy food intake probability for day
      > Changes in user anatomy – by weight & waist / neck/ hip measurements , identify user’s figure changes.


For More information - Refer - System Specification @ Github Link
