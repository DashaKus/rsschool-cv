#cv Dasha Busel

1. Dasha Busel
2. email adress: busel.2002@bk.ru 
   phone number: +375296282350
3. I am stadying in the university at the Faculty of Radiophysics and Electronics. I want to develop in the IT sphere, imorove my English level, create new proj ects
4. I learn C++ and java, I know the principles of OOP, can using git and github, know basic things of the web programmig and HTML.
5. It is a part of code where I stade how to work with functions(write in c++):
```
#include<iostream>
#define _USE_MATH_DEFINES
#include<math.h>
using std::cout;

double summa(double x)
{
double y;
	y= (sin(M_PI * x * x) + log(x * x)) / (sin(M_PI * x * x) + sin(x) + log(x * x) + x * x
		+ pow(M_E,cos(x)));
	return y;
}	

int main()
{
	double x = 2;
	cout << summa(x);
}	
```
	This is part of code where I Write caculatior for food on java:
	```
	package Rfict.java.laba_1.Busel;

import java.sql.SQLOutput;

public class Mainclass<args> {
    public static void main(String[] args) throws Exception{
        Potatoe one=new Potatoe("fri");
        System.out.println();
      //  one.consume();
        Food[] breakfast=new Food[20];
        int counter=0;
        int calories=0;

        for(String i:args)              //бурум значения с того странного окошка
        {
            String[] parts = i.split("/");
            if(parts[0].equals("Apple"))
            {
                breakfast[counter]=new Apple(parts[1].toUpperCase());
                breakfast[counter].consume();
            }
            if(parts[0].equals("Cheese"))
            {
                breakfast[counter]=new Cheese();
                breakfast[counter].consume();
            }
            if(parts[0].equals("Potatoe"))
            {
                breakfast[counter]=new Potatoe(parts[1].toUpperCase());
                breakfast[counter].consume();
            }
            if(parts[0].equals("-calories")){calories =0;}
            else calories=-1;
            counter++;
        }
        int counter_2 = 0;
        if(calories==0)
        {
        for(String j:args) {
            String[] parts_2 = j.split("/");
            calories+= breakfast[counter_2].calculateCalories();
            counter_2++;
        }
         }
        System.out.println("aaaaaa");
        System.out.println("Calories of breakfast is: " + calories);

    }
}
```
6. All works which I do it is laboratory works and some tasks in the university.
7. I listen lectures about sintaksis of c++ and java, princepeles of OOP, security pratocols, cervlets, gsp, multithreading, and basics things in the web development.
8. Me level of English is A2
