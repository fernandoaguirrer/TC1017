#WSQ14
Here is my code:


      #include <iostream>
      using namespace std;
      
      int factorial(int precision){
      	if(precision == 0){
      		return 1;
      	}else{
      		precision = precision*factorial(precision-1);
      	}
      }
      int e(){
      	int aproximacion;
      	float e;
      	float suma=0;
      
      	cout<<"Introduzca la aproximacion deseada de e: "<<endl;
      	cin>>aproximacion;
      
      	for(int precision=0; precision<=aproximacion; precision++){
      		e = 1.0/factorial(precision);
      		suma = suma + e;
      	}
      	cout<<" e = " << suma;
      }
      
      int main(){
      
      	e();
      
      return 0;
      }
