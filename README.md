# CS-360
Mobile Architect &amp; Programming


# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The app I developed was a weight tracking app. The user needs includes the ability to login or to create an account. From there, it would open a page that will allow them to input the date, their current weight, and their goal weight. In result, this would update the progress bar to show them how far along they are until their goal and update the listview that shows their previously stored information. Finally, notifying the user once the bar is filled. This information will also be stored in a SQLite database - LoginDatabase, WeightDatabase, and GoalDatabase.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
To support the features necessary, there are three different screens. First, the login and creating an account screen are together. The next screen is the home screen. The home screen is fairly simplistic for easy use and to fit a larger target audience. It has a settings button in the top right corner, three input slots set horizontally for adding the date, weight, and goal with a button directly below in the middle to save these inputs. Directly below this is the progress bar to show how far along they are from start to goal as well as the ability to check specific dates in the listview below that. The reason I decided on a simplistic approach is because most weight tracking apps on the market are specifically for losing weight with tracking calories, etc. - this app would be beneficial for those who are just simply curious about their weight fluctuation or gaining weight; as well as losing weight.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
To approach the process of coding my app, I started at the beginning of what the user would see; main activity one/login page. From there, I completed the code in order from what the user would see as they move through the app. This made it easier for me to double check what was completed and what other functions I may have wanted to include but overlooked in the design process. 

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?
To ensure my code was functional, I ran an Android Emulator to test each method. Before creating an account, I tried to log in with random credentials. Then once that did not work and had a popup note saying that it could not find the username or password, I created an account - went back - and tried to log in again with that information. Furthermore, it was a lot of back and forth to make sure everything was submitted that needed to be submitted but had limitations if something was inputted incorrectly. 

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
There were many times I came across a challenge. When that happened, YouTube videos that explained similar scenarios while also showing me the visual of how to fix and complete that part of code helped. Throughout the design process, I had made many smaller changes once I got into actually creating it within Android Studios. 

# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
One part of my mobile app that I felt very confident in is creating an account and/or logging in. That is the part that I felt most comfortable completing and feel that works the best.
