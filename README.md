// Asignment #2
/*
Purpose: Calculate the volume of a cylinder, given the radius and height.
//Formula: V=pi*r^2*h  volume calculation
           
*/
using namespace std;
#include <iostream>
#include <cmath>
int main()
{
    double radius;        
    double height;        
    double volume;        
    const double pi=acos(-1);
      cout<<"Enter the radius of the cylinder";
      cin>>radius;
      cout<<"Enter the height of the cylinder";
      cin>>height;
         volume = pi*pow(radius,2.)*height;
         cout<<"\nThe volume of the cylinder is "<<volume;
      system("pause");
}
