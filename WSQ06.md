WSQ06
Here is the code


      #include <iostream>
      #include <cstdlib>
      #include <ctime>
      
      using namespace std;
      
      int main() {
      	int y, intentos=0;
      	srand((unsigned)time(0));
      	int x = (rand()%10)+1;
      
      	do {
      	
      	cout<<"Introduce un numero al azar entre 1 y 10. Tienes " << (5-intentos)<< " oportunidades"<<endl;
      	cin>> y;
      
      	intentos = intentos+1;
      
      	if (y>x){
      		cout<< "Lo siento " <<y<< " es muy grande. Intenta otra vez."<<endl;
      		cout<< "Te quedan " <<(5-intentos)<< " intentos"<<endl <<endl;
      	}
      		else if (y<x){
      			cout<<"Lo siento "<<y<< " es muy pequeño. Intenta otra vez."<<endl;
      			cout<<"Te quedan "<< (5-intentos)<< " intentos"<<endl <<endl;
      		}
      			else if (y=x){
      				cout<<"Felicidades, haz acertado al número. La respuesta correcta era "<< x <<endl<< "Faltaban "<< (5-intentos)<< " intentos para perder";
      				intentos=5;
      			}
      	} while (intentos<5);
      
      	return 0;
      }
