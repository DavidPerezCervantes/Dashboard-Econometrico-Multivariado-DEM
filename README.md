# Dashboard Econométrico Multivariado (DEM)

Este repositorio contiene un Dashboard Econométrico Financiero premium desarrollado en **R Shiny** y compilado nativamente para web utilizando **WebAssembly (WebR y ShinyLive)**. 

## 🚀 Características
- **Ejecución 100% serverless**: La aplicación se ejecuta directamente en el navegador del cliente mediante WebAssembly, eliminando la necesidad de un servidor Shiny Pro o R central.
- **Multivariado**: Incluye modelos VAR/VECM, análisis de cointegración de Johansen, pruebas de raíz unitaria (ADF/KPSS), regresión MCO y un simulador de crisis/estrés financiero interactivo.
- **Apertura Directa**: Diseñado para abrirse de forma inmediata al visitar el enlace principal de GitHub Pages.

## 📁 Estructura del Repositorio
- `app/app.R`: El código fuente principal del dashboard en R Shiny.
- `.github/workflows/deploy.yml`: El flujo de trabajo automatizado de GitHub Actions que compila la aplicación a WebAssembly (`shinylive::export`) y la publica directamente en la raíz de **GitHub Pages**.

---
*Desarrollado con ❤️ para el análisis econométrico de vanguardia.*
