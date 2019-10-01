# Hack-a-thing 2
Alexis Harris, Morgan Sorbaro

## What We Built
In this Hack-a-thing we built four different ios apps in Swift. Since we live together, we pair coded and alternated who was the driver for each game.

*Ninja Game* - This game featured a ninja who shot at preditors as they approaced. If the preditors passed the ninja then the user would loose the game

*Cookie Crunch* - This is a cookie version of candy crush. The user swipes to remove the cookies.

*Numbers Game* - In this game the user needs to add the number one to each digit in the presented number. The user has 60 seconds to do as many correctly as possible and gets a score at the end.

*Food Tracker* - This is an app that lets users keep track of their meals with photos and ratings. Users can add meals, rate them, edit them and delete them.

## Who Did What
Alexis drove for Candy Crush and Food Tracker, while the Ninja Game and Number Game was coded on Morgan's Computer. We played around with pair programming, which actually helped us catch some bugs, especially in the Ninja Game. We also did a bit of individual coding so we could code without having to be in the same place at the same time, where Alexis worked more on the Food Tracker and Morgan worked more on the Numbers Game.

## What We Learned
Overall this project taught us a lot about Swift and IOS developement. Swift is a lot different than react native which we have both worked with before and it was really interesting to see the similarities between Swift, React Native and Andriod Kotlin (which we learned in Mobile Development). Besides having a new base understanding of Xcode and Swift, each game taught us a lot of specific code features we would not otherwise have learned.

*Ninja Game* - This game taught us a lot about randomly spawning objects and collision detection. We had to do projectile math to calculate where the ball should go reletive to the user's touch. From there, we needed to code collision objects to figure out if the ball had hit the attacker.

*Cookie Crunch* - This game offered a lot of challenges and ended up not working well. That being said, we still learned how to read in files from Swift and how to parse them. The cookie crunch bored was set up from a JSON file so different levels could be created, and we learned how to use these level files and parse them in Swift.

*Number Game* - The number game showed us how to work with Coco Pods. Cocopods are additions that you can add into your application and in this app we used them for the timer.

*Food Tracker* - This game taught us a lot about MVC, and how to use the XCode interface. We really enjoyed the ability to drag certain features, like a button or label, straight into the code to code corresponding functions. We also enjoyed using story boards to be able to actually see the app as it was being built up. Additionally, there was a small section on making the app accessible using iOS's built in accessibility features which was really cool. I think if we were to code an app in Swift using iOS, we would definitely implement some of these accessibility features.

## How Did This Inspire Us/Relate to Possible Ideas
There are so many ideas that can come from creating an IOS app. We think what was most inspiring was seeing how easy it is to create an app using the story board. In React Native you need to use CSS to style the whole app but with Swift the drag and drop program with constraints is much better and makes styling easier. We also were inspired by how many cocopod libraries there are to choose from and the different extensions you can easily get just by using a new library. The accessibility features offered in iOS also inspired us to be more cognizant of accessibility while building an application and showed us how easy it would be to implement them in Swift.

In our in-class group, we discussed sustainability and the possibility of creating a game around sustainability. The game tutorials we did here would be a helpful first step toward that idea if we choose to go in that direction, as it helped us think about the process of creating a game.

If we want to make an app, Swift would definitely be an interesting challenge to work with. I think this hack-a-thing allowed us to get comfortable with Swift/XCode in order to use it as a potential medium for a project.

## What Didn't Work
There are many things that did not work with our applications. First, the cookie crunch background images did not show up correctly and eventually we had to abandon the the tutorial due to many bugs being unsolvable. The instructions were relatively clear, but in order to really debug it, we think we would need to get even more comfortable with Swift, as some parts of the language/syntax look really new. Moreover, getting the cocopods to work was much more complicated than expected. In the tutorial we were using it was just a few terminal commands and then it worked fine but on our computer there were many errors and we had to spend a lot of time on Stack Overflow to figure out why they weren't installing. At the end of the day it turns out the pod file wasn't correctly named and everything was fixed after that. Lastly, some parts of the Swift language were a little hard to grasp at first, especially the function declarations which looked very different to us. We had to change one function because Swift (and a bit of syntax) had been updated since the tutorial was made. This took us a little while to figure out, but once we saw how the syntax had been updated, it was an easy fix.

## Resources

https://www.raywenderlich.com/71-spritekit-tutorial-for-beginners

https://www.raywenderlich.com/55-how-to-make-a-game-like-candy-crush-with-spritekit-and-swift-part-1

https://www.raywenderlich.com/54-how-to-make-a-game-like-candy-crush-with-spritekit-and-swift-part-2

https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/BuildABasicUI.html#//apple_ref/doc/uid/TP40015214-CH5-SW1

https://learnappmaking.com/creating-a-simple-ios-game-with-swift-in-xcode/
