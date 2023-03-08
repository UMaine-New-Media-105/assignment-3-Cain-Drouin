var toolboxX = 0;
var toolFalling = false; // You can start from this outline to write your "Hungry Bird" game
// where objects drop and you try to catch them.
function setup() {
  // ADD CONSTANT VARIABLES
  // Set values here that don't change over the course of the game,
  // but are convenient to name as variables because they are used
  // throughout the code. Eg, "groundY" could be the height of the ground.
  var groundY = 350;

  // ADD CHANGING VARIABLES
  // Set an initial value for variables here that may change later.
  // Eg, "birdX = 0" could start the catcher at the canvas' left edge.
  // "seedIsFalling = false" could ensure it doesn't fall until triggered.

  // Set up the canvas.
  createCanvas(400, 400);
  angleMode(DEGREES); // Use this to create shapes with arcs and degrees.
}

function draw() {
  // BACKGROUND
  // Draw the background color and any other shapes that don't change.
  background("skyblue");
  push();
  fill(51, 29, 18);
  noStroke();
  rect(0, 350, 400);
  pop();
  // ADD CATCHER

  // Add your catcher by calling its function with appropriate parameters.
  addToolBox(mouseX, 285);

  // ADD Falling Object
  // Add the falling shape, either directly here or via a function.
  // This code could include animating the fall, or checking for conditions.
}

// CATCHER
function addToolBox(x, y) {
  push();
  if (mouseIsPressed) {
    translate(x, y);
    fill("red");
    rect(10, 50, 50, 25);
    rect(10, 40, 50, 10);
  } else {
    translate(x, y);
    fill("red");
    rect(10, 50, 50, 25);
    rect(0, 0, 10, 50);

    pop();
  }
}
// Add a function here to build your "catcher" from shapes.
// This function can include parameters that tell it where to sit
// as well as conditions that change its appearance.
