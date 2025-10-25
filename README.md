# 🏦 Sistema Bancario en Java

Este proyecto implementa un sistema bancario simple en **Java**, permitiendo crear cuentas, consultar saldos, realizar depósitos, retiros y transferencias entre cuentas.  
Está diseñado para ejecutarse en consola y fue construido siguiendo principios básicos de **Programación Orientada a Objetos (POO)**.

---

## 📋 Características principales

- Creación de cuentas bancarias.
- Depósitos y retiros.
- Transferencias entre cuentas.
- Consulta de saldos.
- Validación de errores y entradas incorrectas.
- Persistencia temporal (los datos se mantienen mientras el programa está activo).

---

## 🧱 Estructura del proyecto

```
.
├── Banco.java
├── CuentaBancaria.java
└── README.md
```

### 🔹 `CuentaBancaria.java`
Contiene la clase principal `CuentaBancaria` con el método `main`, que gestiona el menú de interacción del usuario y las operaciones bancarias.

### 🔹 `Banco.java`
Contiene la clase `Banco`, que administra las cuentas, permite buscarlas por ID y coordina las operaciones entre ellas.

---

## 🚀 Ejecución

1. **Compila los archivos Java**:
   ```bash
   javac Banco.java CuentaBancaria.java
   ```

2. **Ejecuta el programa**:
   ```bash
   java CuentaBancaria
   ```

3. **Sigue las instrucciones del menú interactivo** en consola para crear cuentas, depositar, retirar, transferir o consultar saldo.

---

## 🧩 Ejemplo de uso

```
==== Menú Principal ====
1. Crear cuenta
2. Consultar saldo
3. Depositar
4. Retirar
5. Transferir
6. Salir
Seleccione una opción: 1

Ingrese el nombre del titular: Juan Pérez
Cuenta creada con ID: 1
```

---

## ⚙️ Requisitos

- Java JDK 11 o superior.
- Editor de texto o IDE (VS Code, IntelliJ IDEA, NetBeans, etc.).
- Consola de comandos.

---

## 🧠 Notas

- El programa utiliza `Optional<CuentaBancaria>` para manejar cuentas inexistentes sin causar errores.
- Los datos se guardan en memoria (no hay base de datos ni archivos externos).
- Se corrigieron errores de compilación (`System.out.print(s: ...)`) en la versión final.

