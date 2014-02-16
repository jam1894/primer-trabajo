primer-trabajo
==============

#include &lt;iostream>  using namespace std;  int main() {     int numf=0, numi=0, c=0, res=0, k=0;        cout&lt;&lt;"Digite el numero inicial del rango: ";     cin>>numi;     cout&lt;&lt;"Digite el numero final del rango: ";      cin>>numf;     cout&lt;&lt;"Los numeros primos entre "&lt;&lt;numi&lt;&lt; " y "&lt;&lt;numf&lt;&lt; " son: ";          for(numi=numi; numi&lt;=numf; numi++)          {         for(c=1; c&lt;=numi; c++)         {             res=numi%c;             if(res==0)             {                 k=k+1;             }         }                  if(k==2)         {             cout&lt;&lt;" "&lt;&lt;numi;         }         k=0;   }      cout&lt;&lt;endl&lt;&lt;endl;   system("pause"); }
