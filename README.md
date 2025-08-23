# CS_320_Portfolio
Portfolio for CS 320 - Operating Platforms

•	Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room client wanted to take their existing game, Draw It or Lose, and expand it to cover multiple platforms and needed to review any new software requirements before expansion of new services. Currently the game app runs only on Android, but expansion plans include releasing the game on iOS as well, with potential plans to release on home consoles and PCs in the future.

•	What did you do particularly well in developing this documentation?

I felt that the details that I added in when comparing the various platforms (MacOS, Linux, Windows and even Mobile) were excellent and researched thoroughly. There was enough information available to determine the best platform of choice, without overloading the client with information deemed unnecessary.

•	What about the process of working through a design document did you find helpful when developing the code?

Having a already created UML diagram that just needed proper interpretation and translation into code, probably helped the most. I feel that despite that, I did slightly change the wording of the code, particularly with the singleton class and how it’s called from the program driver class. It still functions similarly, but the order is different.

•	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I had to select one section that needs revision or additional information, it would be the recommendations section. I feel I did good on the information relayed, but I feel that if I had more experience with designing system architecture, I could add more information about exact components that would be needed, especially with security and encryption protocols and credit card transactions and compliance regulations and such.

•	How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

Because the client wanted a platform that would be a one stop shop style, the platform and the language needed to be something universal. Using a Linux distro for the host platform with the Java language for the platform, it would be able to support the vast majority, if not all, currently available platforms. These considerations were made to provide the greatest value, while maintaining the lowest operating costs.

•	How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

So as before, I stated that I approached the singleton class differently than the UML diagram. I believe the UML diagram asked for the game controller class to call the singleton class and provide a code for an instance. Rather what I did, was I called the singleton class from the main class and had that singleton class create the instance of the game controller class and hold that instance within the singleton class and the game controller class could just call back to get its reference id. It might not have been designed how the UML was, but I feel the purpose behind it was solid in the execution.
