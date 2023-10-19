---
layout: default
title: Home
---

## Our Project Layout
## Welcome to our Customized Fitness Plan Creation Program
For our passion project, we've chosen to develop a program that can support you in your pursuit of attaining your desired body shape. This program is designed to aid you in either gaining or losing weight, helping you work towards your ideal physique while promoting a healthier lifestyle

## How Our Program Works

To begin, you'll determine your daily calorie maintenance by providing details such as your age, weight, height, gender, and activity level. This information will be securely stored in our backend associated with your user profile. Subsequently, we'll utilize this data to formulate a personalized plan aligned with your objectives and dietary preferences. If your goal is weight loss, we'll recommend a combination of cardio-focused exercises and suitable foods to assist you in reaching your fitness targets.

<p>Try our program by clicking the "Calculate" Button below:</p>
<button><a href="https://www.google.com/search?sca_esv=569384727&q=smurf+cat+meme&tbm=vid&source=lnms&sa=X&ved=2ahUKEwidooPHqM-BAxXKMUQIHRsGCGEQ0pQJegQICRAB&biw=1440&bih=702&dpr=2&safe=active&ssui=on#fpstate=ive&vld=cid:b4627ef3,vid:Gmc00FKuH70,st:0">Click to see Smurf Cat Before you use the Calculator</a></button>

<head>
    <title>Calorie Calculator</title>
</head>
<body>
    <h1>Calorie Calculator</h1>
    <form action="/save_data_to_backend" method="post">
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required><br><br>

        <label for="weight">Weight (kg):</label>
        <input type="number" id="weight" name="weight" required><br><br>

        <label for="height">Height (cm):</label>
        <input type="number" id="height" name="height" required><br><br>

        <label for="activity">Activity Level:</label>
        <select id="activity" name="activity">
            <option value="sedentary">Sedentary</option>
            <option value="lightly_active">Lightly Active</option>
            <option value="moderately_active">Moderately Active</option>
            <option value="very_active">Very Active</option>
        </select><br><br>

        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required><br><br>

        <input type="submit" value="Calculate Calories">
    </form>
</body>
<br>

## What We Are Working On

- Getting an idea on how to create users for the back end, how the code will work and look
- Making the interface on the front end look easy to use and have a miniamlaistic desing
- Add fun gifs and animations that show succsess or errors to keep on trying