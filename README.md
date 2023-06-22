# Mobile-Architect-and-Programming

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The requirements of the app I developed were to develop UI layouts in Android Studio that depicted the login, inventory, and SMS enabling screens. I was then required to create code that supported the functionality of those layouts by creating corresponding Java files. The goals of the app were to create a fully functional inventory management app that supports user needs by allowing them to keep track of product inventory, in whatever industry they are in.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

All screens and features supported user needs and produced a user-centered UI for the app in various ways. Starting with the login screen, users could create an account easily by simply typing in their usernames and passwords inside the text fields and then clicking on the "Create an Account" button. In the inventory screen shown after the user has logged in, a simple UI is shown that shows a FAB with a brightly colored "+" icon, indicating a user can click on the icon to add items to the inventory. Once a user selects that icon, they are able to add an item description and then change the quanitity amounts or delete the item alltogether should they choose to. In the last UI, the SMS enabling screen, users can get to this screen by clicking on the bell icon in the inventory screen. Here, the users can simply choose to give permission to the app to enable SMS messaging or to not to enable it. If they do enable it, users will be able to recieve text messages when their inventory hits 0. I kept the user in mind by making sure my UI design was user-friendly and ensured all items would be held and saved in the database when the user exits and returns to the app at a later date. My app was successful because it met all requirements and followed android design guidelines. 

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

As I have mentioned in a previous course, I like to work in iterations, completing one task at a time. So, with this project, I first started out creating the XML layouts for each of the screens first. Once I had that down, I started working on the Java code, one screen at a time. For example, I started with the login_screen.xml file first then I got to work on the LoginScreen.Java file until I felt I met all functionality requirements. This ensured that I focused on one aspect at a time, without getting overwhelmed by the complexity of the entire project. 

# How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I tested the app to ensure that my code was functional by running the app in the emulator and testing all features. I did this many, many times until I believed the app was ready to go. This process is extrememly important as when you run your application in an emulator, you will see what is and isn't working properly, so that you can work to fix it. 

# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

The initial stages of the development process are often the most straightforward for me to accomplish. Where I came across the greatest challenges was when working on the Java files that corresponded with the XML layout files. Specifically, it was quite the challenge creating my ListView which would display all inventory items on the invenotry screen of my app. I tried many different methods to ensure that it operated correctly, and even now looking back, there are still some things I wish I did different, such as using an EditText instead of a TextView for the amount of an item, because it might be frustrating to the user if they have to click the "+" icon 100 times. 

# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The component from my mobile app that I believe I was particularly successful in demonstrating my knowledge, skills, and experience was the notification permission screen. In this screen permissions are granted to the Inventory App application if the user decides to "Allow" it. This then initiates the delivery of an SMS message to the user when an inventory items hits 0. 

