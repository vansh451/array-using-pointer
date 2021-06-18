#include <iostream>
using namespace std;

int main()
{
    int data[5];
    int *ptr;
    ptr = data;
    cout << "Enter elements: ";

    for (int i = 0; i < 5; ++i)
    {
        cin >> data[i];
    }

    cout << "You entered: ";
    for (int i = 0; i < 5; ++i)
    {
        cout << endl
             << *(ptr);
        ptr++;
    }

    return 0;
}
