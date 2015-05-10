      #WSQ13
      Aquí está mi código:
      
      #include <iostream>
      using namespace std;
      
      float raiz(float x){
      	
      	double e=x, a =0;
      
      	while (a!= e){
      		a =e;
      		e = (x/e +e)/2; 
      	}
      
      	return e;
      }
      
      int main(){
      	
      	float x;
      
      	cout << "Introduce el numero que desea calcular su raíz cuadrada" << endl;
      	cin >> x;
      
      	cout << "La raíz cuadrada de "  << x << " es " << raiz(x) << endl;
      
      	return 0;
      }
