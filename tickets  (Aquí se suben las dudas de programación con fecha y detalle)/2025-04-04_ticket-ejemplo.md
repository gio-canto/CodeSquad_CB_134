# Ticket de ejemplo – 2025-04-04

**Lenguaje:** C++  
**Tipo de duda:** Código en revisión / Error de compilador / Duda externa

---

## Descripción del problema

Estoy tratando de entender cómo funciona un ciclo `for`. Este es el código que estoy usando:

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; i++) {
        cout << i << endl
    }
    return 0;
}
```

Me sale un error cuando compilo, pero no entiendo qué significa ni cómo arreglarlo.

---

## Mensaje del compilador

```
expected ';' before '}' token
```

No sé en qué parte del código falta el punto y coma.

---

## ¿Qué intentaste hacer?

Intenté agregar un punto y coma al final de la línea `cout << i << endl`, pero no sé si era el problema real.

---

## Qué esperas que pase

Espero que el código imprima los números del 0 al 4, uno por línea, sin errores de compilación.

---

## Duda externa (opcional)

Además, ¿cómo se haría esto mismo pero usando un ciclo `while`?

---

## Notas adicionales

Estoy usando Code::Blocks y soy nuevo en C++.  
No tengo claro cómo interpretar los mensajes del compilador.

---

Gracias por su ayuda 🙏

## 🖊️ Autor del ticket

**Nombre:** Gio Antonio  
**Fecha:** 2025-04-04  
**Grupo:** 1°C  
**Contacto (opcional):** gio@ejemplo.com

---

## 🔁 Respuestas a esta duda

### ✅ Respuesta 1

**Nombre del compañero(a):** Ana P.  
**Fecha:** 2025-04-04

Hola, revisé tu código y el problema está en que olvidaste un punto y coma al final de la línea:

```cpp
cout << i << endl;
