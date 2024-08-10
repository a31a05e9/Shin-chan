# Shinchan Turtle Drawing

This repository contains a Python script that uses the `turtle` graphics library to draw a cartoon character resembling Shinchan, a popular character from the Japanese manga and anime series "Crayon Shin-chan". The script also includes a custom signature at the end of the drawing.

## Prerequisites

To run the script, you need to have Python installed on your system along with the `turtle` graphics library, which is included with Python’s standard library. 

## Code Overview

The script creates a drawing of a character with the following features:

- **Head**: Draws the character's head with a specific skin color.
- **Body**: Includes shirt and pants, along with the details of the hands and feet.
- **Face**: Includes eyes, eyebrows, mouth, and other facial features.
- **Robot**: Draws a small robot as part of the character's drawing.
- **Signature**: Adds a custom signature "By Meher" at the end of the drawing.

### Functions

- **`ankur()`**: Draws the main body of the character.
- **`leftLeg()`, `leftSock()`, `leftShoe()`**: Draws the left leg, sock, and shoe.
- **`rightLeg()`, `rightSock()`, `rightShoe()`**: Draws the right leg, sock, and shoe.
- **`myShirt()`**: Draws the shirt.
- **`myHead()`**: Draws the head with facial features.
- **`rightHand()`, `leftHand()`**: Draws the hands.
- **`myBis()`**: Draws additional items on the character.
- **`leftHand2()`**: Draws an additional hand.
- **`myMouth()`**: Draws the mouth.
- **`myEyebrow(x, y)`**: Draws the eyebrows at specified coordinates.
- **`myEyelid(x, y)`**: Draws the eyelids at specified coordinates.
- **`myallEyes1(x, y)`, `myallEyes2(x, y)`**: Draws the eyes with pupils at specified coordinates.
- **`myRobot()`**: Draws a small robot near the character.
- **`allLegs()`, `allHands()`, `allEyebrows()`, `allEyes()`**: Calls functions to draw all parts of the character's legs, hands, eyebrows, and eyes.
