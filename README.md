# LECTURE-15-Part-2
#include <iostream>
using namespace std;
string function(int user) {
          if (user >= 0 && user <= 11) {
            cout << "good morning";
          }else if (user >= 12 && user <= 17) {
            cout << "good afternoon";
          }else if (user >= 18 && user <= 21) {
            cout << "good evening";
          }else if (user >= 22 && user <= 24) {
            cout << "good night";
          }
          else {
            cout << "Invalid input" << endl;
          }
          string exit;
          return exit;
        }
        int main() {
          int userTime;
          cout << "Enter time (0-24 only): "; cin >> userTime;
          function(userTime);
          return 0;
