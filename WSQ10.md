#WSQ10
Here is my code:



      #include <iostream>
      #include <cmath>
      using namespace std;
      float sum(float num[10]){
      	
      	float x=0;
      	for(int y=0;y<10;y++){
      		x=x+num[y];	}
      	return x;
      	}
      
      float ave(float num[10]){
      	float prom;
      	prom=sum(num)/10;
      	return prom;
      	}
      
      float desv(float num[10]){
      	
      	float var=0;
      	float des=0;
      	for(int f=0;f<10;f++){
      		var=var+pow(num[f]-ave(num),2);
      	}
      	
      	des=pow(var/10,.5);
      	return des;
      	}
      
      int main(){
      
      float num[10];
      
      	for(int i=0;i<10;i++){
      	
      		cout<<"Ingresa un número: "<<endl;
      		cin>>num[i];
      		}	
      	
      	cout<<"El resultado de la suma de tus números es: "<<sum(num)<<endl;
      	cout<<"El promedio de los numeros que ingresaste es: "<<ave(num)<<endl;
      	cout<<"La desviación estandar de tus números es: "<<desv(num)<<endl;
      
      	return 0;
      }

