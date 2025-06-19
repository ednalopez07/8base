
# 8base Proyecto
Este proyecto es una Tienda virtual que permite comprar artículos.

## Si eres nuevo en Playwright
- Lee la documentación: https://playwright.dev/docs/intro
- Lee sobre la extensión para VS Code: https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright

## Estructura del proyecto
src -> Contiene todo el código necesario para desarrollar las pruebas

## ¿Cómo empezar?
Configuración:
1. Clona o descarga el proyecto
2. Extrae y abre en VS Code
3. Instala la extensión Playwright para VS Code: https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright
4. Ejecuta npm instal 
5. Ejecuta npm install @playwright/test
6. Ejecuta npx playwright install para instalar los navegadores y el framework Playwright

## Estructura de carpetas
- test\pages -> Objetos de la pagina
- test\tests -> Archivos spec donde se desarrollan las pruebas
- test\helpers\env -> Se almacenan datos de variables de entorno

## Ejecución de pruebas
1. Ejecutar todas las pruebas en navegadores sin interfaz gráfica:
npx playwright test
2. Ejecutar pruebas en navegadores con interfaz gráfica:
npx playwright test --ui
