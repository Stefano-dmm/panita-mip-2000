# panita-mip-2000

El objetivo del proyecto es desarrollar un conversor de sistemas numéricos que permita al usuario introducir números en diferentes representaciones numéricas (binario en complemento a 2, decimal empaquetado, base 10, octal y hexadecimal) y convertirlos entre sí. El conversor debe ser capaz de manejar números con parte fraccionaria y debe ser desarrollado en assembler de MIPS para ser ejecutado en un MARM (Mips Assembly Run Machine) en el sistema operativo KaiOS.

Requerimientos

Representaciones numéricas permitidas:
Binario en Complemento a 2
Decimal Empaquetado
Base 10 (con signo + o -)
Octal (con signo + o -)
Hexadecimal (con signo + o -)
Funcionalidad para introducir números con parte fraccionaria y realizar conversiones de decimal a binario con 8 bits asociados a la parte fraccional.
Reutilización de código mediante el uso de macros.

Partes del proyecto:

1. Interface de Usuario (UI)??? /// nos dieron a entender que no era necesario

Permite la entrada de números en diferentes representaciones numéricas
Muestra los resultados en cada una de las representaciones numéricas permitidas
Interactúa con el usuario para recibir la entrada y mostrar los resultados

2. Análisis de Entrada

Analiza la entrada del usuario para determinar la representación numérica original del número
Verifica la validez de la entrada y devuelve un error si es necesario

3. Macros

decimal_to_bin: Convierte un número decimal a binario en complemento a 2
decimal_to_dec_emp: Convierte un número decimal a decimal empaquetado
decimal_to_oct: Convierte un número decimal a octal
decimal_to_hex: Convierte un número decimal a hexadecimal
bin_to_decimal: Convierte un número binario en complemento a 2 a decimal
dec_emp_to_decimal: Convierte un número decimal empaquetado a decimal
oct_to_decimal: Convierte un número octal a decimal
hex_to_decimal: Convierte un número hexadecimal a decimal

4. Manejo de Parte Fraccionaria

Maneja la parte fraccionaria de los números, permitiendo la entrada y salida de números con parte fraccionaria
Realiza las conversiones necesarias para manejar la parte fraccionaria correctamente

Stefano Di Michelangelo y Gabriel Longa
