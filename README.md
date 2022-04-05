<p align="center">
<img src="https://github.com/Khondwani/DiscoveryiOSChallenge/blob/18b5ba70f451bc7718324bd710040d9412df9fa5/Discovery-Insure.jpg" width="1000" height="300" border="10"/>
</p>

# Discovery Challenges

## [Challenge 1 Sighting data visualisation and Challenge 2: Sighthing data exploration](https://github.com/Khondwani/Challenge1-2)
For this challenge the above git repo has got everything required. Please read through the Readme.md for that is where i have given my answers and thoughts to challenge 1 and 2.

The commit messages also do share what each commit was for and also a few bug fixes obviously haha :D

## [Challenge 3 Build iOS Application](https://github.com/Khondwani/DiscoveryiOSChallenge)
For this challenge an iOS application was built with the requirement of being able to list bluetooth devices around the device.
For more information do read the ReadMe.md file of the above link to get my though process and what was added to it.

## Challenge 4 Paragraph Questions

- How do you set goals and benchmarks for app development?
  - I set goals depending on the importance of the feauture with regards to the application being built. There are certain features that would require immediate love and care for the app to be up and running. So in this case, I plan out my goals form highest priority to lowest priority.
  - As for benchmarks for app development, I first look at what is out there in the market already. what applications are in the same space i am building the current application. Then from this i guage as to what can i do better as compared to my competitors be it UX/UI, performance and effiecency (ie: Loading information to be way much quicker than a competitors application)
  - There is more for me to learn in this space of bench marking and setting goals. 
- Explain a good life cycle of app development?
  - This in my own words would be the growth of an application. One that goes through an agile process.
  - Basically going through a collection of requirements that the app must perform or have then a design phase where decisions over the UI/UX are made. This process aforementioned before should be iterated upon till atleast all required information is gathered. Then from there we go into the coding phase and testing phase where we start to build the concept, afterwad we then heading back to the design and requirements phase to make sure that all requirements are captured and built into the application. Then from here it is performing some user testing (user test phase) where we get feedback from potential consumers. This feedback can range from bugs to UI/UX and feature suggestions. As a result, this will lead to us iterating back to the previous phases. I guess from my basic experience i would consider this as a good development cycle.
- In your experience what part of the development lifecycle has been the hardest to accomplish? And what has been the easiest?
  - From my past experience the hardest part in the development cycle would be the Requirements phase in terms of getting all requirements to its finest level of detail, I usually end up iterating alot in this phase cause i do not want to waste time coding something and being told its not what is required. So basically i spend most of my time in this phase and that is why i find it difficult and a little boring haha.
  - The easiest has been the coding and testing phase. Reason been i enjoy seeing a product come to life from requirements to a working application that is being tested on by users. I enjoy seeing users enjoying something i have built.
- What are some of your favourite technologies and why? (e.g. Git, Docker etc.)
  -  I have quiet a few, tho my current top technology would be Git. Why Git? Well I have been working on a project, where we decided that we would use git as a storage system. This required some extensive reading and understanding the building blocks of Git. From all of that reading and implementation i found Git to be an exiting version control tool and how it all works in terms of the **working directory**, **staging Index** and **repository**. These 3 play a big role in gits system and understanding them made commands like git cherrypick mcuh more interesting cause i would know what is actually happening in the background. 
- Have you experienced any production issues and how do you handle them? Give an example.
  - YES YES YES YES!!! This happened in one of my side iOS projects and Web projects. Where the database backups could not be restored and this was during a database upgrade. Which then lead to the database being cleaned out!!! Thus causing doctors to have no access to their information. What caused this issue was googles way of zipping backups. So we resorted to manualy uploading bits and peaces of the database which was the only way to restore it. This roughly took an entire evening. This resulted in us making smaller backups and extra database rules that would avoid lose of data in certain parts of the database.
  - The other occasion was when a clients ec2 instance was nolonger working on a specific port and they had submissions to be done. This required countless hours of debugging and figuring out as to why the specifc port is not allowing communication. So usually i break down issue from the biggest picture to the smallest then work up. This lead to me finding out that a certain script they have automatcially run was changing the security groups of the ec2 instance and as a result locking the inbould on that specifc port.
    


