# Senior-Design-2020-Fall
Microsoft teams Description: Microsoft teams is an application for communication and collaboration platform that combines persistent workplace chat, video, meeting file storage, and application integration.
Problem:
because the pandemic by covid-19, all of our fully classes
will be online. Using discord server for handling all students are not enough, so Microsoft teams will be the replacement for discord. soon student will be able to use Microsoft Team for meeting tutor and contact instructors, and TAs. Therefore to
  
 handling a lot of student to join for the channels and the team for more efficient and convenience is to build a robot.
Proposal Summary
Our goal is to build a robot for validate the students for join the team and assign roles/channels.
Key feature of the bot should have:
•
•
Manage member joining and Authentication- check their abc123 and look their credentials. Moreover sending member a private message and the member reply it for validating themselves.
Assign course channels - after validated the member should be assigned for corresponding course channels. The list of course/section for each member can be handled by either a backend database or csv files. The data will be their first name, last name, course/section, abc123, and email id.(Updating feature should be considered)
Assign roles to the channel member - there could be 4 high level roles in each course channel.
•
instructor - add the instructor as the channel owner for the courses assigned. This roles will have all permissions except to remove anyone or create/delete another channel. Instructor should aces the instructor channel

Student - student can send or receive message and join the channel
TA - TA should have same permissions as the instructor role.
Tutor will also get access to tutor time reporting channel.
Extra feature: Based on the in/out stamps by the euros, there should be an automated system that calculates and auto generates a timesheet for each tutor. (tutor should interact directly/privately with the bot through private messages where commands can be entered to execute the above feature)
Our Target Platform
Microsoft Team, C#, .Net, javaScript and python.
