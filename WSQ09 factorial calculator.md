#WSQ09
Here is my code:


      #include <iostream>
      using namespace std;
      
      void newline(){
      	cout<<endl;}
      
      int main(){
      	
      	int x,fact;
      	char respuesta;
      
      	newline();
      	cout<<"Quieres calcular el factorial de un número? sí(s), no(n)."<<endl;
      	cin>>respuesta;
      	newline();
      
      	do{
      		cout<<"Introduce el número para calcular el factorial"<<endl;
      		cin>>x;
      
      		fact=1;
      		
      		for(int i=1;i<=x;i++){
      			fact=fact*i;
      
      		}
      
      		cout<<"El factorial de "<<x<<" es "<<fact<<endl;
      		newline();
      		cout<<"Desea volver a calcular otro factorial? sí(s), no(n)."<<endl;
      		cin>>respuesta;
      		newline();
      		
      	} while(respuesta=='s');
      
      		if(respuesta=='n'){
      			newline();
      			cout<<"Muchas gracias, que tengas un buen dia!"<<endl;
      		}
      		
      		return 0;
      }
