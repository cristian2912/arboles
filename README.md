# Punto 1

**expresion 1**
![image](https://github.com/user-attachments/assets/3169bf0e-391d-4750-9e97-1a2e35dbc624)

**expresion 2**
![image](https://github.com/user-attachments/assets/99f83856-1e6e-4477-a6c9-27afba8f0917)


Expresión 1: (A + (B * ( - (C + D ) ) ))
Conversión a postfija:

Pasos:
Evaluar la suma C + D → C D +
Evaluar el negativo de la suma → C D + -
Multiplicar por B → B C D + - *
Sumar a A → A B C D + - * +
Resultado postfijo: A B C D + - * +

Árbol binario:

El nodo raíz es +.
La rama izquierda es A.
La rama derecha tiene como raíz *:
Hijo izquierdo: B.
Hijo derecho: -:
Hijo izquierdo: C.
Hijo derecho: D.
Expresión 2: ((C + D) / (B * (A − D)))
Conversión a postfija:

Pasos:
Evaluar la suma C + D → C D +
Evaluar la resta A - D → A D -
Multiplicar B * (A - D) → B A D - *
Dividir (C + D) / (B * (A - D)) → C D + B A D - * /
Resultado postfijo: C D + B A D - * /

Árbol binario:

El nodo raíz es /.
La rama izquierda tiene como raíz +:
Hijo izquierdo: C.
Hijo derecho: D.
La rama derecha tiene como raíz *:
Hijo izquierdo: B.
Hijo derecho: -:
Hijo izquierdo: A.
Hijo derecho: D.

# Punto 2

![image](https://github.com/user-attachments/assets/9d5cdfdf-f4c1-4e81-842c-1491014ce0ab)


Inorden: X, Y, W, Z, T, K
Preorden: Z, Y, X, W, T, K
Postorden: X, W, Y, K, T, Z
Construcción del árbol binario:
La raíz del árbol es el primer elemento del preorden: Z.
Dividimos el inorden en dos partes:
Izquierda de Z: X, Y, W.
Derecha de Z: T, K.
Repetimos el proceso recursivamente para cada subárbol.
Árbol binario final:

Raíz: Z.
Hijo izquierdo: Y:
Hijo izquierdo: X.
Hijo derecho: W.
Hijo derecho: T:
Hijo derecho: K.

# punto 3

![image](https://github.com/user-attachments/assets/898a7480-2568-46c6-aa2a-3de8ac97cdb1)


Expresión: + − 8 * 2 3 * 4 − 9 7
Convertir la expresión a un árbol binario:

Nodo raíz: +.
Hijo izquierdo: -:
Hijo izquierdo: 8.
Hijo derecho: *:
Hijo izquierdo: 2.
Hijo derecho: 3.
Hijo derecho: *:
Hijo izquierdo: 4.
Hijo derecho: -:
Hijo izquierdo: 9.
Hijo derecho: 7.
Evaluar la expresión en preorden:

Preorden de este árbol: + − 8 * 2 3 * 4 − 9 7.
Evaluamos paso a paso:
C = 2 * 3 = 6.
B = 8 - 6 = 2.
A = 9 - 7 = 2.
D = 4 * 2 = 8.
Resultado = 2 + 8 = 10.
Resultado: 10.


# punto 4

![image](https://github.com/user-attachments/assets/c1477719-6fca-4f69-aab1-75d5888f59d7)

Nodos Hoja son: -14, -12, 1, 3, 8
Nodos de 2 hijos:
   El -13 tiene 2 hijos: -14 y -1


