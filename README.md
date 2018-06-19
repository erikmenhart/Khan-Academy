# Khan-Academy
//shooting star
var xPos = 50;
var yPos = 100;
var siz = 10;

draw = function() {
    background(29, 40, 115);
    fill(255, 242, 0);
    ellipse(xPos, yPos, siz,siz);
    siz+=1;
    xPos+=1;
};
