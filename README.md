# FizzBuzz-en-Python-Mi-soluci-n-a-un-ejercicio-cl-sico-de-programaci-n
Este programa resuelve el desafío FizzBuzz, que evalúa si un número es divisible por 3, 5 o ambos, y muestra 'Fizz', 'Buzz' o 'FizzBuzz'. Demuestra mi manejo de bucles, condicionales y operadores en Python, habilidades básicas pero esenciales en desarrollo
# FizzBuzz en Python: Mi solución a un ejercicio clásico de programación

## 📜 Descripción breve
Este programa resuelve el desafío **FizzBuzz**, que evalúa si un número es divisible por 3, 5 o ambos, y muestra **"Fizz"**, **"Buzz"** o **"FizzBuzz"**.  
Demuestra mi manejo de bucles, condicionales y operadores en Python, habilidades básicas pero esenciales en desarrollo de software.

## 💻 Código de ejemplo
```python
for numero in range(1, 21):
    if numero % 15 == 0:  # 3*5
        print("Fizz Buzz")
    elif numero % 3 == 0:
        print("Fizz")
    elif numero % 5 == 0:
        print("Buzz")
    else:
        print(numero)
