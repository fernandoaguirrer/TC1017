#WSQ08
Here is my code:


      #include <iostream>
      using namespace std;
      
      void newline(){
      	cout<<endl;
      }
      
      double sum(double x,double y){
      	return x+y;}
      double sust(double x,double y){
      	return x-y;}
      double prod(double x,double y){
      	return x*y;}
      double div(double x,double y){
      	return x/y;}
      double mod(int x,int y){
      	return x%y;}
      
      int main(){
      
      double x,y;
      
      	cout<<"Dame el primer número: "<<endl;
      	cin>>x;
      	cout<<"Dame el segundo valor"  <<endl;
      	cin >>y;
      	newline();
      	cout<<"El resultado de la suma es: "<<sum(x,y)<<endl;
      	newline();
      	cout<<"El resultado de la resta es: "<<sust(x,y)<<endl;
      	newline();
      	cout<<"El resultadode la multiplicación es: "<<prod(x,y)<<endl;
      	newline();
      	cout<<"El resultado de la división es: "<<div(x,y)<<endl;
      	newline();
      	cout<<"El residuo de la división es: "<<mod(x,y)<<endl;
      
      	return 0;
      
      }
