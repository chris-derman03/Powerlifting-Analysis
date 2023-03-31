# Powerlifting-Predictions
Data Analysis on world powerlifting data. Make predictions for new lifters.

As an avid lifer and bodybuilder, I was shocked to notice how much public data on powerlifting was available!
My initial thought as a Data Scientist, like all would, was to ask the question, "Can we predict a competitor's 1-rep max on each main lift based on their stats?"

See the end of this file for some context on powerlifting.

After implementing a prediction model, I hit a dead end as the world of lifting has A LOT of (hold one second) (*clears throat*), A LOTTTTTTT of variability. Genetic freaks of nature exist EVERYWHERE in the lifting world. This inevitably makes the prediction problem extremely difficult to achieve any sort of good accuracy on.
My implementation turned out to perform very decently, but there was still some error as expected with any Machine Learning problem.

However, I noticed that this was actually a good thing. Using some logic, there is a very useful implication to this imperfect model! See the jupyter notebook for an in-depth explanation.

Powerlifting, specifically the IPF (International Powerlifting Federation)
In the competitions we care about (SBD), lifters will compete in three compound muscle movements, Squat, Bench, and deadlift. Squatting is as it sounds, you put a barbell on your back and squat down, then squat back up. With bench press, you lay on a bench, grab a barbell, lower it to your chest, and press it back up. Deadlift begins with a barbell on the floor. You bend down, grab it, and attempt to stand up with the weight.
Each lifter gets 3 attempts for each lift. 3 judges will watch the lift for form technicalities, and will each give the lift a thumbs up or a thumbs down. If at least 2 of the 3 judges green-light the lift, it is valid and recorded. The best of the lifter's 3 attempts is considered to be their 1-rep max for that lift, on that day.
The order is Squat, Bench, Deadlift. (SBD)
