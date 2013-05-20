#include "stdafx.h"
#include <iostream>
#include <string>
#include <conio.h>

using namespace std;

class Car
{
public:
//---------------------Type------------------------
string setTypeCar( string Type )
{ 
TypeCar = Type; 
}
//int 
string getTypeCar() 
{ 
return TypeCar; 
} 
//---------------------Price------------------------
void setPriceCar( int Price )
{
PriceCar=Price;
}
int getPriceCar()
{
return PriceCar;
}
//---------------------Way------------------------
void setWayCar( int Way )
{
WayCar=Way;
}
int getWayCar()
{
return WayCar;
}
void displayMessage()
{
cout<<"Way:"<<getWayCar() <<endl;
cout<<"Type:"<<getTypeCar()<<endl;
cout<<"Price:"<<getPriceCar()<<endl;
}
private:
string TypeCar; 
int PriceCar;
int WayCar;
//int; 

int main()
{
string TypeCar; 
int PriceCar;
int WayCar;
Car myCar; 


cout<< myCar.getTypeCar()<<endl;


cout<<"\nPlease enter the car type:"<<endl;
cin>>TypeCar; 
myCar.setTypeCar( TypeCar );

cout<<"\nPlease enter the car price:"<<endl;
cin>>PriceCar; 
myCar.setPriceCar( PriceCar );

cout<<"\nPlease enter the car way:"<<endl;
cin>>WayCar; 
myCar.setWayCar( WayCar );

myCar.displayMessage(); 

cout<<endl;

getch();
}
}
