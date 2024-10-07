# Web Crawler en Go

Este proyecto es un **crawler web** básico implementado en Go. Su objetivo es rastrear páginas web a partir de una lista de URLs inicial y extraer todas las URLs encontradas en el contenido HTML. Utiliza goroutines para realizar el rastreo de manera concurrente, lo que mejora la eficiencia del proceso.

## Requisitos

- [Go](https://golang.org/dl/) (versión 1.16 o superior)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/web-crawler-go.git
   cd web-crawler-go
2. Asegúrate de tener el paquete golang.org/x/net/html instalado:
   ```bash
   go get golang.org/x/net/html
3. Uso, ejecutar el scraper o crawler, proporciona una o más URLs como argumentos de línea de comandos. Por ejemplo:
     ```bash
   go run main.go https://ejemplo.com https://ejemplo2.com

## GRACIAS!
