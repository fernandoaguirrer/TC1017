Here is my code fixed
q2

      #include <iostream>
      using namespace std;
      //Jesús Fernando Aguirre Robles A01224994
      
      int superpower(int a, int b){
      	int resultado;
      	
      	resultado=1;
      	for(int i=1; i<=b; i++){
      		resultado=resultado*a;}
      	return resultado;
      	}
      	
      	
      	int main(){
      		
      		int a,b;
      		cout<<"Ingresa el primer número: "<<endl;
      		cin>>a;
      		
      		cout<<"Ingresa la potencia a la que quieres elevar el número: "<<endl;
      		cin>>b;
      		
      		cout<<a<<" elevado a la potencia "<<b<<" es igual a "<<superpower(a,b)<<endl;
      		
      		return 0;
      	}
