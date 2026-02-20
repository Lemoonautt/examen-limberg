# examen-limberg

1. Crear una clase llamada CuentaBancaria
2. Debe tener:
Atributos:
titular
numero_cuenta
saldo
Métodos:
mostrar_info() → muestra los datos de la cuenta
depositar(monto) → aumenta el saldo
retirar(monto) → disminuye el saldo si hay fondos suficientes

3. Crear una lista vacía
Ejemplo: cuentas = []
4. Crear las siguientes funciones
crear_cuenta()
Debe:
Pedir nombre del titular
Pedir número de cuenta
Pedir saldo inicial
Crear un objeto CuentaBancaria
Guardarlo en la lista
EJEMPLO:
nueva_cuenta=CuentaBancaria(titular, numero, saldo)
cuentas.append(nueva_cuenta)
mostrar_cuentas()
Debe:
Recorrer la lista con un bucle
Mostrar la información de cada cuenta usando el método mostrar_info()

realizar_deposito()
Debe:
Pedir número de cuenta
Buscar la cuenta en la lista
Pedir monto a depositar
Llamar al método depositar()
realizar_retiro()
Debe:
Pedir número de cuenta
Buscar la cuenta en la lista
Pedir monto a retirar
Validar que tenga saldo suficiente
Llamar al método retirar()

5. Crear un menú interactivo
El programa debe repetirse hasta que el usuario elija salir.
===== MENÚ =====
1. Crear cuenta
2. Mostrar cuentas
3. Depositar dinero
4. Retirar dinero
5. Salir
Debe usar:
while
if / elif / else
CONSIDERACIONES IMPORTANTES
No permitir retiros mayores al saldo.
Mostrar mensaje si la cuenta no existe.
El programa debe ejecutarse correctamente sin errores.