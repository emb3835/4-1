# 4-1
//Erik Bailey
//April 20, 2017
PFont font;
PFont a;
void setup() 
{
size(480, 120);
a=loadFont("Calibri-48.vlw");
font = loadFont("ACaslonPro-Bold-48.vlw");
textFont(font);
}
void draw()
{
background(102);
fill(255);
textFont(a);
text("Erik", 26, 30, 240, 100);
fill(0);
textFont(font);
text("Erik", 26, 78, 240, 100);
}
