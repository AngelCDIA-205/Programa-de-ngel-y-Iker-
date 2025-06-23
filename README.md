# Programa-de-ngel-y-Iker-
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

if __name__ == "__main__":
    x = float(input("Ingrese el primer número: "))
    y = float(input("Ingrese el segundo número: "))
    print(f"Suma: {sumar(x, y)}")
    print(f"Resta: {restar(x, y)}")
def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero."
    return a / b

def main():
    print("Calculadora de multiplicación y división")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))
    
    opcion = input("¿Qué operación deseas realizar? (multiplicar/dividir): ").strip().lower()
    
    if opcion == "multiplicar":
        resultado = multiplicar(num1, num2)
        print(f"El resultado de multiplicar {num1} por {num2} es: {resultado}")
    elif opcion == "dividir":
        resultado = dividir(num1, num2)
        print(f"El resultado de dividir {num1} entre {num2} es: {resultado}")
    else:
        print("Opción no válida.")

if __name__ == "__main__":
    main()
