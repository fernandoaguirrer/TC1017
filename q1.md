Here is my code fixed
Q1

      #include <iostream>
      using namespace std;
      //Jesús Fernando Aguirre Robles A01224994
      
      void triangles(int x){
      	for(int i=1; i<=x; i++){
      		for(int k=1; k<=i; k++){
      		cout<<"T";
      		}
      		cout<<endl;
      	}
      	for(int j=x; j>0; j--){
      		for(int l=1; l<=j; l++){
      		cout<<"T";
      		}
      		cout<<endl;
      	}
      }
      	
      	int main(){
      	int n;
      	 	cout<<"Ingresa el tamaño del triangulo"<<endl;
      	 	cin>>n;
      	 
      	 triangles(n);
      	}
