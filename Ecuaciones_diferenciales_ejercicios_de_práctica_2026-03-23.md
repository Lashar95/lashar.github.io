# índice:
- [índice:](#índice)
- [Preparación para prueba diagnostica - 23/3/2026](#preparación-para-prueba-diagnostica---2332026)
  - [✍️ Bloque 1: Derivadas](#️-bloque-1-derivadas)
    - [📋Apuntes:](#apuntes)
  - [✍️ Bloque 2: Integrales](#️-bloque-2-integrales)
    - [Sustitución simple:](#sustitución-simple)
      - [📋Apuntes:](#apuntes-1)
    - [Fracciones parciales (factores lineales distintos)](#fracciones-parciales-factores-lineales-distintos)
      - [📋Notas](#notas)
  - [Bloque 3: Ecuaciones Diferenciales separables.](#bloque-3-ecuaciones-diferenciales-separables)
      - [📋Notas](#notas-1)
    - [🚀 Para recordar](#-para-recordar)
  - [Bloque 4: Verificar soluciones](#bloque-4-verificar-soluciones)
  - [Bloque 5: Gráficas](#bloque-5-gráficas)
      - [📋 Apuntes](#-apuntes)
  - [Resolución:](#resolución)
  - [💥 Recordatorio](#-recordatorio)
    - [📌 Reglas de desigualdad](#-reglas-de-desigualdad)
    - [📌 Gráficas](#-gráficas)
    - [📌 Dominio de la solución](#-dominio-de-la-solución)

# Preparación para prueba diagnostica - 23/3/2026

🔍**tags:** #ecuaciones_diferenciales #facultad

⛓️**fuente:** [Ecuaciones Diferenciales - ejercicios de práctica](./Ecuaciones_diferenciales_ejercicios_de_práctica_2026-03-23.pdf)

🔗**relacionado:** [Ecuaciones Diferenciales](./Ecuaciones_Diferenciales_Prueba_Diagnostica_ejercicios_2026-03-21.md)

⌛**estado:** `completado`



## ✍️ Bloque 1: Derivadas

**Ejercicios:**

1. $f(t) = e^{3t}$

2. $f(t) = e^{-2t}$

3. $f(t) = \sin(4t)$

4. $f(t) = \cos(5t)$

5. $f(t) = e^{-t} + e^{2t}$

6. $f(t) = 2\sin(3t) - \cos(t)$

7. $f(t) = e^{2t}\sin(3t)$

8. $f(t) = \cos(2t) \cdot e^{-t}$

9. $f(t) = \sin(2t) + 3\cos(2t)$

10. $f(t) = e^{kt}$ (con $k$ constante)

### 📋Apuntes:

👉 En el ejercicio 10 tenemos $f(t) = e^{kt}$, si derivamos obtenemos el resultado:

$$
\frac{d}{dt}e^{kt}=Ke^{Kt}
$$

Si volvemos a integrar obtendremos la función original como bien ya sabemos, lo que quiero anotar es que para integrar se debe aplicar sustitución:

$$
\int_{}^{} Ke^{Kt} \, dt
$$


$$
u=Kt 
$$
$$
du=K\, dt
$$

Sustituimos:
$$
\int_{}^{} e^{u} \, du \rightarrow e^{u}+C
$$

$$
\boxed{e^{Kt}}
$$

Como se puede ver volvimos a la función original.

---

## ✍️ Bloque 2: Integrales

### Sustitución simple:

1. $\int 2x e^{x^2} \, dx$

2. $\int_{}^{} \frac{2x}{x^2+1} \, dx$

3. $\int_{}^{} \frac{e^t}{1+e^{2t}} \, dt$

4. $\int_{}^{} \frac{2t}{1+t^2} \, dt$

5. $\int_{}^{} \cos(2x)e^{\sin(2x)} \, dx$

#### 📋Apuntes:

👉 Ahora aprendimos a integrar por sustitución simple, la idea es buscar una similitud entre las dos funciones, es decir, que la derivada de una función se parecida o igual a la otra función para poder así hacer sustitución.

**Ejercicio destacado:**

Para el ejercicio 5:

5. $\int_{}^{} \cos(2x)e^{\sin(2x)} \, dx$

Nos dio como resultado:

$$
\boxed{\frac{e^{\sin(2x)}}{2}+C}
$$

El cual si derivamos el resultado sería de esta manera:

$$
f'(x)=\frac{1}{2}\frac{d}{dx}e^{\sin(2x)}
$$

Acá aplicamos regla de la cadena para $e^{\sin(2x)}$  

$$
\frac{d}{dx}e^{\sin(2x)}=2\cos(2x)\cdot e^{\sin(2x)}
$$

Quedando:

$$
\frac{1}{2}\cdot2\cos(2x)\cdot e^{\sin(2x)}=\frac{2\cos(2x)\cdot  e^{\sin(2x)}}{2}
$$

$$
\boxed{\cos(2x)\cdot e^{\sin(2x)}}
$$

Volviendo así a la expresión original.

---

### Fracciones parciales (factores lineales distintos)

6. $\int \frac{1}{(x+1)(x+2)} \, dx$

7. $\int \frac{3x+2}{(x-1)(x+2)} \, dx$

8. $\int \frac{2x-1}{(x+3)(x-1)} \, dx$

9. $\int \frac{5}{(x-2)(x+3)} \, dx$

10. $\int \frac{x+4}{(x-1)(x+1)} \, dx$

#### 📋Notas

👉 Mejoré bastante a la hora de hacer integrales con fracciones parciales.

Para el ejercicio 9 cuando llegamos a la expresión:

$$
x(A+B)+3A-2B=5
$$

Nos quedarán dos expresiones:

$$
\begin{cases}
A+B=0 \\
3A-2B=5
\end{cases}
$$


Nos damos cuenta que solo tenemos una constante del lado derecho de la igualdad. Por lo que para hallar A y B tendremos que:

Igualar A más B a 0:

$$
A+B=0 
$$
$$
B=-A
$$

De acá sustituimos en la otra expresión:

$$
3A-2B=5
$$
$$
3A-2(-A)=5
$$
$$
3A+2A=5
$$
$$
A=\frac{5}{5}
$$
$$
A=1
$$

Sustituimos en la otra expresión para hallar B:

$$
B=-1
$$

Valores de A y B:

$$
\boxed{A=1} \hspace{0.2cm} \boxed{B=-1}
$$

---

## Bloque 3: Ecuaciones Diferenciales separables.

**Resolver, verificar y hallar dominio:**

1. $y' = \frac{t}{y}, \quad y(0) = 1$

2. $y' = -\frac{2t}{y}, \quad y(0) = 2$

3. $y' = \frac{t^2}{y}, \quad y(1) = 0$

4. $y' = \frac{1}{y}, \quad y(0) = 2$

5. $y' = \frac{2t}{y+1}, \quad y(0) = 0$

6. $y' = -\frac{t}{2y}, \quad y(2) = 0$

7. $y' = \frac{e^t}{y}, \quad y(0) = 1$

8. $y' = \frac{t}{y^2}, \quad y(1) = 0$


#### 📋Notas

👉 Una constante cumple para ser función de $t$.

En el ejercicio 4:

$$
y'=\frac{1}{y}, y(0)=2
$$

El $1$ cuenta para poder resolver este ejercicio en variables separadas, se trata a la constante 1 en función de $t$.


👉 Para el ejercicio 5 aplicamos factorización a binomio al cuadrado, para más detalles ver la nota: [Factorización a binomio al cuadrado](./Matemáticas_Factorizar_polinomio_a_binomio_al_cuadrado_teoría_2026-03-23.md).

👉 El dominio solamente se determina por las **operaciones restrictivas:**

- **Raíz cuadrada:** El radicando debe ser $\geq 0$
- **División:** Denominador $\neq 0$
- **Logaritmo:** argumento $>0$

Si hay una constante sumando o resta, ésta no afecta al dominio de la función.

👉 **Regla de oro:** en una desigualdad cuando se multiplica por un número negativo se invierte la desigualdad.`

👉 Para el ejercicio 8 el Dominio=$\mathbb{R}$ **¿Por qué?**

La expresión que nos había quedado era:

$$
y=\sqrt[3]{\frac{3t^2}{2}-\frac{3}{2}}
$$

El Dominio de esta función son todos los reales $\mathbb{R}$

En una raíz cúbica:

- No hay desigualdad que resolver.
- El radicando puede ser positivo negativo o cero.
- La función existe para todo $t$ real.
- La función solución existe para todo $t$ (raíz cúbica).
- En la ED original, $y=0$ cuando $t = \pm 1$, por lo que la derivada no está definida allí.
- El dominio del **problema de valor inicial** (con $t=1$) suele tomarse como $(-1, \infty)$ o similar.

### 🚀 Para recordar
- Raíz cuadrada: radicando $\geq 0$
---

## Bloque 4: Verificar soluciones


Para cada par (ED, función), verificar si es solución:

1. $$ y' = 2y, \quad y(t) = Ce^{2t} $$

2. $$ y'' + y = 0, \quad y(t) = A \sin(t) + B \cos(t) $$

3. $$ y'' - 9y = 0, \quad y(t) = Ce^{3t} + De^{-3t} $$

4. $$ y' = -3y, \quad y(t) = Ce^{-3t} $$

5. $$ y'' + 4y = 0, \quad y(t) = 2 \sin(2t) + 3 \cos(2t) $$

En este bloque aprendí que a una ecuación diferencial es una igualdad constituida por la función $y(t)$ y su derivada. En estos ejercicios nos dan una ecuación diferencial con una función $y(t)$ la cual debemos derivar y sustituir en la ECD para verificar que la función $y(t)$ es parte de la ECD.

$$
y'=2y\, , y(t)=Ce^{2t}
$$

Se deriva $y(t)=Ce^{2t}$:

$$
y'=C\cdot2e^{2t}
$$

$$
y'=2y(t)
$$

Se sustituye para comprobar que cumple con la ecuación diferencial:

$$
2y(t)=2y \rightarrow \text{Cumple}
$$

$$
\boxed{2y(t)=2y}
$$

---

## Bloque 5: Gráficas

Graficar cualitativamente (identificando características clave):

1. $$ f(t) = e^{3t} $$

2. $$ f(t) = e^{-t} $$

3. $$ f(t) = 2\sin(t) $$

4. $$ f(t) = \cos(2t) $$

5. $$ f(t) = 4\sin(2t) $$

6. $$ f(t) = 2e^{-2t} $$


#### 📋 Apuntes

- [Gráfico del Seno y Coseno](./Matemáticas_Gráfico_del_Seno_y_Coseno_teoría_24-03-2026.md).

👉 Aprendí sobre las gráficas exponenciales y gráficas de seno y coseno. 

---

## Resolución:

[Preparación para prueba diagnóstica](./Ecuaciones_Diferenciales_Preparación_para_prueba_diagnostica_Ejercicio_2026-03-24.pdf)


---

## 💥 Recordatorio

### 📌 Reglas de desigualdad

- Multiplicar o dividir por **negativo** → **invierte** el signo ($\geq$ se convierte en $\leq$).
- $t^2 \leq a$ → $-\sqrt{a} \leq t \leq \sqrt{a}$
- $t^2 \geq a$ → $t \leq -\sqrt{a}$ o $t \geq \sqrt{a}$

### 📌 Gráficas

| Función | Características |
|---------|-----------------|
| $e^{kt}$ | Crece si $k>0$, decrece si $k<0$. Pasa por $(0,1)$. Asíntota horizontal $y=0$. |
| $A \sin(\omega t)$ | Amplitud $A$, período $\frac{2\pi}{\omega}$, pasa por $(0,0)$ |
| $A \cos(\omega t)$ | Amplitud $A$, período $\frac{2\pi}{\omega}$, pasa por $(0,A)$ |

### 📌 Dominio de la solución

| Operación | Restricción |
|-----------|-------------|
| $\sqrt{\text{radicando}}$ | Radicando $\geq 0$ |
| $\frac{1}{\text{denominador}}$ | Denominador $\neq 0$ |
| $\ln(\text{argumento})$ | Argumento $> 0$ |

**Raíz cúbica** $\sqrt[3]{\cdot}$: sin restricción.