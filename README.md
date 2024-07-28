# freshstart
#include <iostream>
using namespace std;
int main(){
    
    char weekdays;
    cout<<"enter the charater";
    cin>>weekdays;
    
    switch (weekdays){
        case'a':
            cout<<"monday"<<endl;
            break;
        case'b':
            cout<<"tuesday"<<endl;
            break;
        case'c':
            cout<<"wednesday"<<endl;
            break; 
        case'd':
            cout<<"thursday"<<endl;
            break;
        case'e':
            cout<<"friday"<<endl;
            break; 
        case'f':
            cout<<"saturday"<<endl;
            break;
        case'g':
            cout<<"sunday"<<endl;
            break; 
        
        default:
            cout<<"none!"<<endl;
            break;
    }
    return 0;
        
        
        
        
        
        
            
    
}
