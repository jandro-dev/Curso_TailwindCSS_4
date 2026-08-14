
<div align="center">

## LinkHub TailwindCSS

Centro de enlaces organizado en un layout bento grid moderno, construido con Tailwind CSS 4 y el CLI oficial sin frameworks.

</div>

<br>

## Para empezar

### Prerequisitos

- NVM (recomendado para asegurar versión de Node).  
  Ver [documentación oficial](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)

  ```sh
  nvm use
  # o
  nvm use <version>
  ```

- PNPM (recomendado por su eficiencia y rapidez)

  ```sh
  npm install -g pnpm
  ```

- o NPM

	```sh
	npm install npm@latest -g
	``` 

- Extensión **[Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)**

### Instalación

1. Clona el repositorio

   ```sh
   git clone https://github.com/jandro-dev/Curso_TailwindCSS_4.git
   ```

2. Instala los paquetes de NPM

   ```sh
   pnpm install
   ```

3. Ejecuta el watcher de Tailwind

   ```sh
   pnpx @tailwindcss/cli -i ./input.css -o ./assets/output.css --watch
	 ```
	
	 > 💡 Este comando escanea tus archivos HTML en busca de clases de Tailwind y genera/actualiza `output.css` automáticamente cada vez que guardas cambios.