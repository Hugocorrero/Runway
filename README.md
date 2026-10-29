# Runway · ¿Cuánto tiempo puedes aguantar sin tu sueldo?

Runway es un simulador que calcula cuántos meses puede mantenerse una persona sin su salario, estimando el impacto de perder el empleo, renunciar, reducir jornada o generar ingresos alternativos, y diseña un plan de ahorro para tomar esa decisión con seguridad.

## Qué hace

- **Runway financiero:** `Ahorros ÷ Gastos esenciales`, con semáforo (rojo < 3 meses, ámbar 3–6, verde > 6).
- **Escenarios con fecha exacta:** renuncia, despido (con paro estimado), cambio de jornada (reducción o aumento con porcentaje) y freelance.
- **Gráfica diaria de ahorros** y fecha en la que se agotan.
- **Plan de salida:** ahorro mensual necesario para renunciar dentro de X meses con un colchón de Y meses.
- **Alertas de riesgo:** deudas elevadas, gastos superiores a ingresos y aviso conductual.

> El cálculo del paro es una **estimación educativa**: 70 % de la base reguladora los primeros 180 días y 60 % después, con mínimos y máximos según hijos a cargo y el IPREM. Se requieren 360 días cotizados y estar inscrito como demandante de empleo.

## Tecnología

Web estática en HTML + CSS + JavaScript puro (un único archivo, sin librerías ni dependencias externas). Funciona en GitHub Pages sin configuración.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `runway`), público.
2. Sube `index.html` y `README.md` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos tu web estará en `https://TU-USUARIO.github.io/runway/`.

## Autoría

Proyecto académico. Autor/a: _(añade tu nombre y grupo)_
