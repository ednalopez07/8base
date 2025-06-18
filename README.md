
# 8base Proyecto
Este proyecto es una Tienda virtual que permite comprar artículos.

## Si eres nuevo en Playwright
Lee la documentación: https://playwright.dev/docs/intro
Lee sobre la extensión para VS Code: https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright

## Estructura del proyecto
src -> Contiene todo el código necesario para desarrollar las pruebas

## ¿Cómo empezar?
Configuración:
Clona o descarga el proyecto
Extrae y abre en VS Code
Instala la extensión Playwright para VS Code: https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright
Ejecuta npm i para instalar las dependencias
Ejecuta npx playwright install para instalar los navegadores y el framework Playwright

## Estructura de carpetas
src\pages -> Objetos de la pagina
src\tests -> Archivos spec donde se desarrollan las pruebas
src\helpers\env -> Se almacenan datos de variables de entorno

## Ejecución de pruebas
Ejecutar todas las pruebas en navegadores sin interfaz gráfica (headless):
npx playwright test
Ejecutar pruebas en navegadores con interfaz gráfica:
npx playwright test --ui
