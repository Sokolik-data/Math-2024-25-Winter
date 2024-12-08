## Przykłady obliczania pochodnych

### Przykład 1  
**Funkcja:**  
$y(x) = -3x + 3$  

**Reguła:**  
Pochodna funkcji liniowej:  
$$ \frac{d}{dx}[ax + b] = a $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = -3 $$  

---

### Przykład 2  
**Funkcja:**  
$y(x) = \pi x + \sin(1)$  

**Reguła:**  
Pochodna funkcji liniowej i stałej:  
$$ \frac{d}{dx}[ax + b] = a $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = \pi $$  

---

### Przykład 3  
**Funkcja:**  
$y(x) = 4 + \sin(2)$  

**Reguła:**  
Pochodna stałej:  
$$ \frac{d}{dx}[C] = 0 $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 0 $$  

---

### Przykład 4  
**Funkcja:**  
$y(x) = 2x^3 - 3x^2 + 8x - 9$  

**Reguła:**  
Pochodna funkcji potęgowej:  
$$ \frac{d}{dx}[x^n] = n \cdot x^{n-1} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 6x^2 - 6x + 8 $$  

---

### Przykład 5  
**Funkcja:**  
$y(x) = 6x^{1/3}$  

**Reguła:**  
Pochodna funkcji potęgowej:  
$$ \frac{d}{dx}[x^n] = n \cdot x^{n-1} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 2x^{-2/3} = \frac{2}{\sqrt[3]{x^2}} $$  

---

### Przykład 6  
**Funkcja:**  
$y(x) = \sqrt{x}$  

**Reguła:**  
Pochodna pierwiastka:  
$$ \frac{d}{dx}[\sqrt{x}] = \frac{1}{2\sqrt{x}} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = \frac{1}{2\sqrt{x}} $$  

---

### Przykład 7  
**Funkcja:**  
$y(x) = \cos(x) + \sin(x)$  

**Reguła:**  
Pochodne funkcji trygonometrycznych:  
$$ \frac{d}{dx}[\sin(x)] = \cos(x), \quad \frac{d}{dx}[\cos(x)] = -\sin(x) $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = -\sin(x) + \cos(x) $$  

---

### Przykład 8  
**Funkcja:**  
$y(x) = 2\sin(x)\cos(x)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = 2\sin(x)$, $v = \cos(x)$:  
$$ \frac{du}{dx} = 2\cos(x), \quad \frac{dv}{dx} = -\sin(x) $$  
$$ \frac{dy}{dx} = 2\cos(x)\cos(x) + 2\sin(x)(-\sin(x)) $$  
$$ \frac{dy}{dx} = 2\cos^2(x) - 2\sin^2(x) $$  

---

### Przykład 9  
**Funkcja:**  
$y(x) = x\sin(x)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = x$, $v = \sin(x)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = \cos(x) $$  
$$ \frac{dy}{dx} = 1 \cdot \sin(x) + x \cdot \cos(x) $$  
$$ \frac{dy}{dx} = \sin(x) + x\cos(x) $$  

---

### Przykład 10  
**Funkcja:**  
$y(x) = (x+1)(x+1)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji:  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = (x+1)$, $v = (x+1)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = 1 $$  
$$ \frac{dy}{dx} = 1 \cdot (x+1) + (x+1) \cdot 1 $$  
$$ \frac{dy}{dx} = 2(x+1) $$  

---

### Przykład 11  
**Funkcja:**  
$y(x) = \frac{x}{x+1}$  

**Reguła:**  
Pochodna funkcji ułamkowej:  
$$ \frac{d}{dx}\left(\frac{f(x)}{g(x)}\right) = \frac{f'(x)g(x) - f(x)g'(x)}{g^2(x)} $$  

**Rozwiązanie:**  
Niech $f(x) = x$, $g(x) = x+1$:  
$$ f'(x) = 1, \quad g'(x) = 1 $$  
$$ \frac{dy}{dx} = \frac{1 \cdot (x+1) - x \cdot 1}{(x+1)^2} $$  
$$ \frac{dy}{dx} = \frac{1}{(x+1)^2} $$  

## Obliczanie pochodnych dla podanych funkcji

### Przykład 12  
**Funkcja:**  
$y(x) = (x+1)\exp(x)$  

**Reguła:**  
Pochodna iloczynu funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = (x+1)$, $v = \exp(x)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = \exp(x) $$  
$$ \frac{dy}{dx} = 1 \cdot \exp(x) + (x+1) \cdot \exp(x) $$  
$$ \frac{dy}{dx} = \exp(x)(x+2) $$  

---

### Przykład 13  
**Funkcja:**  
$y(x) = \sin(x^2)$  

**Reguła:**  
Pochodna funkcji złożonej:  
$$ \frac{d}{dx}[\sin(u)] = \cos(u) \cdot \frac{du}{dx} $$  

**Rozwiązanie:**  
Niech $u = x^2$, wtedy $\frac{du}{dx} = 2x$:  
$$ \frac{dy}{dx} = \cos(x^2) \cdot 2x $$  
$$ \frac{dy}{dx} = 2x\cos(x^2) $$  

---

### Przykład 14  
**Funkcja:**  
$y(x) = \exp(-2x)$  

**Reguła:**  
Pochodna funkcji wykładniczej:  
$$ \frac{d}{dx}[\exp(u)] = \exp(u) \cdot \frac{du}{dx} $$  

**Rozwiązание:**  
Niech $u = -2x$, wtedy $\frac{du}{dx} = -2$:  
$$ \frac{dy}{dx} = \exp(-2x) \cdot (-2) $$  
$$ \frac{dy}{dx} = -2\exp(-2x) $$  

---

### Przykład 15  
**Funkcja:**  
$y(x) = \frac{1}{\sin(x+1)}$  

**Reguła:**  
Pochodna funkcji ułamkowej:  
$$ \frac{d}{dx}\left(\frac{1}{f(x)}\right) = -\frac{f'(x)}{[f(x)]^2} $$  

**Rozwiązanie:**  
Niech $f(x) = \sin(x+1)$, wtedy:  
$$ \frac{d}{dx}[f(x)] = \cos(x+1) \cdot 1 = \cos(x+1) $$  
$$ \frac{dy}{dx} = -\frac{\cos(x+1)}{\sin^2(x+1)} $$  

---

### Przykład 16  
**Funkcja:**  
$y(x) = \sqrt{2x+1}$  

**Reguła:**  
Pochodna funkcji pierwiastkowej:  
$$ \frac{d}{dx}[\sqrt{f(x)}] = \frac{1}{2\sqrt{f(x)}} \cdot f'(x) $$  

**Rozwiązanie:**  
Niech $f(x) = 2x+1$, wtedy $\frac{d}{dx}[f(x)] = 2$:  
$$ \frac{dy}{dx} = \frac{1}{2\sqrt{2x+1}} \cdot 2 $$  
$$ \frac{dy}{dx} = \frac{2}{2\sqrt{2x+1}} $$  
$$ \frac{dy}{dx} = \frac{1}{\sqrt{2x+1}} $$
