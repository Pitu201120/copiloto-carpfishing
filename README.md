# Copiloto Carpfishing Web App v1

Este proyecto está preparado para usarse de dos maneras:

## Opción 1: verlo en local en tu PC
1. Descarga y descomprime este proyecto.
2. Entra en la carpeta del proyecto.
3. Haz doble clic en `index.html`.

Eso te deja ver la app en el navegador.

### Mejor forma local
Algunas funciones externas como mapa y meteorología suelen funcionar mejor si lo abres con un servidor local.

#### En Windows
1. Abre la carpeta del proyecto.
2. En la barra de dirección escribe `cmd` y pulsa Enter.
3. En la ventana negra escribe:

```bash
python -m http.server 8000
```

4. Abre el navegador y entra en:

```text
http://localhost:8000
```

## Opción 2: subirlo a Vercel
Esta es la opción recomendada para usarlo bien en el móvil.

### Método fácil con GitHub + Vercel
1. Crea una cuenta en GitHub.
2. Sube esta carpeta a un repositorio nuevo.
3. Crea una cuenta en Vercel.
4. En Vercel, pulsa `Add New` → `Project`.
5. Conecta tu repositorio de GitHub.
6. Vercel detectará que es un proyecto estático.
7. Pulsa `Deploy`.

Cuando termine, Vercel te dará una URL pública.

## Archivos del proyecto
- `index.html` → la app
- `README.md` → esta guía
- `vercel.json` → configuración simple para Vercel

## Qué funciona ya
- mapa normal y satélite
- meteorología básica
- alertas meteorológicas simples
- planificación previa de concurso
- estrategia previa
- chat táctico básico
- registro de picadas y capturas
- métricas de sesión

## Qué falta para una app profesional
- base de datos online real
- cuentas de usuario
- guardar sesiones en nube
- notificaciones push reales
- motor de estrategia más avanzado
- más embalses y conocimiento específico
