#WSQ07
Here is my code


      #include <iostream>
      using namespace std;
      
      
      int main(){
      	int x,y,z,validacion,resultado,suma;
      
      	do{
      		cout<<"Escribe tu numero más pequeño"<<endl;
      		cin>>x;
      		cout<<"Escribe tu numero más grande"<<endl;
      		cin>>y;
      
      		if(x<y){
      			validacion = 0;
      		}
      		else {
      			cout<<endl<<"Escribiste los numeros incorrectamente"<<endl;
      			validacion = 10;
      		}
      	} while(validacion==10);
      
      	if (validacion==0){
      		z=(y-x)+1;
      
      		suma=0;
      
      
      		for(int i=0; i<z; i++){
      			resultado= (x+i);
      			suma = suma + resultado;
      		}
      	
      		cout<<"El resultado de "<<x<<" a "<<y<<" es = "<<suma;
      	}
      
      	return 0;
      }
