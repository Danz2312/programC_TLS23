#include <iostream>
#include <cmath>
using namespace std;
int main()
{
    float lokIdeal,jarakAntara,i,j;
    int pendudukA,pendudukB,f;
    
    cout<<"jarak antara dua kota (meter):";
    cin>>jarakAntara;
    cout<<endl;
    
    
    
    cout<<"jumlah penduduk kota A (jiwa):";
    cin>>pendudukA;
    cout<<endl;
    
    cout<<"jumlah penduduk kota B (jiwa):";
    cin>>pendudukB;
    cout<<endl;
    
    if(pendudukA<pendudukB)
    
    i=sqrt(pendudukB/pendudukA);
    else
    i=sqrt(pendudukA/pendudukB);
    
    i++;
  
    
    
    lokIdeal=jarakAntara/i;
    
    cout<<endl;
    if(pendudukA<pendudukB)
    {
        cout<<"jarak ideal infrastruktur dari kota A (meter):"<<lokIdeal<<endl;
        cout<<"jarak ideal infrastruktur dari kota B (meter):"<<jarakAntara-lokIdeal<<endl;
    }
    else
    {
        cout<<"jarak ideal infrastruktur dari kota B (meter):"<<lokIdeal<<endl;
        cout<<"jarak ideal infrastruktur dari kota A (meter):" <<jarakAntara-lokIdeal<<endl;
    }
    return 0;
}
