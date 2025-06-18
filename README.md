
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
4. Ejecuta npm i para instalar las dependencias
5. Ejecuta npx playwright install para instalar los navegadores y el framework Playwright

## Estructura de carpetas
- src\pages -> Objetos de la pagina
- src\tests -> Archivos spec donde se desarrollan las pruebas
- src\helpers\env -> Se almacenan datos de variables de entorno

## Ejecución de pruebas
1. Ejecutar todas las pruebas en navegadores sin interfaz gráfica (headless):
npx playwright test
2. Ejecutar pruebas en navegadores con interfaz gráfica:
npx playwright test --ui
