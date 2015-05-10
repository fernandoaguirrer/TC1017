Here is my code fixed
q3


      #include <iostream>
      using namespace std;
      
      //Jesús Fernando Aguirre Robles A01224994
      
      long fibonacci(long x){
      	long a,b,f;
      	if(x==0){
      		f=0;
      	}
      	a=0;
      	b=1;
      
      	for(int i=0; i<x; i++){
      		f=a+b;
      		b=a;
      		a=f;
      	}
      	return f;
      }
      	int main(){
      		int n;
      		
      	cout<<"Que número de la serie quieres?"<<endl;
      	cin>>n;
      	
      	cout<<"El fibonacci de ese numero es: "<<fibonacci(n)<<endl;
      	
      	return 0;
      }
