# step_goal_calculator
For calculating the daily steps left for your yearly goal

Step Goal Calculator

A simple web page that tells you how many steps you need today to keep your yearly average at your daily step goal.

Live page: https://resonantfrequency.github.io/step_goal_calculator/

How to use:

Enter your daily step goal (it defaults at 8,000 and a change is remembered on your device).
Enter your average steps per day so far, including today.
Check the date. It fills in automatically, along with the day of the year.
Tap Calculate.

What you get:

More steps needed today to bring your average up to your goal, or a cushion showing how far ahead of pace you are.
Recovery table if you are behind: the daily average that closes the gap over 1, 3, 7, 14, or 30 days, starting tomorrow.
Rest of the year: the minimum steps for tomorrow to stay at goal, and the average per day needed through December 31. Leap years are handled.

How it works:

Steps so far = average x day of the year
Steps still needed today = (goal x day of the year) - steps so far

This assumes your average is your total steps divided by the number of days so far, with today counted as a day.

Privacy

Everything runs in your browser. Nothing you enter is sent anywhere. Your goal is saved only in your own browser, so clearing browser data or switching devices resets it to 8,000.
