---
title: Support
permalink: /support/
---

# Feel Good support

Feel Good is a mood diary for iPhone that looks for patterns. Each evening it asks how you feel, how your energy was and how well the day went. It reads the health data your phone already has, and after three weeks it tells you which of those signals move with your mood. Everything stays on your phone; the [privacy policy](../privacy/) says exactly what is kept and where.

## What the app does

**Check-ins.** Three notifications a day, at a random time in the morning, in the afternoon and in the evening. Hold a notification to answer from the lock screen: how you feel from 1 to 10, then your energy from 1 to 10 or skip it. The evening notification also asks how well you spent the day, 1 (wasted) to 10 (well spent), or skip. Opening the app shows the same questions plus optional tags and a note; the day question appears there from 17:00.

**Health data.** After you connect the Health app, Feel Good copies one number per day for sleep, steps, resting heart rate, heart rate variability, active energy, exercise minutes and workouts. It syncs by itself whenever you open the app or save a check-in.

**Time in apps (optional).** Pick apps on the Plan page (the Today tab, then Plan), in Apple's picker, and iOS counts your minutes in each, in 5-minute steps. Each app becomes one more line in your data and one more thing tested against your mood.

**Insights.** The Insights tab shows how far you are from the minimum, the patterns found so far, and a Your data list with yesterday's and today's value for every metric and app. A Trends chart draws your daily minutes in each tracked app over the last week or month, one line per app, with a line at 10 minutes to stay under; a day with no mark is a day iOS was not counting that app.

**Screen time (optional).** Once Screen Time access is allowed, the Insights tab opens with a Screen time box drawn by iOS: today's total time on the phone, pickups and notifications, the last seven days as bars, today's top apps, and the last seven days against the seven before, app by app, so you can watch the number go down, with every app by category, for today or the last seven days, on a page behind it. These numbers are drawn by iOS inside a sealed view; Feel Good cannot read, store or test them against your mood, which is why they are shown but not correlated.

**Good day badge (optional).** A widget for your Home or Lock Screen that stays lit through the quiet hours you choose, a morning hour to an evening hour or bedtime to the small hours, as long as the tracked apps you pick for each window stay closed, give or take an allowance in minutes. It fills through the day, dims as you use the allowance, and goes out a minute past it. A break, started from the Today tab, frees the apps for a set number of minutes without touching the badge. The Today tab shows how the day is going, each window's minutes and breaks and the tracked apps' minutes today, with a line to keep you going, and how yesterday went, bedtime included, in full in the morning and in one line after. The Plan page, behind the Today tab, sets it up and says how to add the widget.

**Quiet hours and Ask for time (optional).** Quiet hours are a schedule: up to three windows, each with its hours, the days of the week it starts on, the apps that count in it, its own allowance and its own breaks, so a morning and an afternoon window, or weekday and weekend hours, are both possible; a day with no window is a day off for the badge. A window may run past midnight, for bedtime; the night then counts for the day it starts on, and the badge shows how it went until the next quiet hours start. With Close the apps on, the apps you chose open to a Quiet hours screen during those hours instead of opening. Tap Ask for time on that screen and it asks what for, with two answers, then for how long, 5 or 15 minutes, and the app opens right there; the minutes come out of your allowance and it closes again by itself once they are used. From Feel Good's Today tab you can also ask in your own words. Saying what for is the point; the words are not kept. Each ask in a day costs a little more: the first is the question, the second makes you wait ten seconds first, and from the third you wait thirty seconds and then ask in Feel Good itself, in a sentence. While the badge is on, a change that loosens your plan (a shorter window, a bigger allowance, an app removed, the badge or Close the apps turned off) starts only once today's quiet hours are over; a change that tightens it starts at once. The Plan page shows what is waiting and lets you drop it.

## How insights work

Insights need 21 days that have both a mood rating and at least one health number. With fewer days the tab shows a progress bar and nothing else, because anything it said earlier would be noise.

Once there are enough days, the app compares each daily metric, and each metric's value from the day before, with that day's average mood. It uses a rank correlation, so a few unusual days do not dominate, and it corrects for the fact that it is testing many metrics at once, so a pattern has to be strong enough to survive that correction before it is shown. Each pattern says how strong it is, which direction it runs, and how many days it is based on.

These are associations, not causes. "Higher hours of sleep goes with better mood" means those two moved together in your data over those days. It does not mean one caused the other; something else may drive both, or the direction may run the other way. Treat a pattern as a question worth asking about your own life, not as an answer.

## Common questions

**Why is a metric blank?**
Yesterday's or today's value is blank when Health has no number for that day. Common reasons: that category is not allowed for Feel Good (check the Health app, your picture, then Apps, then Feel Good); nothing recorded it (heart rate, heart rate variability and exercise minutes mostly come from an Apple Watch; sleep needs a watch or a sleep app); or the day has not synced yet (Feel Good re-reads Health when you open the app, at most once every 15 minutes; Sync now in Settings forces it). A whole category that is blank on every day is simply not shown in the list.

**Why does app counting start the next morning?**
iOS counts an app's minutes from the start of each day. The day you pick an app is usually left blank rather than guessed, because part of it went uncounted; from the next morning every day is counted. A day shows 0 when the app was being counted and you did not reach the first 5-minute mark, and shows nothing when iOS was not counting that day.

**How do I stop tracking an app?**
On the Plan page (the Today tab, then Plan), swipe the app away. iOS stops counting it at once. The days already counted are kept so the app's history is not lost. To stop app tracking altogether, turn off Feel Good under Settings > Screen Time > Apps with Screen Time Access.

**I said no to a permission. How do I change my mind?**
Each tab tells you when its permission is off and has an Open Settings button. Notifications: Settings > Notifications > Feel Good. Health: the Health app, your picture, Apps, Feel Good. Screen Time: Settings > Screen Time > Apps with Screen Time Access.

**I need one of those apps for a bit. Do I have to lose the badge?**
No. Tap the widget and tap Take a break. For the length set in that window (20 minutes unless you change it) the apps are free and nothing you do in them counts; the countdown shows on the widget. When it ends, the rest of quiet hours counts as before, with whatever allowance you had left. You can end a break early, and the number of breaks a day is yours to set, per window.

**Will it remind me?**
Two reminders, both on by default under Reminders on the Plan page: one five minutes before your quiet hours start each day, and one a minute before a break ends so you can close the app in time. The badge also tells you when the allowance is used up and when the day is lost. All of them need notifications allowed.

**Can Feel Good stop me opening the apps?**
Yes, if you ask it to: Close the apps under Quiet hours on the Plan page (the Today tab, then Plan). iOS then shows a Quiet hours screen over those apps in those hours. You are never locked out: Ask for time on that screen asks what for and for how long and opens the app for those minutes, and a break frees them all. Turn the switch off and the screen is gone.

**I lost the badge. Is the day over?**
Not yet. Open Feel Good (tapping the widget or the notification takes you there) and tap Start again from now. The loss is cleared and the count starts from that minute. You get one restart a day; a second loss stands until tomorrow. The evening is free either way, and tomorrow starts fresh.

**What is "Show sample data"?**
A switch in Settings that shows ninety made-up days, marked "Sample data" on screen, so you can see what the Insights and History tabs will look like before you have three weeks of your own. It is built into the app, never mixed with your data, and turns itself off once your own data reaches 21 days.

**How do I delete everything?**
Settings (the gear at the top of any tab) > Delete all data. It removes every check-in, Health copy, app count and setting from your phone and stops app tracking. Deleting the app does the same. The Health app keeps its own data.

**Does anything leave my phone?**
No. There is no account, no server, no analytics and no advertising. Details are in the [privacy policy](../privacy/).

## Contact

Problems, questions or ideas: feelgood.app.support@gmail.com
