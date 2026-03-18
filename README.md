# Examen de 2 Evaluacion (Python,git,Markdown)

## Indice

1. [Ejercicio Propuesto](#1-ejercicio-propuesto)
2. [Realizacion del ejercicio](#2-realizacion-del-ejercicio)


<br><br>

---

## 1. Ejercicio propuesto

Se trata de un documento donde principalmente se nos pide crear un programa donde se le piden al *usuario* datos como su **nombre y edad** los cuales se mostraran por pantalla al terminar

Un formato muy parecido como este  

```cmd
Escribe tu nombre: John
Escribe edad: 45
John tiene 45 años
```
<br>

---

## 2. Realizacion del ejercicio

Para hacerlo creo una serie de variables

- Primera `nombre = str(input("Escribe tu nombre: "))`
    - En esta se ve como llamamos una variable con input
        - El usuario pondra su nombre :+1:
- Segunda `edad = int(input("Escribe edad: "))`
- Ahora seria la salida formateada con el printf `print(f"{nombre} tiene {edad} años")`

Codigo total:

```python
nombre = str(input("Escribe tu nombre: "))
edad = int(input("Escribe edad: "))
print(f"{nombre} tiene {edad} años")
```

<br>

[Enlace repositorio](https://github.com/JohnAngeloVera/Examen_2_Evaluacion)