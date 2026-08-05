# Calc
# Pseudocódigo – Calculadora básica

```
Inicio

    Escribir "CALCULADORA BÁSICA"
    Escribir "1. Suma"
    Escribir "2. Resta"
    Escribir "3. Multiplicación"
    Escribir "4. División"

    Escribir "Seleccione una opción:"
    Leer opcion

    Escribir "Ingrese el primer número:"
    Leer num1

    Escribir "Ingrese el segundo número:"
    Leer num2

    Segun opcion Hacer

        Caso 1:
            resultado ← num1 + num2
            Escribir "Resultado: ", resultado

        Caso 2:
            resultado ← num1 - num2
            Escribir "Resultado: ", resultado

        Caso 3:
            resultado ← num1 * num2
            Escribir "Resultado: ", resultado

        Caso 4:
            Si num2 = 0 Entonces
                Escribir "Error: No se puede dividir entre cero."
            Sino
                resultado ← num1 / num2
                Escribir "Resultado: ", resultado
            FinSi

        De Otro Modo:
            Escribir "Opción no válida."


    FinSegun

Fin
```
<img width="363" height="738" alt="Captura de pantalla 2026-08-05 140234" src="https://github.com/user-attachments/assets/3a288876-c9ca-4ef2-b961-a4a174c8bb54" />
