# Verification_Bot

Application that is used to confirm university students in a discord servers by looking them up in the official website for students via their first & last name (and possibly other parameters)

This will also be used as a way to familiarize myself with independent side projects and thinking of creative solutions/app-development on my own

This will a 3 part pronged project, with individual components that can semi-function on their own if errors run into each other


1. Data collection from users (front end). A google form that collects data and runs a script to either email data/send it

2. The 24/7 running cloud instance that checks every 15 minutes for a new entry in the google sheets (or if any new entry is submitted), and if there is one to ping the discord bot for positive or negative 

3. The discord bot which would then message said user and let them know they're approved or rejected due to missing parameters/
