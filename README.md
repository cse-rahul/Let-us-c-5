# Let-us-c-5
Q.(e) The length &amp; breadth of a rectangle and radius of a circle are input through the keyboard. Write a program to calculate area &amp; perimeter of the rectangle and area &amp; circumference of the circle.



      #include<stdio.h>
      int main()
    {
      	float l,b,a,r,c;
	       printf("enter the lenght, breadth of rectangle and radius of circle\n");
	
	       printf("l=");	scanf("%f",&l);
	       printf("b=");	scanf("%f",&b);

         a=l*b;
	
       	printf("area of rectangle=%f\n",a);
       	printf("r=");	scanf("%f",&r);

	     	c=3.14*r*r;
	      printf("area of circle=%f\n",c);

	    return 0;
	
     }
