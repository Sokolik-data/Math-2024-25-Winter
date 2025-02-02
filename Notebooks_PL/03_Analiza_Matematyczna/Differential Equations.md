## Differential Equations

***№1***

Aby rozwiązać dane równanie różniczkowe pierwszego rzędu:
$$ y'(x) = y $$
(Aby решить данное дифференциальное уравнение первого порядка:)

1. Jest to liniowe równanie różniczkowe pierwszego rzędu i jest przykładem równania z separowalnymi zmiennymi.
(Это уравнение является линейным дифференциальным уравнением первого порядка и является примером уравнения с разделяющимися переменными.)

2. Rozdziel zmienne $y$ i $x$:
$$ \frac{dy}{dx} = y $$
$$ \frac{dy}{y} = dx $$
(Разделим переменные $y$ и $x$:)

3. Zintegruj obie strony:
$$ \int \frac{dy}{y} = \int dx $$
$$ \ln |y| = x + C $$
gdzie $C$ to stała całkowania.
(Интегрируем обе части:)

4. Użyj funkcji wykładniczej dla obu stron, aby rozwiązać względem $y$:
$$ |y| = e^{x + C} $$
$$ y = \pm e^C e^x $$
(Воспользуемся экспонентой обеих частей для решения относительно $y$:)

5. Uprość wyrażenie, wprowadzając nową stałą $C_1 = \pm e^C$, gdzie $C_1$ może być dowolną liczbą rzeczywistą:
$$ y = C_1 e^x $$
(Упростим выражение, введя новую константу $C_1 = \pm e^C$, где $C_1$ может быть любым действительным числом:)

W ten sposób, ogólne rozwiązanie danego równania różniczkowego:
$$ y(x) = C_1 e^x $$
gdzie $C_1$ to dowolna stała.
(Таким образом, общее решение данного дифференциального уравнения:)

***
Aby rozwiązać dane równanie różniczkowe pierwszego rzędu:
$$ y'(x) = \frac{1}{2y(x)} $$
(Для решения данного дифференциального уравнения первого порядка:)

1. To równanie jest również równaniem ze zmiennymi separowalnymi.
(Это уравнение также является уравнением с разделяющимися переменными.)

2. Wyraźmy $ y' $ jako $ \frac{dy}{dx} $ i przekształćmy równanie, aby oddzielić zmienne:
$$ \frac{dy}{dx} = \frac{1}{2y} $$
$$ 2y \, dy = dx $$
(Выразим $ y' $ как $ \frac{dy}{dx} $ и перепишем уравнение, чтобы разделить переменные:)

3. Zintegrujmy obie strony:
$$ \int 2y \, dy = \int dx $$
$$ y^2 = x + C $$
gdzie $ C $ to stała całkowania.
(Интегрируем обе части:)

4. Rozwiążmy uzyskane równanie względem $ y $:
$$ y = \pm \sqrt{x + C} $$
(Решим полученное уравнение относительно $y $:)

W ten sposób, ogólne rozwiązanie danego równania różniczkowego:
$$ y(x) = \pm \sqrt{x + C} $$
gdzie $ C $ to dowolna stała.
(Таким образом, общее решение данного дифференциального уравнения:)

---
***№2***

Aby rozwiązać dane równanie różniczkowe pierwszego rzędu:
$$ \frac{dy}{dx} = \frac{x}{y} $$
(Для решения данного дифференциального уравнения первого порядка:)
stosujemy metodę separacji zmiennych.

1. **Separacja zmiennych**: Przekształćmy równanie tak, aby z jednej strony były tylko $x$ i $dx$, a z drugiej — tylko $y$ i $dy$:
$$ y \, dy = x \, dx $$
(Разделение переменных:)

2. **Całkowanie obu stron**: Całkujemy lewą i prawą stronę:
$$ \int y \, dy = \int x \, dx $$
$$ \frac{y^2}{2} = \frac{x^2}{2} + C $$
gdzie $C$ to stała całkowania.
(Интегрирование обеих частей:)

3. **Wyrażenie rozwiązania**: Rozwiązujemy otrzymane równanie względem $y$:
$$ y^2 = x^2 + C' $$
gdzie $C' = 2C$ dla uproszczenia.
(Выражение решения:)

4. **Ogólne rozwiązanie**: Ponieważ $y^2$ może być zarówno dodatnie, jak i ujemne, a pierwiastek kwadratowy liczby ma dwie wartości ($+$ i $-$):
$$ y = \pm \sqrt{x^2 + C'} $$
(Общее решение:)

W ten sposób, ogólne rozwiązanie danego równania różniczkowego:
$$ y(x) = \pm \sqrt{x^2 + C'} $$
gdzie $C'$ to dowolna stała, którą można dostosować w zależności od warunków początkowych.
(Таким образом, общее решение данного дифференциального уравнения:)

---

Aby rozwiązać dane równanie różniczkowe pierwszego rzędu:
$$ \frac{dy}{dx} = \frac{y}{x} $$
(Для решения данного дифференциального уравнения первого порядка:)
stosujemy metodę separacji zmiennych.

1. **Separacja zmiennych**: Przekształćmy równanie tak, aby z jednej strony były tylko zmienne $y$ i $dy$, a z drugiej — tylko $x$ i $dx$:
$$ \frac{dy}{y} = \frac{dx}{x} $$
(Разделение переменных:)

2. **Całkowanie obu stron**: Całkujemy lewą i prawą stronę:
$$ \int \frac{dy}{y} = \int \frac{dx}{x} $$
$$ \ln |y| = \ln |x| + C $$
gdzie $C$ to stała całkowania.
(Интегрирование обеих частей:)

3. **Wyrażenie rozwiązania przez eksponentę**: Skorzystajmy z własności logarytmów i eksponenty, aby wyrazić $y$ przez $x$:
$$ |y| = e^{\ln |x| + C} $$
$$ y = \pm e^C |x| $$
$$ y = C_1 x $$
gdzie $C_1 = \pm e^C$ — nowa stała, która może przyjąć dowolną rzeczywistą wartość.
(Выражение решения через экспоненту:)

W ten sposób, ogólne rozwiązanie danego równania różniczkowego:
$$ y(x) = C_1 x $$
gdzie $C_1$ to dowolna stała.
(Таким образом, общее решение данного дифференциального уравнения:)

---
Aby rozwiązać dane równanie różniczkowe pierwszego rzędu:
$$ \frac{dy}{dx} = xy $$
(Для решения данного дифференциального уравнения первого порядка:)
stosujemy metodę separacji zmiennych.

1. **Separacja zmiennych**: Przekształćmy równanie tak, aby zmienne $x$ i $dx$ były po jednej stronie, a zmienne $y$ i $dy$ — po drugiej:
$$ \frac{dy}{y} = x \, dx $$
(Разделение переменных:)

2. **Całkowanie obu stron**: Całkujemy lewą i prawą stronę:
$$ \int \frac{dy}{y} = \int x \, dx $$
$$ \ln |y| = \frac{x^2}{2} + C $$
gdzie $C$ to stała całkowania.
(Интегрирование обеих частей:)

3. **Wyrażenie rozwiązania przez eksponentę**: Skorzystajmy z własności logarytmów i eksponenty, aby wyrazić $y$ przez $x$:
$$ |y| = e^{\frac{x^2}{2} + C} $$
$$ y = C_1 e^{\frac{x^2}{2}} $$
gdzie $C_1 = \pm e^C$ — nowa stała, która może przyjąć dowolną rzeczywistą wartość.
(Выражение решения через экспоненту:)

W ten sposób, ogólne rozwiązanie danego równania różniczkowego:
$$ y(x) = C_1 e^{\frac{x^2}{2}} $$
gdzie $C_1$ to dowolna stała.
(Таким образом, общее решение данного дифференциального уравнения:)

---
***№3***

Aby rozwiązać dane równanie różniczkowe drugiego rzędu:
$$ y''(x) + y'(x) = 0 $$
z warunkami początkowymi $ y(0) = 2 $ i $ y'(0) = -1 $, możemy użyć metody rozwiązywania równań różniczkowych z stałymi współczynnikami.
(Для решения данного дифференциального уравнения второго порядка с начальными условиями $ y(0) = 2 $ и $ y'(0) = -1 $, мы можем использовать метод решения дифференциальных уравнений с постоянными коэффициентами.)

1. **Równanie charakterystyczne**: Najpierw znajdujemy równanie charakterystyczne dla danego równania różniczkowego. Podstawiając $ y = e^{rx} $, otrzymujemy:
$$ r^2e^{rx} + re^{rx} = 0 $$
$$ e^{rx}(r^2 + r) = 0 $$

Ponieważ $ e^{rx} $ nigdy nie jest równe zero, otrzymujemy:
$$ r^2 + r = 0 $$
$$ r(r + 1) = 0 $$
Stąd:
$$ r_1 = 0, \quad r_2 = -1 $$

2. **Ogólne rozwiązanie**: Teraz, korzystając z znalezionych korzeni, możemy zapisać ogólne rozwiązanie równania:
$$ y(x) = C_1 e^{0x} + C_2 e^{-x} = C_1 + C_2 e^{-x} $$

3. **Wykorzystanie warunków początkowych**:
   - Podstawiamy $ y(0) = 2 $:
     $$ y(0) = C_1 + C_2 = 2 $$
   - Dla $ y'(x) $, znajdujemy pochodną:
     $$ y'(x) = -C_2 e^{-x} $$
   - Podstawiamy $ y'(0) = -1 $:
     $$ y'(0) = -C_2 = -1 $$
     $$ C_2 = 1 $$

   Teraz podstawiamy wartość $ C_2 $ do równania dla $ C_1 $:
   $$ C_1 + 1 = 2 $$
   $$ C_1 = 1 $$

4. **Końcowe rozwiązanie**: W ten sposób rozwiązanie zadania to:
$$ y(x) = 1 + e^{-x} $$

To rozwiązanie spełnia warunki początkowe i jest rozwiązaniem wyjściowego równania różniczkowego.
(Это решение удовлетворяет начальным условиям и является решением исходного дифференциального уравнения.)

---
Aby rozwiązać dane równanie różniczkowe drugiego rzędu:
$$ y''(x) - y(x) = 0 $$
z warunkami początkowymi $ y(0) = 2 $ i $ y'(0) = 0 $, możemy użyć metody rozwiązywania liniowych równań różniczkowych ze stałymi współczynnikami.
(Для решения данного дифференциального уравнения второго порядка с граничными условиями $ y(0) = 2 $ и $ y'(0) = 0 $, мы можем использовать метод решения линейных дифференциальных уравнений с постоянными коэффициентами.)

1. **Równanie charakterystyczne**: Najpierw znajdujemy równanie charakterystyczne dla danego równania różniczkowego. Podstawiając założenie $ y = e^{rx} $:
$$ r^2 e^{rx} - e^{rx} = 0 $$
$$ e^{rx}(r^2 - 1) = 0 $$

Ponieważ $ e^{rx} $ nigdy nie jest równe zero, mamy:
$$ r^2 - 1 = 0 $$
$$ r^2 = 1 $$
$$ r = \pm 1 $$

2. **Ogólne rozwiązanie**: Na podstawie znalezionych korzeni równania charakterystycznego, ogólne rozwiązanie równania ma postać:
$$ y(x) = C_1 e^x + C_2 e^{-x} $$
gdzie $ C_1 $ i $ C_2 $ to stałe, które musimy ustalić na podstawie warunków początkowych.

3. **Wykorzystanie warunków początkowych**:
   - Podstawiamy $ y(0) = 2 $:
     $$ y(0) = C_1 e^0 + C_2 e^0 = C_1 + C_2 = 2 $$
   - Obliczamy $ y'(x) $:
     $$ y'(x) = C_1 e^x - C_2 e^{-x} $$
   - Podstawiamy $ y'(0) = 0 $:
     $$ y'(0) = C_1 e^0 - C_2 e^0 = C_1 - C_2 = 0 $$
     $$ C_1 = C_2 $$

   Z $ C_1 + C_2 = 2 $ i $ C_1 = C_2 $, otrzymujemy:
   $$ 2C_1 = 2 $$
   $$ C_1 = C_2 = 1 $$

4. **Końcowe rozwiązanie**: Po podstawieniu znalezionych wartości stałych, otrzymujemy:
$$ y(x) = e^x + e^{-x} $$
$$ y(x) = 2 \cosh(x) $$

W ten sposób końcowe rozwiązanie równania różniczkowego to:
$$ y(x) = 2 \cosh(x) $$
gdzie funkcja $\cosh(x)$ to hipreboliczny kosinus.
(Таким образом, конечное решение дифференциального уравнения: $$ y(x) = 2 \cosh(x) $$ где функция $\cosh(x)$
 — это гиперболический косинус.)

---
Aby rozwiązać dane równanie różniczkowe drugiego rzędu:
$$ \frac{d^2\,y(x)}{dx^2} = -\omega^2 y(x) $$
mamy do czynienia z klasycznym równaniem oscylatora harmonicznego, gdzie $ \omega $ jest stałą oznaczającą częstotliwość.
(Для решения данного дифференциального уравнения второго порядка: $$ \frac{d^2\,y(x)}{dx^2} = -\omega^2 y(x) $$ мы сталкиваемся с классическим уравнением гармонического осциллятора, где $ \omega $ — это постоянная, обозначающая частоту.)

1. **Równanie charakterystyczne**: Najpierw znajdźmy równanie charakterystyczne dla tego równania różniczkowego. Podstawiając $ y = e^{rx} $:
$$ r^2 e^{rx} = -\omega^2 e^{rx} $$
$$ r^2 + \omega^2 = 0 $$
(Характеристическое уравнение: Прежде всего, найдем характеристическое уравнение для этого дифференциального уравнения. Подставим $ y = e^{rx} $:)

2. **Korzenie równania charakterystycznego**: Rozwiązując to równanie kwadratowe, otrzymujemy:
$$ r^2 = -\omega^2 $$
$$ r = \pm i\omega $$
To kompleksowe korzenie, co wskazuje, że rozwiązanie będzie oscylować.
(Корни характеристического уравнения: Решая это квадратное уравнение, получаем:)

3. **Ogólne rozwiązanie**: Wykorzystując korzenie równania charakterystycznego, ogólne rozwiązanie równania można zapisać jako kombinację sinusów i cosinusów:
$$ y(x) = C_1 \cos(\omega x) + C_2 \sin(\omega x) $$
gdzie $ C_1 $ i $ C_2 $ to stałe, które zostaną określone na podstawie warunków początkowych.
(Общее решение: Используя корни характеристического уравнения, общее решение уравнения можно записать как комбинацию синусов и косинусов:)

To ogólne rozwiązanie opisuje harmoniczne oscylacje o amplitudzie zależnej od stałych $ C_1 $ i $ C_2 $ oraz o kątowej częstotliwości $\omega$. Rozwiązanie jest periodyczne z okresem $ T = \frac{2\pi}{\omega} $.
(Это общее решение описывает гармонические колебания с амплитудой, зависящей от констант $ C_1 $ и $ C_2 $, и угловой частотой $\omega$. Решение является периодическим с периодом $ T = \frac{2\pi}{\omega} $.)
