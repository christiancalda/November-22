# November-22

#include <iostream>
using namespace std;
int main() {
    int marks[5];
    for (int i=0; i<5; i++)
    {
        cout << "Enter a number" << endl;
        cin >> marks[i];
    }
    
        for (int j =0; j <5; j++)
        
    {
        cout << "The numbers are:";
        cout << marks[j];
        
    }
        
    

    return 0;
}
                        
                        
--------------------------------------------------------------------------------------------------------------------------------
                        
                        
   #include <iostream>
using namespace std;
int main() {
    
    string snacks [3][4]= {
        {"Cheetos","Piatos","DingDong"},// first throw
        {"Flavoured Youghurt", "Oman chips","Oreo", "Lays"}, // second row
        {"hotdog","nuggets","eggs","bacon"} // third row
        
        };
        
        for (int i = 0; i < 3; i++){
            for(int j = 0; j < 4; j++)
            {
                cout << snacks[i][j] << endl; 
            }
        }
       

    return 0;
}
  
  ------------------------------------------------------------------------------------------------------------
  
  #include <iostream>
using namespace std;
int main() {
    
    string art[5][1]= {
        {"-----"},// first throw
        {"-o-o-"}, // second row
        {"-@@@-"}, // third row
        {"-vvv-"},// fourth row
        {"-xxx-"}// fifth row
        };
        
        for (int i = 0; i < 5; i++){
            for(int j = 0; j < 1; j++)
            {
                cout << art[i][j] << endl; 
            }
        }
       

    return 0;
}
