#  Bootstrap Interactivo

Simulador animado del método de remuestreo bootstrap para comprender su lógica y finalidad de forma visual e intuitiva.

🔗 **[Ver demo en vivo](https://fcontiggiani.github.io/bootstrap-interactivo/)**

---

## ¿Qué es el bootstrap?

El bootstrap es una técnica estadística de **remuestreo con reposición** que permite aproximar la distribución muestral de un estadístico (por ejemplo, la media) sin necesidad de asumir ninguna distribución poblacional subyacente.

La idea central: si la muestra disponible es una buena representación de la población, entonces remuestrear repetidamente *desde esa muestra* simula lo que ocurriría si repitiéramos el muestreo en el mundo real.

---

## ¿Qué hace este simulador?

- Muestra una **muestra original** de n = 20 datos ficticios de ingresos
- Permite generar **muestras bootstrap** de a una o de a 100
- Construye la **distribución bootstrap de la media** en tiempo real
- Calcula el **intervalo de confianza al 95% por el método del percentil**
- Visualiza cómo el IC converge a medida que aumentan los resampleos

---

## Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- [Chart.js 4.4](https://www.chartjs.org/) para el histograma
- Sin frameworks, sin dependencias adicionales — un solo archivo `.html`

---

## Uso local

Simplemente abrí `index.html` en cualquier navegador moderno. No requiere servidor ni instalación.

```bash
git clone https://github.com/fcontiggiani/bootstrap-interactivo.git
cd bootstrap-interactivo
# abrí index.html en tu navegador
```

---

## Autor

Desarrollado con fines educativos en el marco de actividades del  
[Instituto de Investigaciones en Políticas Públicas y Gobierno (IIPPyG)](https://unrn.edu.ar)  
Universidad Nacional de Río Negro — Sede Atlántica

---

## Licencia

[MIT](LICENSE) — libre para usar, modificar y distribuir con atribución.
