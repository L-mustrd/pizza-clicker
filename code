var pizza=createSprite(100, 300);
pizza.setAnimation("pizza.png");
pizza.scale=0.5;

var peptxt=createSprite(350, 100);
peptxt.setAnimation("txt.gif");
peptxt.scale=3;

var vegtxt=createSprite(350, 200);
vegtxt.setAnimation("txt.gif");
vegtxt.scale=3;

var suptxt=createSprite(350, 300);
suptxt.setAnimation("txt.gif");
suptxt.scale=3;

var pintxt=createSprite(325, 390);
pintxt.setAnimation("txt.gif");
pintxt.scale=4;

var rattxt=createSprite(340, 30);
rattxt.setAnimation("txt.gif");
rattxt.scale=2.7;

var stafftxt=createSprite(80, 50);
stafftxt.setAnimation("text.gif");
stafftxt.scale=5;

var todd=createSprite(225, 50);
todd.setAnimation("todd.png");
todd.scale=0.25;

var end=createSprite (200, 220);
end.setAnimation ("txt.gif");
end.visible=false;
end.scale=5;

var why = 0;

var clicks = 0;

var clicksperclick = 1;

var clickspersec = 0;

var bad = 0;

var verybad = 5;

var neu = 0;

var winbig = 0;

var dingdingding = 5;

var chart = 0;

var final = 0;

var ___ = 0;

fill("black");
noStroke();

function draw() {
if (___==0){
  
if (final==0){
  
  if (clicks==-Infinity){
    pizza.visible=false;
    peptxt.visible=false;
    vegtxt.visible=false;
    suptxt.visible=false;
    pintxt.visible=false;
    stafftxt.visible=false;
    rattxt.visible=false;
    neu=1;
    why=why+1;
  }
  
  if (why>=1000){
    end.visible=true;
  }
  if(chart<=10){
  if (neu==0){
  background(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  fill(randomNumber(0, 255), randomNumber(0, 255), randomNumber(0, 255));
  rect(randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400), randomNumber(0, 400));
  }
  }
  
  clicks=clicks+clickspersec;
  
  if(mousePressedOver(pizza) && mouseWentDown("left")){
    clicks=clicks+clicksperclick;
  }
  
  if(clicks>=10){
    if(mousePressedOver(peptxt) && mouseWentDown("left")){
      clicksperclick=clicksperclick+1;
      clicks=clicks-10;
      pizza.setAnimation("pepperoni.png");
    }
  }

  if(clicks>=1000){
    if(mousePressedOver(vegtxt) && mouseWentDown("left")){
      clicksperclick=clicksperclick+150;
      clicks=clicks-1000;
      pizza.setAnimation("veggie.png");
    }
  }
  
  if(clicks>=1000000){
    if(mousePressedOver(suptxt) && mouseWentDown("left")){
      clicksperclick=clicksperclick+200000;
      clicks=clicks-1000000;
      pizza.setAnimation("supreme.png");
    }
  }
  
  if(clicks>=1000000000){
    if(mousePressedOver(pintxt) && mouseWentDown("left")){
      bad=1;
      clicks=clicks-1000000000;
      pizza.setAnimation("pineapple.png");
    }
  }
  
  if(clicks>=10000000){
    if(mousePressedOver(rattxt) && mouseWentDown("left")){
      clicks=clicks-10000000;
      clickspersec=clickspersec+1000;
    }
  }
  
  if(clicks>=10000){
    if(mousePressedOver(stafftxt) && mouseWentDown("left")){
      clicks=clicks-10000;
      clickspersec=clickspersec+1;
    }
  }
  
  if(bad==1){
    verybad=verybad*verybad;
    clicks=clicks-verybad;
  }
  
  todd.rotation=todd.rotation+2;
  drawSprites();
  if (why>=1000){
   text("End Game", 200, 200); 
  }
  
  fill("black");
  text("Pepperoni | 10", 300, 100);
  text("Staff | 10000", 50, 50);
  text("veggie | 1000", 300, 200);
  text("supreme | 1000000", 290, 300);
  text("pineapple | 1000000000", 250, 375);
  text("rat free | 10000000", 290, 30);
  
  textSize(50);
  textAlign(CENTER, CENTER);
  
  if(bad==1){
    textSize(25);
  }
  text(clicks, 200, 150);
  // if you are reading this you are an El Bozo
  if (mousePressedOver(todd)){
          if (keyWentDown("e")){
                  clicks=10000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000;
          }
  }
  if (mousePressedOver(stafftxt)){
    if(keyDown("l")){
      if(keyDown("m")){
          if(keyDown("s")){
                if(keyDown("d")){
                  winbig=1;
                }
              }
            }
          }
        }
  if(winbig==1){
    dingdingding=dingdingding*dingdingding;
    clicks=clicks+dingdingding;
  }
}
}

  if(mousePressedOver(end) && mouseWentDown("left")){
    final=1;
    background(0, 0, 0);
  }
  if (winbig==1 && bad==1){
    chart=chart+1;
  }
  if(chart==1000){
    background(255, 255, 255);
    text("you win pizza clicker", 200, 200);
    ___=1;
  }
}
