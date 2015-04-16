# quiz-9.4

#include <iostream>
#include <string>

using namespace std;

bool qwert(string x){
    string u, z;
    
    u = x;
    
    reverse(x.begin(),x.end());
    
    if (u == x){
        
        cout << "Es la misma palabra" << endl;
    }
    else{
        
        cout << "No es la misma palabra" << endl;
        
    }
    
    return 0;
}

int main(){
    string x, u;
    
    cout << "Palabra" << endl;
    cin >> x;
    
    qwert(x);
    
    return 0;
}
