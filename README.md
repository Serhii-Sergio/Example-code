
 std::locale().global(std::locale(""));


Тест:
#include <iostream>
 
int main()
{
    std::locale().global(std::locale(""));
    std::cout<<"Привіт!\n";
    return 0;
}
