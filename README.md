#include <iostream>

int main() {
    double m, b, x, y;

    // Введите коэффициенты m и b
    std::cout << "Введите коэффициенты m и b: ";
    std::cin >> m >> b;

    // Введите значение x
    std::cout << "Введите значение x: ";
    std::cin >> x;

    // Решение уравнения прямой
    y = m * x + b;

    // Вывод результата
    std::cout << "Значение y для x = " << x << ": " << y << std::endl;

    return 0;
}

