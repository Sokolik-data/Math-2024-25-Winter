## Extremum

6. The profit function is $P(u) = -2u^2 + 50u - 300$, where $u$ is the number of units sold. Find the number of units that maximize profit.

7. You have 10 meters of string, and you need to use it to enclose the largest possible rectangular. Find the dimensions of the rectangle.

8. Find extremum od $f(x) = x^2 + 3x - 5$.

9. Find extremum of $f(x) =\frac{x^2+2x+1}{x-1}$
---

***№6***

Chcemy znaleźć liczbę jednostek $ u $, która maksymalizuje funkcję zysku $ P(u) = -2u^2 + 50u - 300 $ (Мы хотим найти количество единиц $ u $, которое максимизирует функцию прибыли).

### Krok 1: Określenie rodzaju funkcji (Определить, что это за функция)
Jest to funkcja kwadratowa, która otwiera się w dół (ponieważ współczynnik przy $ u^2 $ jest ujemny: $-2$) i ma maksimum w wierzchołku paraboli (Это квадратичная функция, которая открывается вниз (поскольку коэффициент при $ u^2 $ отрицательный: $-2$) и имеет максимум в вершине параболы).

### Krok 2: Wzór na wierzchołek paraboli (Формула для вершины параболы)
Współrzędna wierzchołka dla funkcji w postaci $ ax^2 + bx + c $ jest obliczana za pomocą wzoru (Координата вершины для функции в виде $ ax^2 + bx + c $ вычисляется по формуле):
$$
u_{\text{max}} = -\frac{b}{2a}.
$$

W tym przypadku:
- $ a = -2 $,
- $ b = 50 $.

Podstawiamy wartości do wzoru:
$$
u_{\text{max}} = -\frac{50}{2(-2)} = -\frac{50}{-4} = 12.5.
$$

### Krok 3: Interpretacja (Интерпретация)
Liczba jednostek $ u $, która maksymalizuje zysk, wynosi $ \mathbf{12.5} $ (Количество единиц $ u $, которое максимизирует прибыль, равно $ \mathbf{12.5} $).

### Krok 4: Obliczenie maksymalnego zysku (опционально) (Вычисление максимальной прибыли)
Podstawiamy $ u = 12.5 $ do funkcji $ P(u) $, aby obliczyć maksymalny zysk (Подставляем $ u = 12.5 $ в функцию $ P(u) $, чтобы вычислить максимальную прибыль):
$$
P(12.5) = -2(12.5)^2 + 50(12.5) - 300.
$$
$$
P(12.5) = -2(156.25) + 625 - 300.
$$
$$
P(12.5) = -312.5 + 625 - 300 = 12.5.
$$

Maksymalny zysk wynosi $ 12.5 $ 
---

***№7***

Mamy 10 metrów sznurka, który trzeba użyć, aby ogrodzić prostokąt o jak największym polu (У нас есть 10 метров верёвки, которые нужно использовать, чтобы оградить прямоугольник с наибольшей площадью). Znajdźmy wymiary takiego prostokąta (Найдём размеры такого прямоугольника).

---

### Krok 1: Zapiszmy wzory (Шаг 1: Запишем формулы)
Niech długość prostokąta będzie $ l $, a szerokość $ w $ (Пусть длина прямоугольника будет $ l $, а ширина $ w $). Obwód prostokąta wynosi (Периметр прямоугольника равен):
$$
2l + 2w = 10.
$$

Uprośćmy to równanie (Упростим это уравнение):
$
l + w = 5 \quad \text{(dzielimy obie strony przez 2) (делим обе стороны на 2)}.
$

---

### Krok 2: Wyraźmy szerokość przez długość (Шаг 2: Выразим ширину через длину)
Z równania $ l + w = 5 $ wyznaczamy szerokość $ w $ (Из уравнения $ l + w = 5 $ выражаем ширину $ w $):
$$
w = 5 - l.
$$

---

### Krok 3: Zapiszmy wzór na pole (Шаг 3: Запишем формулу площади)
Pole prostokąta wyraża się jako (Площадь прямоугольника выражается как):
$$
A = l \cdot w.
$$

Podstawiamy $ w = 5 - l $ do wzoru (Подставляем $ w = 5 - l $ в формулу):
$$
A = l \cdot (5 - l).
$$

Rozwijamy nawiasy (Раскрываем скобки):
$$
A = 5l - l^2.
$$

---

### Krok 4: Znajdźmy długość maksymalizującą pole (Шаг 4: Найдём длину, которая максимизирует площадь)
Funkcja $ A = 5l - l^2 $ jest kwadratowa, a ponieważ współczynnik przy $ l^2 $ jest ujemny ($ -1 $) (Функция $ A = 5l - l^2 $ является квадратичной, и поскольку коэффициент при $ l^2 $ отрицательный ($ -1 $), wykres funkcji to parabola otwierająca się w dół (график функции — парабола, открывающаяся вниз). Maksymalne pole osiągane jest w wierzchołku paraboli (Максимальная площадь достигается в вершине параболы).

Współrzędna wierzchołka paraboli dla funkcji w postaci $ ax^2 + bx + c $ obliczana jest ze wzoru (Координата вершины параболы для функции вида $ ax^2 + bx + c $ вычисляется по формуле):
$$
l_{\text{max}} = -\frac{b}{2a}.
$$

W naszym przypadku (В нашем случае):
- $ a = -1 $,
- $ b = 5 $.

Podstawiamy wartości (Подставляем значения):
$$
l_{\text{max}} = -\frac{5}{2(-1)} = \frac{5}{2} = 2.5.
$$

Zatem długość prostokąta maksymalizująca pole wynosi $ l = 2.5 $ (Таким образом, длина прямоугольника, которая максимизирует площадь, равна $ l = 2.5 $).

---

### Krok 5: Znajdźmy szerokość (Шаг 5: Найдём ширину)
Szerokość można obliczyć z równania $ w = 5 - l $ (Ширину можно вычислить из уравнения $ w = 5 - l $):
$$
w = 5 - 2.5 = 2.5.
$$

---

### Krok 6: Sprawdźmy (Шаг 6: Проверим)
Prostokąt o długości $ l = 2.5 $ i szerokości $ w = 2.5 $ jest kwadratem (Прямоугольник с длиной $ l = 2.5 $ и шириной $ w = 2.5 $ является квадратом). To jest zgodne z oczekiwaniami, ponieważ dla danego obwodu maksymalne pole ma kwadrat (Это соответствует ожиданиям, так как для заданного периметра максимальную площадь имеет квадрат).

---

### Odpowiedź (Ответ):
Wymiary prostokąta maksymalizującego pole to (Размеры прямоугольника, который максимизирует площадь, следующие):
$$
\boxed{2.5 \, \text{m} \times 2.5 \, \text{m}}.
$$
---

***№8***

Znajdźmy ekstremum funkcji $ f(x) = x^2 + 3x - 5 $ (Найдём экстремум функции $ f(x) = x^2 + 3x - 5 $). Jest to funkcja kwadratowa, więc jej wykres to parabola (Это квадратичная функция, поэтому её график — парабола). Współczynnik przy $ x^2 $ jest dodatni ($ a = 1 $) (Коэффициент при $ x^2 $ положительный ($ a = 1 $)), co oznacza, że parabola otwiera się w górę, a funkcja ma minimum (что означает, что парабола открывается вверх, и функция имеет минимум).

---

### Krok 1: Znajdźmy wierzchołek paraboli (Шаг 1: Найдём вершину параболы)
Współrzędna $ x $ wierzchołka dla funkcji w postaci $ ax^2 + bx + c $ obliczana jest ze wzoru (Координата $ x $ вершины для функции вида $ ax^2 + bx + c $ вычисляется по формуле):
$$
x_{\text{wierzchołka}} = -\frac{b}{2a}.
$$

W naszym przypadku (В нашем случае):
- $ a = 1 $,
- $ b = 3 $,
- $ c = -5 $.

Podstawmy wartości (Подставим значения):
$$
x_{\text{wierzchołka}} = -\frac{3}{2 \cdot 1} = -\frac{3}{2}.
$$

---

### Krok 2: Obliczmy wartość funkcji w wierzchołku (Шаг 2: Найдём значение функции в вершине)
Podstawmy $ x = -\frac{3}{2} $ do funkcji $ f(x) $, aby znaleźć minimum (Подставим $ x = -\frac{3}{2} $ в функцию $ f(x) $, чтобы найти минимум):
$$
f\left(-\frac{3}{2}\right) = \left(-\frac{3}{2}\right)^2 + 3 \cdot \left(-\frac{3}{2}\right) - 5.
$$

Obliczmy krok po kroku (Посчитаем шаг за шагом):
$$
f\left(-\frac{3}{2}\right) = \frac{9}{4} - \frac{9}{2} - 5.
$$

Sprowadźmy do wspólnego mianownika ($ 4 $) (Приведём к общему знаменателю ($ 4 $)):
$$
f\left(-\frac{3}{2}\right) = \frac{9}{4} - \frac{18}{4} - \frac{20}{4}.
$$

Dodajmy ułamki (Сложим дроби):
$$
f\left(-\frac{3}{2}\right) = \frac{9 - 18 - 20}{4} = \frac{-29}{4}.
$$

---

### Odpowiedź (Ответ):
Minimum funkcji osiągane jest przy $ x = -\frac{3}{2} $, a wartość funkcji w tym punkcie wynosi $ f(x) = -\frac{29}{4} $ (Минимум функции достигается при $ x = -\frac{3}{2} $, а значение функции в этой точке равно $ f(x) = -\frac{29}{4} $).

Zatem ekstremum funkcji to (Таким образом, экстремум функции равен):
$$
\boxed{x = -\frac{3}{2}, \, f(x) = -\frac{29}{4}}.
$$
---


***№9***

Znajdźmy ekstremum funkcji $ f(x) = \frac{x^2 + 2x + 1}{x - 1} $ (Найдём экстремум функции $ f(x) = \frac{x^2 + 2x + 1}{x - 1} $).

---

### Krok 1: Uprośćmy licznik (Шаг 1: Упростим числитель)
Licznik funkcji (Числитель функции):
$$
x^2 + 2x + 1 = (x + 1)^2.
$$
Zatem funkcja przyjmuje postać (Таким образом, функция принимает вид):
$$
f(x) = \frac{(x + 1)^2}{x - 1}.
$$

---

### Krok 2: Znajdźmy pochodną (Шаг 2: Найдём производную)
Użyjmy reguły pochodnej ilorazu (Используем правило производной частного):
$$
f'(x) = \frac{u'v - uv'}{v^2},
$$
gdzie $ u = (x + 1)^2 $ i $ v = x - 1 $ (где $ u = (x + 1)^2 $ и $ v = x - 1 $).

1. Znajdźmy $ u' $ (Найдём $ u' $):
$$
u' = 2(x + 1).
$$

2. Znajdźmy $ v' $ (Найдём $ v' $):
$$
v' = 1.
$$

3. Podstawmy do wzoru (Подставим в формулу):
$$
f'(x) = \frac{2(x + 1)(x - 1) - (x + 1)^2}{(x - 1)^2}.
$$

---

### Krok 3: Uprośćmy wyrażenie (Шаг 3: Упростим выражение)
Rozwińmy nawiasy w liczniku (Раскроем скобки в числителе):
$$
f'(x) = \frac{2(x + 1)(x - 1) - (x + 1)^2}{(x - 1)^2}.
$$

Rozwińmy $ 2(x + 1)(x - 1) $ (Раскроем $ 2(x + 1)(x - 1) $):
$$
2(x + 1)(x - 1) = 2(x^2 - 1).
$$

Rozwińmy $ (x + 1)^2 $ (Раскроем $ (x + 1)^2 $):
$$
(x + 1)^2 = x^2 + 2x + 1.
$$

Podstawmy (Подставим):
$$
f'(x) = \frac{2(x^2 - 1) - (x^2 + 2x + 1)}{(x - 1)^2}.
$$

Uprośćmy licznik (Упростим числитель):
$$
2(x^2 - 1) = 2x^2 - 2,
$$
$$
2x^2 - 2 - (x^2 + 2x + 1) = 2x^2 - 2 - x^2 - 2x - 1 = x^2 - 2x - 3.
$$

Zatem pochodna wynosi (Таким образом, производная равна):
$$
f'(x) = \frac{x^2 - 2x - 3}{(x - 1)^2}.
$$

---

### Krok 4: Znajdźmy punkty krytyczne (Шаг 4: Найдём критические точки)
Punkty krytyczne to miejsca, gdzie $ f'(x) = 0 $ lub pochodna nie istnieje (Критические точки — это места, где $ f'(x) = 0 $ или производная не существует).

1. $ f'(x) = 0 $, gdy licznik jest równy zeru (если числитель равен нулю):
$$
x^2 - 2x - 3 = 0.
$$

Rozwiążmy równanie kwadratowe (Решим квадратное уравнение):
$$
x^2 - 2x - 3 = (x - 3)(x + 1) = 0.
$$
Zatem $ x = 3 $ lub $ x = -1 $ (Следовательно, $ x = 3 $ или $ x = -1 $).

2. Pochodna nie istnieje, gdy mianownik jest równy zeru (Производная не существует, если знаменатель равен нулю):
$$
(x - 1)^2 = 0 \implies x = 1.
$$

---

### Krok 5: Zbadajmy punkty krytyczne (Шаг 5: Исследуем критические точки)
Wykluczamy $ x = 1 $, ponieważ funkcja $ f(x) $ nie jest zdefiniowana w tym punkcie (Исключаем $ x = 1 $, так как функция $ f(x) $ не определена в этой точке). Zbadajmy zachowanie $ f'(x) $ w otoczeniu $ x = 3 $ i $ x = -1 $ (Исследуем поведение $ f'(x) $ в окрестностях $ x = 3 $ и $ x = -1 $).

1. Dla $ x = -1 $ (Для $ x = -1 $):
$$
f(x) = \frac{(-1 + 1)^2}{-1 - 1} = 0.
$$

2. Dla $ x = 3 $ (Для $ x = 3 $):
$$
f(x) = \frac{(3 + 1)^2}{3 - 1} = \frac{16}{2} = 8.
$$

---

### Odpowiedź (Ответ):
Ekstrema funkcji to (Экстремумы функции):
- Minimum dla $ x = -1 $, $ f(x) = 0 $ (Минимум при $ x = -1 $, $ f(x) = 0 $);
- Maksimum dla $ x = 3 $, $ f(x) = 8 $ (Максимум при $ x = 3 $, $ f(x) = 8 $).
