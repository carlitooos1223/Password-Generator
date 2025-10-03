# Generador de Contraseñas Seguras

Este proyecto contiene un script en **Bash** (`script.sh`) que genera una contraseña aleatoria y segura con las siguientes características:

- Al menos un carácter especial
- Al menos un dígito
- Al menos una letra mayúscula
- Al menos una letra minúscula
- Longitud total de 12 caracteres

## Lenguaje

- **Bash (Bourne Again Shell)**

## ¿Cómo funciona?

El script define una función `generatePassword` que:
1. Selecciona un carácter de cada categoría requerida (especial, dígito, mayúscula, minúscula).
2. Completa el resto de la contraseña con caracteres aleatorios permitidos.
3. Mezcla el resultado para asegurar aleatoriedad.
4. Imprime la contraseña generada por pantalla.

## Uso

1. **Haz el script ejecutable** (si es necesario):

   ```sh
   chmod +x script.sh
   ```
