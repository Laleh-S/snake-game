# Snake Game
Link to project https://laleh-s.github.io/Project/

## Overview
After learning JavaScript for only two weeks, I had to build and design a JavaScript grid game. I decided to choose snake because I used to enjoy playing this game on my sony ericsson phone.

## Requirements
- Render a game in the browser
- Use JavaScript, CSS and HTML
- Use JavaScript for DOM manipulation
- Deploy the game using GitHub pages

## Technologies Used
- HTML
- CSS
- JavaScript
- DOM
- Git
- GitHub Pages

## Wireframe and planning
My planning and wireframing for this project was very limited due to my lack of experience. I was not sure what and how much details I had to add to this. My initial planning for this project was very limited due to my lack of experience. I was so excited about starting a project and I started working on it immediately.  

<img width="1132" alt="Screen Shot 2022-08-19 at 18 02 20" src="https://user-images.githubusercontent.com/92860992/185671657-6729f439-0d42-44d7-a8d5-e9834a03ba89.png">

## Approach 
 
I first started by creating my grid in HTMl, I very soon realised that creating a 400 grid using HTML is not good practice as It involves a lot of repetitive coding. I then created a div in my HTML and gave it the class name of the “container”.  I targeted that div with the class “container” to append new divs to it. I defined the width and the cell count in variables. I used a for loop to create more divs.
````
const container = document.querySelector('.container')
  const width = 20
  const cellCount = width * width
  const cells = []
  for (let i = 0; i < cellCount; i++) {
    const cell = document.createElement('div')
    cell.id = `cell-${i}`
    cell.classList.add('grid')
    container.appendChild(cell)
    cells.push(cell)
  }
````

## Project Screenshot
<img width="865" alt="Screen Shot 2022-09-09 at 21 05 24" src="https://user-images.githubusercontent.com/92860992/189425539-88ba3a7a-891b-4a6d-a96a-69f4d5e559e8.png">


## Key Learnings
The main thing I learned in this project was the importance of prior planning, wireframing and sketching before starting writing codes. I literally threw myself right in the middle of coding without knowing exactly what step to take at each stage. I’ve learned that proper planning prior to coding can have a major impact on the final product. I’ve also learned that good planning would give the coder the ability to foresee the problems they may face along the way.

## Wins
This was my very first project and I only had one week to create this game. In the end I was very happy being able to create and deploy a functioning game and meet all my MVP targets on time.


## Future Improvements
- WFixing issues with collisions
- Working on different levels
- Adding bonus features
- Adding a start button
- Working on the Gameover UI


