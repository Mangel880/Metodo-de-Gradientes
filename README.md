# Simulador de planificación financiera mediante GCP

Proyecto académico para Métodos Numéricos — mención Ingeniería de Sistemas.

## Contenido
- `index.html`: aplicación web autocontenida (HTML, CSS y JavaScript).
- Tres escenarios precargados: ideal, bajo estrés y mal condicionado.
- Editor interactivo de matriz A, vector b, vector inicial, tolerancia e iteraciones.
- Validación de simetría y definición positiva mediante factorización de Cholesky.
- Solución de referencia por Cholesky.
- Implementación de Gradientes Conjugados (GC) y Gradientes Conjugados Precondicionado (GCP) con precondicionador Jacobi.
- Errores absolutos, relativos y porcentuales por variable.
- Números de condición espectrales y gráficos de convergencia.
- Cuatro pruebas QA automatizadas.
- Exportación de resultados a CSV.

## Ejecución local
No requiere instalación de dependencias ni servidor:
1. Descargue o clone el repositorio.
2. Abra `index.html` en un navegador moderno.

Para probarlo con un servidor local:
```bash
python -m http.server 8000
```
Luego visite `http://localhost:8000`.


