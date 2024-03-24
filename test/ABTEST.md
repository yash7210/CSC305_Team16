#A/B Test Name: Onboarding Flow Optimization

#User Story Number: US1

#Metric: Adoption

#Hypothesis: 
The current onboarding flow may be causing friction for new users, resulting in a lower adoption rate. Simplifying the onboarding process and providing clearer guidance may lead to an increase in user sign-ups and engagement.

#Experiment:
Audiences: All new users who install the app during the test period will be included in the experiment. This ensures that the results are applicable to the target audience.
Experiment Setup: During the experiment, users will be randomly assigned to one of two variations of the onboarding flow: the control group will experience the current onboarding flow, while the experimental group will experience an optimized version.
Tracking Using Firebase Analytics: Firebase Analytics will be used to track key metrics such as:
Number of users who complete the onboarding process
Time spent in the onboarding flow
Drop-off points within the onboarding flow

#Variations:
Control Group (Variant A - Current Onboarding Flow): Users in this group will experience the existing onboarding flow, which consists of entering in basic information such as email and password, and then checking their email for a verification link. The user needs to verify their email before they can log in with their new account.
Experimental Group (Variant B - Optimized Onboarding Flow): Users in this group will experience an optimized onboarding flow, which includes the following changes:
Simplified sign-up process with fewer steps and clearer calls-to-action.
Personalized recommendations based on user preferences captured during sign-up.
Being able to log in to the app without having to initially verify their email. App usage will be limited until their email is verified, such as being unable to post to the leaderboard or social feed.
Design Work: Mockups and designs for the optimized onboarding flow will be created to visually represent the changes being tested. These designs will be reviewed and approved by the team before implementation.
Rationale: By testing variations of the onboarding flow, we can determine which approach leads to higher user adoption rates. The experimental group will provide insights into the effectiveness of the optimized onboarding flow compared to the current flow, helping us make data-driven decisions to improve user acquisition and retention.

This A/B test aims to directly address the Adoption metric by optimizing the onboarding experience to encourage more users to sign up for and engage with the FitnessRivals App.


A/B Test Name:
User Story Number:
Metric (from the HEART grid):
Hypothesis:
Experiment:
Variations:

A/B Test Name:
User Story Number:
Metric (from the HEART grid):
Hypothesis:
Experiment:
Variations:

A/B Test Name:
User Story Number:
Metric (from the HEART grid):
Hypothesis:
Experiment:
Variations:

User Story Number: 2
Metric (from the HEART grid): Engagement

Hypothesis: Changing the UI theme from light mode to dark mode (or vice versa), or altering the layout of buttons within the app, can increase user engagement. This is based on the assumption that visual comfort and ease of navigation have a significant impact on how users interact with the app. For instance, users might find dark mode less straining on the eyes in low-light conditions, leading to longer usage periods. Similarly, a more intuitive button layout could streamline user interactions, reducing frustration and potentially increasing the frequency and duration of app usage.

Experiment: Audience Selection: For this experiment, we'll allocate 50% of our user base to each variation. This ensures a significant sample size for both variations, providing reliable data while still exposing a large portion of our users to the potential improvements.
A 50/50 split allows for a direct comparison between the two variations with a balanced distribution of any external factors that might influence engagement.

Tracking with Firebase Analytics:

User Engagement Metrics: We'll track session length, number of sessions per user, and interactions per session as primary indicators of engagement.
Specific Interactions: For the button layout test, we'll also track click-through rates on the modified buttons and navigation paths to determine if the new layout is more intuitive.
Dark/Light Mode Preference: Track user switches between dark and light modes, if applicable, to see if there's a clear preference or if the option influences engagement time.


User Grouping: Use Firebase Remote Config to assign users randomly to either the control group or the experiment group.
Event Tracking: Implement custom events in Firebase Analytics for each key action you want to track, such as "switch_theme" for users changing between light and dark mode, or "button_click" with parameters to identify specific buttons.
Variations: Dark Mode vs. Light Mode: One group of users will experience the app in dark mode, while another group uses the traditional light mode. This tests the hypothesis that visual comfort affects engagement.
Which variation resulted in longer session times or more frequent app usage?
Is there a significant preference for either dark or light mode, based on user switches or engagement metrics?
Based on these findings, you can make informed decisions on implementing these UI/UX changes across your app to enhance overall user engagement

# A/B Test Name: Workout Screen Layout

User Story Number: US5 Provide Workouts with API

Metric (from the HEART grid): Engagement 

Hypothesis: By organizing workout information into a more structured format and providing additional details such as difficulty level, required equipment, and instructions on a separate screen, users will find it easier to discover and engage with workouts, leading to improved user engagement.

Experiment Setup:
We will allocate 50% of our user base to each variation, ensuring a balanced representation of users across both Test A and Test B. This will allow us to see how each group engages with the workout screens. We will track the engagement metrics of both groups by tracking the time spent on each workout page and recording the number of workouts viewed per session. Hypothetically both of these could be tracked using the Firebase A/B Testing feature to understand which layout our users prefer. 

Variations:
Test A (Control): Display all user workouts on a single screen without detailed information.

Test B (Variant): Display workouts on a separate screen, providing additional details such as difficulty level, required equipment, and instructions. Utilize tab or toggle list design to make the information more accessible and organized.

Design Mockup for Test A:
<img src="src/TestA.png" height="50" width="50"/>

Design Mockup for Test B:
<img src="src/TestB1.png" height="50" width="50"/>
<img src="src/TestB2.png" height="50" width="50"/>
