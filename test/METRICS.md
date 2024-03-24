### [Heart Framework](https://docs.google.com/presentation/d/1fdXlihNzZi-2fniiHWL7yIMDTZ40Lplni75lV9GFX2k/edit?usp=sharing)

- Metric 1:
- Metric 2 Adoption:
    We will utilize Firebase to collect relevant data and implement blocks within the app to track user interactions. Here's how we plan to do it:

    New User Sign-ups: Firebase provides authentication functionality that allows us to track new user sign-ups automatically. We will leverage Firebase Authentication to capture data on new users joining our app.

    Leaderboard Views: To track how many times users view the leaderboard, we will implement blocks within the app that increments a counter stored in Firebase whenever the leaderboard view button is pressed. This will involve adding event listeners to the leaderboard view button and updating a cloud variable in Firebase each time the button is clicked.

    Social Feed Views: Similarly, we will track how many times users view the social feed by implementing code within the app that increments another counter stored in Firebase whenever the social feed view button is pressed. This will involve adding event listeners to the social feed view button and updating a separate cloud variable in Firebase each time the button is clicked.

    This data will enable us to assess how effectively we're onboarding new users and engaging them with key features such as the leaderboard and social feed.

- Metric 3: 
- Metric 4 Retention:
  User Retention can be found within the Firebase Analytics page. Our team will use this exact measurement to determine user retention as other methods would prove
time consuming and useless considering the time constraints of the project. We have set a goal of a 30% user retention rate, encouraging users to return to our app by providing an experience that lives up to our golden path of a social workout platform where friends can compete with one another. The leagues within our app will be the primary form of this competition, a unique part of our app that can not be found elsewhere and will encourage a higher user retention rate.
  
- Metric 5 Task Success: We will have to keep track of all successes and failures of moving on to another screen, so the success rate of a button that changes screen. The Login button, Continue buttons, Different screen buttons on the bottom of the main screens to navigate to the leaderboard, workouts, or feeds. We will add blocks in Thunkable to increment a global value in firebase when a user successfully moves on to a specific screen and maybe another value for when a user runs into an error. Average Time per task could be fetched through code blocks in thunkable.
