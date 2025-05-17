<div align="center">
  <img width="250" src="./assets/images/logo.png">
</div>

<h1 align="center">Irrational Pi: Algorithm Art</h1>

## Project Overview

This project visualizes the irrational nature of Pi by using a double-arm algorithmic system. The interactive visualization draws beautiful patterns using the relationship between rotational speeds tied to Pi and customizable drawing parameters. Users can experiment with various controls to generate unique artistic interpretations of Pi's irrationality.

## Inspiration

Credit for the core idea goes to **@fascinating.fractals** and his [video](https://www.youtube.com/shorts/aUDYWYqtAR4) about drawing the irrational Pi. Without his creative content, this visualization would not exist. Please consider supporting his content.

## Preview

<div align="center">
  <img src="./assets/images/pi_visualization_1747473685628.png">
</div>

## Features

- Interactive parameter controls via a customizable panel
- Options to pause, reset, randomize, clear, or save both settings and imagery
- Pixel preservation mode for high-density trail art
- Load and save your favorite settings as JSON
- Download canvas art with one click
- Each session gives you a different way to visually experience Pi

## How to Use

1. Open `index.html` directly in your browser.
2. Use the ⚙️ icon to toggle the controls panel.
3. Adjust sliders or numeric inputs for speed, arm lengths, trail length, arm skip, or line width.
4. Use buttons to pause or play, reset, randomize, clear, or save current visualization or settings.
5. Flip Pixel Mode on or off for alternative rendering.
6. Save your settings as JSON, or load previously saved settings.
7. Download your art when you find a pattern you enjoy.

## Technologies & Methods Used

### Tools

- [Cursor IDE](https://www.cursor.com/)

- [Claude App](https://claude.ai/chats)

- [ChatGPT App](https://chat.openai.com/chat)

- [Cha](https://github.com/MehmetMHY/cha/)

- [Gemini App](https://gemini.google.com/app)

### Models Used

- Claude 3.7 Sonnet

- Google Gemini 2.5 Pro

- OpenAI o3

### How It Was Built

1. Used **Cha** to extract the content and description from **@fascinating.fractals** [video](https://www.youtube.com/shorts/aUDYWYqtAR4).

2. The content as a prompt was inputted into [Claude App](https://claude.ai/chats) to generate a prototype and render it though their **Interactive Artifact** side window. Claude's **Claude 3.7 Sonnet** was used for this entire process.

3. After the prototype was good enough and I ran out of free chat memory, I created a local [git](https://git-scm.com/) project and transferred the code from Claude's web app to this local git project.

4. After transferring it, I opened the local project with the **Cursor IDE**, were I have a Pro plan, and I utilized **Claude 3.7 Sonnet** and **Google Gemini 2.5 Pro** to finish implementing the project itself. I did use the **ChatGPT** and **Gemini** web apps to generate ideas and feed it into the **Cursor IDE** to fix more complex bugs. In **ChatGPT** I utilized OpenAI's **o3** model and in **Gemini** I used their **Google Gemini 2.5 Pro** model.

5. I tested the project in my browser by just opening the single index HTML file in my browser.

## License

This project is for personal and educational use only. Major creative credit goes to @fascinating.fractals for the algorithmic inspiration. See his [video](https://www.youtube.com/shorts/aUDYWYqtAR4) for a detailed explanation and origin.
