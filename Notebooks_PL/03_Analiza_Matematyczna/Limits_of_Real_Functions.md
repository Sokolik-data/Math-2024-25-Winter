## Limits of Real Functions

1. Compute:
   - $\displaystyle\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}$

2. Find:
   
   - $\displaystyle \lim_{x \to 0} \frac{\sin(3x)}{2x+1}$.

3. Find the asymptotes of the function:
  
   - $f(x) = \frac{x^2 - 1}{x^2 + 1}$
   - $g(x) = \frac{\sin(x)}{x^2+1}$

***№1***

Aby obliczyć:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$

### Rozwiązanie krok po kroku

1. **Zidentyfikuj stopnie licznika i mianownika:** *(Идентифицируйте степени числителя и знаменателя)*
   - Licznik: \( x^3 + 2x^2 \) (stopień = 3),
   - Mianownik: \( x^4 - 3x^3 \) (stopień = 4).

   Ponieważ stopień licznika jest mniejszy niż stopień mianownika, granica powinna zmierzać do 0.  *(Поскольку степень числителя меньше степени знаменателя, предел должен стремиться к 0.)*

2. **Podziel licznik i mianownik przez najwyższą potęgę \( x \) w mianowniku (\( x^4 \)):** *(Разделите числитель и знаменатель на высшую степень \( x \) в знаменателе (\( x^4 \)):)*

   Przekształć wyrażenie: *(Преобразуйте выражение)*

   $$
   \frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{1 - \frac{3x^3}{x^4}}.
   $$

   Upraszczając poszczególne wyrażenia: *(Упрощая отдельные выражения)*

   $$
   \frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}.
   $$

3. **Oblicz granicę dla $x \to \infty$:** *(Вычислите предел при $x \to \infty $:)*

   Gdy $ x \to \infty$:
   - $\frac{1}{x} \to 0$,
   - $\frac{2}{x^2} \to 0$,
   - $\frac{3}{x} \to 0$.

   Podstawiając te wartości do wyrażenia *(Подставляя эти значения в выражение)*:

   $$
   \lim_{x \to \infty} \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}} = \frac{0 + 0}{1 - 0} = 0.
   $$

### Wniosek *(Вывод)*  

Granica wynosi:  
*(Предел равен)* 

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3} = 0.
$$

***№2***

Znajdź granicę *(Найди предел)* : 
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1}.
$$

### Rozwiązanie *(Решение)*  

#### Krok 1: Analiza zachowania licznika i mianownika *(Шаг 1: Анализ поведения числителя и знаменателя)*
- Licznik $\sin(3x)$ dąży do $\sin(0) = 0$, gdy $x \to 0$.
- Mianownik $2x + 1$ dąży do $1$, gdy $x \to 0$.

Zatem wyrażenie przyjmuje postać *(Таким образом, выражение принимает вид)*  :
$$
\frac{0}{1}.
$$

#### Krok 2: Podstawienie \(x = 0\)
Podstawiając \(x = 0\):
$$
\frac{\sin(3 \cdot 0)}{2 \cdot 0 + 1} = \frac{0}{1} = 0.
$$

### Odpowiedź końcowa
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1} = 0.
$$


***№3***
### Znajdź asymptoty funkcji $ f(x) = \frac{x^2 - 1}{x^2 + 1} $ *(Найдите асимптоты функции)*

#### 1. Asymptoty poziome *(1. Горизонтальные асимптоты)*  
Asymptoty poziome ustalamy analizując granicę funkcji, gdy $ x \to \pm \infty $.  
*(Горизонтальные асимптоты определяются анализом предела функции при $ x \to \pm \infty $)*

Dla funkcji:
$$
f(x) = \frac{x^2 - 1}{x^2 + 1},
$$
dzielimy licznik i mianownik przez \( x^2 \) *(делим числитель и знаменатель на \( x^2 \))*: 
$$
f(x) = \frac{1 - \frac{1}{x^2}}{1 + \frac{1}{x^2}}.
$$

Gdy $ x \to \pm \infty $, człony z $ \frac{1}{x^2} \to 0 $. *(Когда $ x \to \pm \infty $, члены с $ \frac{1}{x^2} \to 0 $)* 

Dlatego:
$$
\lim_{x \to \pm \infty} f(x) = \frac{1 - 0}{1 + 0} = 1.
$$

W związku z tym, pozioma asymptota to *(Таким образом, горизонтальная асимптота)*  :
$$
y = 1.
$$



#### 2. Asymptoty pionowe *(2. Вертикальные асимптоты)*  
Asymptoty pionowe występują tam, gdzie mianownik jest równy zero, a licznik nie jest równy zero.  
*(Вертикальные асимптоты возникают там, где знаменатель равен нулю, а числитель не равен нулю.)*


Rozważmy mianownik $ x^2 + 1 = 0 $ *(Рассмотрим знаменатель $ x^2 + 1 = 0 $)*:
$$
x^2 = -1.
$$

Nie istnieją żadne rozwiązania tego równania w zbiorze liczb rzeczywistych. W związku z tym asymptoty pionowe **nie istnieją** *(Не существует решений этого уравнения в множестве действительных чисел. Следовательно, вертикальные асимптоты **не существуют**)*.



#### 3. Asymptoty skośne *(3. Косые асимптоты)*  
Ponieważ stopień licznika jest równy stopniowi mianownika, asymptoty skośne również **nie istnieją**.  
*(Поскольку степень числителя равна степени знаменателя, косые асимптоты также **не существуют**.)*




### Odpowiedź:  
*(Ответ:)*  
1. **Pozioma asymptota:** \( y = 1 \).  
*(1. Горизонтальная асимптота: \( y = 1 \).)*  
2. **Asymptoty pionowe:** brak.  
*(2. Вертикальные асимптоты: отсутствуют.)*  
3. **Asymptoty skośne:** brak.  
*(3. Косые асимптоты: отсутствуют.)*



## Znajdź asymptoty funkcji  *(Найдите асимптоты функции)*

### Dana funkcja:  
*(Дана функция):*
 
$$
g(x) = \frac{\sin(x)}{x^2 + 1}
$$

---

## Rozwiązanie  *(1. Горизонтальные асимптоты)*

### 1. Asymptoty poziome  

Asymptoty poziome sprawdzamy, gdy $x \to \infty $ lub $x \to -\infty $:  
*(Горизонтальные асимптоты проверяются при $x \to \infty$ или $ x \to -\infty $):*

Obliczamy granicę:  
*(Вычисляем предел):*


$$
\lim_{x \to \pm \infty} g(x) = \lim_{x \to \pm \infty} \frac{\sin(x)}{x^2 + 1}.
$$

#### Własności funkcji $\sin(x)$: *(Свойства функции $ \sin(x) $):*

Jest znane, że:  
*(Известно, что)*

$$
|\sin(x)| \leq 1 \text{ dla każdego } x.
$$

Zatem możemy napisać:  

$$
|g(x)| = \left| \frac{\sin(x)}{x^2 + 1} \right| \leq \frac{1}{x^2 + 1}.
$$

#### Obliczamy granicę: *(Вычисляем предел):*

Gdy $x \to \pm \infty$, mianownik $x^2 + 1 \to \infty$. Zatem *(Когда $x \to \pm \infty $, знаменатель $ x^2 + 1 \to \infty $)*:  

$$
\lim_{x \to \pm \infty} \frac{1}{x^2 + 1} = 0.
$$

#### Odpowiedź:  

W związku z tym:  

$$
\lim_{x \to \pm \infty} g(x) = 0.
$$

Oznacza to, że **pozioma asymptota** funkcji $g(x)$ to *(Это означает, что **горизонтальная асимптота** функции \( g(x) \) равна)*:  

$$
y = 0.
$$



### 2. Asymptoty pionowe  *(2. Вертикальные асимптоты)*

Asymptoty pionowe występują, gdy mianownik dąży do \( 0 \). Sprawdźmy mianownik:  
*(Вертикальные асимптоты возникают, когда знаменатель стремится к (0). Проверим знаменатель)*



$$
x^2 + 1.
$$

Zauważamy, że:  

$$
x^2 + 1 > 0 \text{ dla każdego } x.
$$

Oznacza to, że mianownik **nigdy nie jest równy 0**, co oznacza brak asymptot pionowych. *(Это означает, что знаменатель **никогда не равен 0**, что указывает на отсутствие вертикальных асимптот.)*



### 3. Asymptoty ukośne *(3. Косые асимптоты)*

Asymptoty ukośne pojawiają się, jeśli stopień licznika jest wyższy niż stopień mianownika. W naszym przypadku:  
*(Косые асимптоты появляются, если степень числителя выше степени знаменателя. В нашем случае)* 
 

-  Licznik $ \sin(x) $ **nie rośnie w nieskończoność**, ponieważ funkcja $ \sin(x) $ jest ograniczona przedziałem od $-1$ do $1$.  
  *(Числитель $\sin(x)$ **не растет до бесконечности**, так как функция $ \sin(x) $ ограничена интервалом от $-1$ до $1$.)*
- Mianownik $ x^2 + 1 $ rośnie szybciej przy dużych wartościach $|x| $.  
  *(Знаменатель $ x^2 + 1 $ растет быстрее при больших значениях $|x| $.)*

W związku z tym, asymptoty ukośne również nie występują. *(Следовательно, косые асимптоты также отсутствуют.)*

## Odpowiedź:  
*(Ответ):*

1. **Asymptota pozioma:** $ y = 0 $ (dla $ x \to \pm \infty $).  
   *(Горизонтальная асимптота: $ y = 0 $ при $ x \to \pm \infty $).*
2. **Asymptoty pionowe:** brak.  
   *(Вертикальные асимптоты: отсутствуют.)*
3. **Asymptoty ukośne:** brak.  
   *(Косые асимптоты: отсутствуют.)*
