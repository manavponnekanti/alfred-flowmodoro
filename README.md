# Flowmodoro

A flow-based productivity timer which counts up instead of down and lets you take appropriately timed breaks as-needed. Automatically toggles Do Not Disturb on/off, logs work blocks to a calendar of your choice, and has the ability to toggle and change MacOS Background Sounds.

## Setup
Download and open the `.alfredworkflow` file from [latest releases](https://github.com/manavponnekanti/alfred-flowmodoro/releases/). When setting up the workflow for the first time, you can specify the trigger keyword, your work/break ratio, and the name of the calendar (assuming you have one set up in Calendar.app) that you wish to sync your work blocks to.

If you don't want to sync your work blocks to Calendar, just leave that variable empty. If you put in the name of a calendar that doesn't exist, events will just save to your default calendar.

When you first run the workflow, it will ask you to install the accompanying Apple Shortcut that the workflow relies on for changing your focus state, toggling Background Noises, and starting break timers.

## The work/break ratio

My issue with Pomodoro timers has always been that when I get really into something, I don't want to stop at 25 minutes. For other tasks, I can't even muster that much. However, I like the proportion of working to time off: 25 minutes to 5 minutes break. This means 6 minutes off if you work for 30 minutes, and 12 minutes off if you work for an hour. This workflow will automatically start break timers of varying lengths depending on how long you've worked.

The default ratio is 5 (the standard Pomodoro ratio), but you can change this to whatever you like. If you change it to 3, for example, if you work for 30 minutes you'll get a 10 minute break.
