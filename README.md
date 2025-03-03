# -d-di-ortanin-tapilmasi-c-
task c++ ədədi ortasi
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Nece eded daxil edeceksiniz? ";
    cin >> n;

    double sum = 0, num;
    for (int i = 0; i < n; i++) {
        cout << "Ededi daxil edin: ";
        cin >> num;
        sum += num;
    }

    double ededi_orta = sum / n;
    cout << "Ededi orta: " << ededi_orta << endl;

    return 0;
}

