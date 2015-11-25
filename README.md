# 2D_Becas
/*String año[]={"2004","2005","2006","2007","2008","2009","2010","2011","2012","2013","2014"};
 float mujeres[]={3.307,3.399,4.676,5.420,6.034,6,658,6.762,6.453,5.486,4.221,5.722};
 float hombres[]={6.488,7.572,8.692,9.670,10.690,11.302,11.370,10.596,9.055,7.086,9.409};*/
PFont fuente, fuente_peq;
void setup() {
  size(1080, 720);
  background(48, 45, 45);


  stroke (255);
  strokeWeight (5);
  line(372, 165, 709, 530);
  line(349, 185, 685, 551);
  stroke (247, 179, 70);
  strokeWeight (25);
  noFill();
  ellipse (529, 359, 525, 525);
  strokeCap(SQUARE);
  line (710, 170, 810, 70);
  line (750, 70, 823, 70);
  line (811, 60, 811, 130);

  line (237, 640, 337, 540);

  line (237, 580, 297, 640);
  stroke (38, 114, 183);
  arc (529, 359, 615, 615, -0.7, 0.7);
  arc (529, 359, 615, 615, -2.2, -0.89);

  stroke (228, 21, 123);
  arc (529, 359, 615, 615, 0.93, 2.3);
  arc (529, 359, 615, 615, 2.5, 3.9);

  stroke (255);
  strokeWeight (10);

  //hombres
  //2004
  arc (529, 359, 450, 450, 4.0491, 4.967486304);
  //2005
  arc (529, 359, 370, 370, 4.0491, 5.0111280680583);
  //2006
  arc (529, 359, 280, 280, 4.07, 4.948337441409);
  //2007
  arc (529, 359, 185, 185, 4.15, 4.9335912470613);
  //2008
  arc (529, 359, 95, 95, 4.3, 4.63395332547);
  //2009
  line (540, 344, 610, 274);
  //2014
  arc (529, 359, 450, 450, -0.1428, 0.76);
  //2013
  arc (529, 359, 370, 370, -0.1423, 0.74);
  //2012
  arc (529, 359, 280, 280, -0.139, 0.69);
  //2011
  arc (529, 359, 185, 185, -0.13, 0.63);
  //2010
  arc (529, 359, 95, 95, -0.119, 0.5);

  //mujeres
  //2004
  arc (529, 359, 450, 450, 3.378809744, 3.9);
  //2005
  arc (529, 359, 370, 370, 3.407923662, 3.88);
  //2006
  arc (529, 359, 280, 280, 3.327465262, 3.85);
  //2007
  arc (529, 359, 185, 185, 3.281383448, 3.8);
  //2008
  arc (529, 359, 95, 95, 3.23918405, 3.67);
  //2009
  //line (540,344,640,244);
  line (485, 399, 515, 369);
  //2014
  arc (529, 359, 450, 450, 0.9, 1.805458942);
  //2013
  arc (529, 359, 370, 370, 0.92, 1.820060273);
  //2012
  arc (529, 359, 280, 280, 0.94, 1.821861513);
  //2011
  arc (529, 359, 185, 185, 1, 1.867878371);
  //2010
  arc (529, 359, 95, 95, 1.1, 1.780765741);




  strokeWeight (2);
  fuente = loadFont("MyriadPro-Regular-20.vlw");

  textFont(fuente, 16);
  text("Hombres", 55, 45);
  text("Mujeres", 55, 75);
  text("Investigadores segun sexo", 900, 685);
  text("11.500.000", 860, 175);
  text("7.000.000", 130, 545);

  textFont (fuente, 12);
  text ("2004", 365, 197  );
  text ("2005", 395, 227);
  text ("2006", 425, 260);
  text ("2007", 455, 293);
  text ("2008", 485, 326);
  text ("2009", 515, 359);
  text ("2010", 545, 392);
  text ("2011", 575, 424);
  text ("2012", 605, 457);
  text ("2013", 635, 490);
  text ("2014", 665, 523);

  fill(255);
  stroke(255);
  noFill();
  line(140, 680, 880, 680);
  line(200, 540, 337, 540);
  line(710, 170, 847, 170);

  rect(25, 650, 115, 55);
  noStroke();
  fill(255);
  ellipse(337, 540, 15, 15);
  ellipse(710, 170, 15, 15);
  fill(74, 114, 177);
  rect(25, 25, 25, 25);
  fill(191, 50, 118);
  rect(25, 60, 25, 25);
  noFill();
}


void draw() {

  //hombres 2004
  if ((mouseX>=390) && (mouseX<=645) &&(mouseY>=150) &&(mouseY<170))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 450, 450, 4.0491, 4.967486304);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("6488", 50, 680);
    noFill();
  } 
  //hombres 2005
  else if ((mouseX>=400) && (mouseX<=645) &&(mouseY>175) &&(mouseY<=190))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 370, 370, 4.0491, 5.0111280680583);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("7572", 50, 680);
    noFill();
  } 
  // hombres 2006
  else if ((mouseX>=430) && (mouseX<=600) &&(mouseY>195) &&(mouseY<=255))
  {

    stroke (237, 152, 0);  
    strokeWeight (10);
    arc (529, 359, 280, 280, 4.07, 4.948337441409);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("8692", 50, 680);
    noFill();
  } 
  // hombres 2007
  else if ((mouseX>=460) && (mouseX<=550) &&(mouseY>260) &&(mouseY<=295))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 185, 185, 4.15, 4.9335912470613);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("9670", 50, 680);
    noFill();
  } 
  //hombres 2008 
  else if ((mouseX>=500) && (mouseX<=540) &&(mouseY>300) &&(mouseY<=326))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 95, 95, 4.3, 4.63395332547);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("10690", 50, 680);
    noFill();
  } 
  
  //hombres 2009 
  else if ((mouseX>=510) && (mouseX<=620) &&(mouseY>301) &&(mouseY<=326))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    line (540, 344, 610, 274);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("11302", 50, 680);
    noFill();
  }
  //hombres 2010 
  else if ((mouseX>=555) && (mouseX<=600) &&(mouseY>360) &&(mouseY<=392))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 95, 95, -0.119, 0.5);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("11370", 50, 680);
    noFill();
  }
  //hombres 2011 
  else if ((mouseX>=601) && (mouseX<=620) &&(mouseY>340) &&(mouseY<=424))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 185, 185, -0.13, 0.63);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("10569", 50, 680);
    noFill();
  }

  //hombres 2012 
  else if ((mouseX>=625) && (mouseX<=672) &&(mouseY>340) &&(mouseY<=474))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 280, 280, -0.139, 0.69);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("9055", 50, 680);
    noFill();
  } 
  //hombres 2013 
  else if ((mouseX>=675) && (mouseX<=715) &&(mouseY>340) &&(mouseY<=494))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
     arc (529, 359, 370, 370, -0.1423, 0.74);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("7086", 50, 680);
    noFill();
  }
  
   //hombres 2014 
  else if ((mouseX>=716) && (mouseX<=745) &&(mouseY>330) &&(mouseY<=524))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 450, 450, -0.1428, 0.76);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("9409", 50, 680);
    noFill();
  }
  
  
  
  
  
  //mujeres 2004
 else if ((mouseX>=300) && (mouseX<=340) &&(mouseY>=230) &&(mouseY<290))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 450, 450, 3.378809744, 3.9);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("3307", 50, 680);
    noFill();
  } 
 //mujeres 2005
  else if ((mouseX>=343) && (mouseX<=385) &&(mouseY>240) &&(mouseY<=280))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 370, 370, 3.407923662, 3.88);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("3399", 50, 680);
    noFill();
  } 
  // mujeres 2006
 else if ((mouseX>=387) && (mouseX<=425) &&(mouseY>255) &&(mouseY<=290))
  {

    stroke (237, 152, 0);  
    strokeWeight (10);
    arc (529, 359, 280, 280, 3.327465262, 3.85);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("4676", 50, 680);
    noFill();
  } 
  // mujeres 2007
 else if ((mouseX>=430) && (mouseX<=450) &&(mouseY>295) &&(mouseY<=350))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 185, 185, 3.281383448, 3.8);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("5420", 50, 680);
    noFill();
  } 
  //mujeres 2008 
 else if ((mouseX>=480) && (mouseX<=490) &&(mouseY>300) &&(mouseY<=360))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
     arc (529, 359, 95, 95, 3.23918405, 3.67);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("6034", 50, 680);
    noFill();
  } 
 
  //mujeres 2009 
  else if ((mouseX>=481) && (mouseX<=510) &&(mouseY>361) &&(mouseY<=392))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    line (485, 399, 515, 369);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("6658", 50, 680);
    noFill();
  }
  //mujeres 2010 
  else if ((mouseX>=511) && (mouseX<=530) &&(mouseY>395) &&(mouseY<=410))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
     arc (529, 359, 95, 95, 1.1, 1.780765741);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("6762", 50, 680);
    noFill();
  }
  //mujeres 2011 
  else if ((mouseX>=491) && (mouseX<=550) &&(mouseY>424) &&(mouseY<=464))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 185, 185, 1, 1.867878371);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("6453", 50, 680);
    noFill();
  }

  //mujeres 2012 
  else if ((mouseX>=481) && (mouseX<=600) &&(mouseY>484) &&(mouseY<=509))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 280, 280, 0.94, 1.821861513);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("5486", 50, 680);
    noFill();
  } 
  //mujeres 2013 
  else if ((mouseX>=460) && (mouseX<=630) &&(mouseY>510) &&(mouseY<=545))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 370, 370, 0.92, 1.820060273);
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("4221", 50, 680);
    noFill();
  }
  
   //mujeres 2014 
  else if ((mouseX>=455) && (mouseX<=650) &&(mouseY>560) &&(mouseY<=600))
  {

    stroke (237, 152, 0);
    strokeWeight (10);
    arc (529, 359, 450, 450, 0.9, 1.805458942);  
    textFont(fuente, 30);
    fill(237, 152, 0); 
    text ("5722", 50, 680);
    noFill();
  }
  
  else 
  {
    stroke (255);
    strokeWeight (10);

    //hombres
    //2004
    arc (529, 359, 450, 450, 4.0491, 4.967486304);
    //2005
    arc (529, 359, 370, 370, 4.0491, 5.0111280680583);
    //2006
    arc (529, 359, 280, 280, 4.07, 4.948337441409);
    //2007
    arc (529, 359, 185, 185, 4.15, 4.9335912470613);
    //2008
    arc (529, 359, 95, 95, 4.3, 4.63395332547);
    //2009
    line (540, 344, 610, 274);
    //2014
    arc (529, 359, 450, 450, -0.1428, 0.76);
    //2013
    arc (529, 359, 370, 370, -0.1423, 0.74);
    //2012
    arc (529, 359, 280, 280, -0.139, 0.69);
    //2011
    arc (529, 359, 185, 185, -0.13, 0.63);
    //2010
    arc (529, 359, 95, 95, -0.119, 0.5);

    //mujeres
    //2004
    arc (529, 359, 450, 450, 3.378809744, 3.9);
    //2005
    arc (529, 359, 370, 370, 3.407923662, 3.88);
    //2006
    arc (529, 359, 280, 280, 3.327465262, 3.85);
    //2007
    arc (529, 359, 185, 185, 3.281383448, 3.8);
    //2008
    arc (529, 359, 95, 95, 3.23918405, 3.67);
    //2009
    //line (540,344,640,244);
    line (485, 399, 515, 369);
    //2014
    arc (529, 359, 450, 450, 0.9, 1.805458942);
    //2013
    arc (529, 359, 370, 370, 0.92, 1.820060273);
    //2012
    arc (529, 359, 280, 280, 0.94, 1.821861513);
    //2011
    arc (529, 359, 185, 185, 1, 1.867878371);
    //2010
    arc (529, 359, 95, 95, 1.1, 1.780765741);

    fill(48, 45, 45);
    strokeWeight(1);
    rect(25, 650, 115, 55);
    noFill();
  }
}
