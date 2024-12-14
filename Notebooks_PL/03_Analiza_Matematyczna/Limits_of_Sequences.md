## Limits of Sequences

1. Calculate:
   - $\displaystyle \lim_{n \to \infty} \frac{n^2 + 3n}{2 n^2 - 2n}$

   - $\displaystyle \lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1}$

2. Prove using the squeeze theorem:
   - $\displaystyle\lim_{n \to \infty} \frac{\sin(n)}{n}$

4. Find the limit of the sequence:
   - $a_n = (1+\frac{1}{n})^n$

---

### **№1**
## Rozwiązanie zadania

Obliczmy granicę *(Вычислим предел)*:

$\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n}$.



### Krok 1: Podzielmy licznik i mianownik przez $n^2$ *(Шаг 1: Разделим числитель и знаменатель на $n^2$)*

Dzielimy licznik i mianownik przez $n^2$ *(Делим числитель и знаменатель на $n^2$)*:

$\frac{n^2 + 3n}{2n^2 - 2n} = \frac{\frac{n^2}{n^2} + \frac{3n}{n^2}}{\frac{2n^2}{n^2} - \frac{2n}{n^2}}$.

Obliczamy poszczególne elementy *(Вычисляем отдельные элементы)*:

$\frac{n^2}{n^2} = 1, \quad \frac{3n}{n^2} = \frac{3}{n}, \quad \frac{2n^2}{n^2} = 2, \quad \frac{2n}{n^2} = \frac{2}{n}$.

Otrzymujemy *(Получаем)*:

$\frac{n^2 + 3n}{2n^2 - 2n} = \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}$.



### Krok 2: Obliczamy granicę, gdy $n \to \infty$ *(Шаг 2: Вычисляем предел при $n \to \infty$)*

Analizujemy granicę, gdy $n \to \infty$ *(Анализируем предел, когда $n \to \infty$)*:

- $\frac{3}{n} \to 0$,
- $\frac{2}{n} \to 0$.

Otrzymujemy *(Получаем)*:

$\lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1}{2}$.


### Odpowiedź *(Ответ)*:

$\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \frac{1}{2}$.


---


 $$\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1}$$

### Rozwiązanie *(Решение)*:

1. **Rozwiń licznik:** *(Разложим числитель)*

   Licznik można rozwinąć za pomocą wzoru na sześcian sumy *(Числитель можно разложить по формуле куба суммы)*:

   $$ (2n+3)^3 = 8n^3 + 36n^2 + 54n + 27 $$

2. **Rozważmy ułamek:** *(Рассмотрим дробь)*

   Teraz nasz ułamek wygląda tak *(Теперь наша дробь выглядит так)*:

   $$ \frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1} $$

3. **Podzielmy licznik i mianownik przez $n^3$:** *(Разделим числитель и знаменатель на $n^3$)*

   Podzielimy zarówno licznik, jak i mianownik przez $n^3$ *(Разделим как числитель так и знаменатиль на $n^3$)*:

   $$ \frac{\frac{8n^3}{n^3} + \frac{36n^2}{n^3} + \frac{54n}{n^3} + \frac{27}{n^3}}{\frac{n^3}{n^3} - \frac{1}{n^3}} $$

4. **Uprośćmy ułamek:** *(Упростим дробь)*:

   Po podzieleniu otrzymujemy *(После деления получаем)*:

   $$ \frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}} $$

5. **Obliczamy granicę, gdy $n \to \infty$:** *(Вычислим предел при $n \to \infty$)*

   Gdy $n \to \infty$ *(Когда $n \to \infty$)*:

   - $\frac{36}{n} \to 0$,
   - $\frac{54}{n^2} \to 0$,
   - $\frac{27}{n^3} \to 0$,
   - $\frac{1}{n^3} \to 0$.

   Dlatego granica przybiera postać *(Поэтому предел принимает вид)*:

   $$ \frac{8}{1} = 8 $$

### Odpowiedź *(Ответ)*:

- $$\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} = 8$$

---
***№2***
Prove using the squeeze theorem *(Доказать с помощью теоремы зажатия)*:
- $\displaystyle\lim_{n \to \infty} \frac{\sin(n)}{n}$

## Dowód za pomocą twierdzenia ściskania *(Доказательство с использованием теоремы зажатия)*

Należy udowodnić *(Необходимо доказать)*:  
$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$  

z wykorzystaniem **twierdzenia ściskania (Squeeze Theorem)** *(с использованием **теоремы зажатия**)*.



### 1. Własności funkcji $ \sin(n) $

Funkcja $\sin(n)$  jest ograniczona w całej swojej dziedzinie za pomocą następującej nierówności *(Функция $sin(n) $ ограничена на всём своём определении следующими неравенствами)*:  

$$
-1 \leq \sin(n) \leq 1
$$

Ta nierówność będzie podstawą do zastosowania twierdzenia ściskania *(Это неравенство станет основой для применения теоремы зажатия)*.



### 2. Ustalanie nierówności

Teraz z własności $-1 \leq \sin(n) \leq 1$ uzyskujemy *(Теперь из свойства $-1 \leq \sin(n) \leq 1 $ получаем)*:  

$$
-1 \leq \sin(n) \leq 1
$$

Dzielimy teraz wszystkie człony przez \( n > 0 \) *(Теперь делим все члены на \( n > 0 \))*:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$



### 3. Zastosowanie twierdzenia ściskania

Teraz mamy nierówność *(Теперь у нас есть неравенство)*:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

Obliczamy teraz granice krańców dla $n \to \infty $ *(Теперь вычислим пределы крайних членов при $n \to \infty $)*:

- **Lewy kraniec:**   *(Левая граница)*

$$
\lim_{n \to \infty} -\frac{1}{n} = 0
$$

- **Prawy kraniec:**  *(Правая граница)*

$$
\lim_{n \to \infty} \frac{1}{n} = 0
$$



### 4. Wniosek

Z twierdzenia ściskania wynika, że jeśli funkcja jest ściskana między dwiema innymi funkcjami, które zbliżają się do tego samego granicy, to sama funkcja również musi zbliżać się do tego samego wyniku.   *(Из теоремы зажатия следует, что если функция зажата между двумя другими функциями, стремящимися к одному пределу, то и сама функция должна стремиться к тому же значению)*

W związku z tym:  *(Следовательно)*

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$



### Odpowiedź *(Ответ)*:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$



***№3***

Find the limit of the sequence:
   - $a_n = (1+\frac{1}{n})^n$


## Rozwiązanie:

1. **Krok 1: Przypomnijmy definicję liczby matematycznej \( e \):** *(Шаг 1: Напомним определение математической константы \( e \):)*

   Liczba \( e \) (przybliżona wartość to \( 2,718 \)) jest definiowana za pomocą następującego granicy:  
   *(Число \( e \) (приблизительное значение \( 2,718 \)) определяется следующим пределом:)*

   $$
   e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n
   $$

2. **Krok 2: Porównanie zadania z definicją liczby \( e \):**  *(Шаг 2: Сравним задачу с определением числа \( e \):)*

   Nasze zadanie jest przedstawione w następującej formie:  
   *(Наша задача представлена в следующем виде:)*

   $$
   a_n = \left(1 + \frac{1}{n}\right)^n
   $$

   To wyrażenie jest dokładnie równoważne definicji liczby \( e \). *(Это выражение точно соответствует определению числа \( e \))*

3. **Krok 3: Wniosek:** *(Шаг 3: Вывод:)*

   Na podstawie tego można stwierdzić, że:  
   *(На основе этого можно утверждать, что)*

   $$
   \lim_{n \to \infty} a_n = e
   $$

---

## Odpowiedź *(Ответ)*:

Granica danej sekwencji jest równa *(Предел данной последовательности равен)*:

$$
\lim_{n \to \infty} a_n = e
$$
