//Circle.java
//Yangyang Lian

class Circle

{

private double x,y,radius;

  

void setX(double value){this.x=value;}

double getX(){return this.x;}

void setY(double value){this.y=value;}

double getY(){return this.y;}

void setRadius(double value){this.radius=value;}

double getRadius(){return this.radius;}

double getArea(){return Math.PI*Math.pow(this.radius,2);}

boolean doesOverlap(Circle otherCircle){

double distance,radius_sum;

radius_sum=this.radius+otherCircle.radius;

distance=Math.sqrt(Math.pow((this.x-otherCircle.x),2)+Math.pow((this.y-otherCircle.y),2));


if(radius_sum>=distance){return true;}

else{return false;}

}

}

//CircleTester.java

public class CircleTester{

public static void main(String[] args){

Circle c1=new Circle();

c1.setX(8);

c1.setY(-6);

c1.setRadius(5);

Circle c2=new Circle();

c2.setX(2);

c2.setY(3);

c2.setRadius(12);

Circle c3=new Circle();

c3.setX(15);

c3.setY(28);

c3.setRadius(10);

System.out.printf("Circle c1 Area: %.2f",c1.getArea());

System.out.printf("\nCircle c2 Area: %.2f",c2.getArea());

System.out.printf("\nCircle c3 Area: %.2f",c3.getArea());

System.out.println("\n\nCircles c1 and c2 Overlap: "+c1.doesOverlap(c2));

System.out.println("Circles c2 and c3 Overlap: "+c2.doesOverlap(c3));

}

}

