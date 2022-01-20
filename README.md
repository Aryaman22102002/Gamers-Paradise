# Gamers-Paradise

<h1 align = "center" > STREET RACER 2D

## Table of Contents

- [Gamers-Paradise](#gamers-paradise)
  - [Table of Contents](#table-of-contents)
  - [🗒️About](#️about)
  - [📁File Structure](#file-structure)
  - [👨‍💻 Tech-Stack](#-tech-stack)
  - [🛠️ Prerequisites](#️-prerequisites)
    - [<b>Gesture control</b>](#bgesture-controlb)
    - [<b>Play Game</b>](#bplay-gameb)
  - [📈Future Prospects](#future-prospects)
  - [🎮 Demo of the game](#-demo-of-the-game)
  - [👋 Controlling the game using hand detection](#-controlling-the-game-using-hand-detection)
  - [🏅 Team Members](#-team-members)
  - [😎 Mentors](#-mentors)
  - [License](#license)


## 🗒️About

• Making a Gesture-controlled 2D Car Racing game using phaser.js

• Implementing stearing control using hand gestures with help of OpenCv library of Python

• Visit our [Github repo](https://github.com/ParthShirole/Gamers-Paradise) to clone and play the game.

## 📁File Structure
```
┣ 📂my_game
 ┃ ┣ 📂assets
 ┃ ┃ ┣ 📜enemycar.png
 ┃ ┃ ┣ 📜phaser.png
 ┃ ┃ ┣ 📜player.png
 ┃ ┃ ┣ 📜road_test.png
 ┃ ┃ ┣ 📜sound.mp3
 ┃ ┃ ┗ 📜star.png
 ┃ ┣ 📜control.py
 ┃ ┣ 📜game.js
 ┃ ┣ 📜index.html
 ┃ ┣ 📜phaser.js
 ┃ ┗ 📜phaser.min.js
 ┣ 📜Gesture_Controls.ipynb
 ┣ 📜LICENSE
 ┗ 📜README.md
```

## 👨‍💻 Tech-Stack

<p>
<image src="https://github.com/get-icon/geticon/blob/master/icons/html-5.svg" width=30 title="Html">
<image src="https://github.com/get-icon/geticon/blob/master/icons/css-3.svg" width=30 title="CSS">
<image src="https://github.com/get-icon/geticon/blob/master/icons/javascript.svg" width=30 title="Javascript">
<image src="https://github.com/get-icon/geticon/raw/master/icons/python.svg" width=35 title="python">
<image src="https://user-images.githubusercontent.com/83249996/146242645-c764b523-2fce-4f59-b2e9-b51a5a0fc028.jpg" width=35 title="phaser">
<image src="https://github.com/get-icon/geticon/blob/master/icons/opencv.svg" width=28 title="opencv">
</p>

 
## 🛠️ Prerequisites 
  ### <b>Gesture control</b>
  Following Libraries must be installed. 
  The commands for installation are :<br/>
 ```
 pip install numpy
 ```
 ```
 pip install opencv-python
 ```
 ```
 pip install mediapipe
 ```
 ```
 pip install cvzone==1.4.1 
 ```
 ```
 pip install pynput
 ```
  In the code there is a part to capture the live stream Videocapture(n) here the index n is by default 0 for most machines but if the webcam doesn't work with 0 you can try 1,-1,0 and so on. 
<br/>
### <b>Play Game</b>
Run the index.html file via liveserver to play the game<br>
Press ```Spacebar``` to Start the game<br/> 

## 📈Future Prospects

- [ ] Use Flask to import gesture control code
- [ ] Implement socket connection between client and server
- [ ] Add levels in Game

  
## 🎮 Demo of the game


https://user-images.githubusercontent.com/81592570/146214263-dfd22969-75af-4e91-a78e-102664125066.mp4


## 👋 Controlling the game using hand detection 
  
  
  

https://user-images.githubusercontent.com/81592570/146202672-1971c43b-1c81-4498-a553-87b6c22c8a72.mp4

We have mapped the controls of the car to the W,A,S,D keys on the keyboard so by using these virtual keys we can control the car .
  We are using Mediapipe hand detection model under hood for hand detection . 
  
  
  ![hand_landmarks](https://user-images.githubusercontent.com/81592570/146204032-e8524d4c-97db-461f-9d6e-6018c3275de2.png)

  


 
## 🏅 Team Members

- [Parth Shirole](https://github.com/ParthShirole) - parthshirole06@gmail.com
- [Aryaman Shardul](https://github.com/Aryaman22102002) - aryashardul2002@gmail.com
- [Rishabh Bali](https://github.com/Ris-Bali) - rishabhsbali@gmail.com
- [Kunal Agarwal](https://github.com/KunalA18) - kunalagarwal1072002@gmail.com 

## 😎 Mentors 
- [Kush Kothari](https://github.com/kkothari2001) 
- [Reshmika Nambiar](https://github.com/Reshmika-Nambiar)
  
## License
The [License](LICENSE) used in this project.  
