# xwan0374_9103_Week8_Quiz
<h1>Part 1</h1>

My assignment is inspired by Wassily Kandinsky's work "several circles", which consists mainly of colorful prototypes of different sizes. These circles of different sizes and colors give the viewer a rhythmic and dynamic visual experience and the artist creates a wonderful and vibrant atmosphere. I will bring this randomness of different colors and sizes into my projects.
![several circles](https://github.com/xwan0374/xwan0374_9103_tut6/blob/main/several%20circles.webp)

My second inspiration was Kazimir Malevich - Aeroplane Flying, 1915, which impressed me with the combination of minimal geometric shapes. The bright colors and minimal geometric images draw the viewer's attention to the dynamics of the graphic structure of the work. The minimalist geometry and bold color palette of this piece is something I would like to incorporate into my project.
![Kazimir Malevich - Aeroplane Flying, 1915](https://github.com/xwan0374/xwan0374_9103_tut6/blob/main/Kazimir%20Malevich%20-%20Aeroplane%20Flying%2C%201915.jpeg)


<h1>Part 2</h1>

In order to implement the imaging technique I chose in part 1, I obtained the Aunt code at [link text](https://happycoding.io/tutorials/p5js/). This code generates circles of random size and color.[link text](https://happycoding.io/tutorials/p5js/random). 

function setup() { 
    createCanvas(200, 200); 
    background(32); 
}

function draw() { 
    var circleX = random(width); 
    var circleY = random(height); 
    var circleSize = random(10, 100); 
    fill(random(255), random(255), random(255));
    ellipse(circleX, circleY, circleSize);
}


The second code is about setting the position and size of the graphic.
[link text](https://p5js.org/examples/form-shape-primitives.html). 

function setup() {
  // Sets the screen to be 720 pixels wide and 400 pixels high
  createCanvas(720, 400);
  background(0);
  noStroke();

  fill(204);
  triangle(18, 18, 18, 360, 81, 360);

  fill(102);
  rect(81, 81, 63, 63);

  fill(204);
  quad(189, 18, 216, 18, 216, 360, 144, 360);

  fill(255);
  ellipse(252, 144, 72, 72);

  fill(204);
  triangle(288, 18, 351, 360, 288, 360);

  fill(255);
  arc(479, 300, 280, 280, PI, TWO_PI);
}

I'll try to combine the elements of these two inspirations to add some visual effects through these two sets of codes.



