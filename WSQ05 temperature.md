#WSQ05
Here's the code


      #include <iostream>
      using namespace std;
      
      int main (){
      int F,c;
      	cout<<"Introduce los grados Fahrenheit: "<<endl;
      	cin>> F;
      
      	c=5*(F-32)/9;
      	cout<<"Los grados "<<F<<" Fahrenheit en grados centigrados son: " <<c<<endl;
      
      	if (c>=100){
      		cout<<"El agua a esta temperatura sí hierve"<<endl;
      
      	}
      		else{
      			cout<<"El agua a esta temperatura no hierve" <<endl;
      
      		}
      	return 0;
      }
