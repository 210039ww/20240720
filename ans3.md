#include <iostream>

using namespace std;

int main() {
    // 印出九九乘法表
    for (int i = 1; i <= 9; ++i) {
        for (int j = 1; j <= 9; ++j) {
            cout << i << " * " << j << " = " << i * j << "\t";
        }
        cout << endl;
    }

    return 0;
}


gemini
#include <iostream>

using namespace std;

int main() {
  for (int i = 1; i <= 9; i++) {
    for (int j = 1; j <= 9; j++) {
      cout << i << " x " << j << " = " << i * j << "\t";
    }
    cout << endl;
  }

  return 0;
}
