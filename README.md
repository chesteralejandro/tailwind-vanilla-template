# Tailwind CSS CLI

This is an example setup of TailwindCSS using the CLI.

## ⚙️ Setup

- Install Tailwind CSS.
    ```bash
    npm install tailwindcss @tailwindcss/cli
    ```
- Import Tailwind in your main CSS file.
    ```bash
    @import "tailwindcss";
    ```
- Start the Tailwind CLI build process.
    ```bash
    npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
    ```
- Start using the Tailwind in your HTML.
    ```html
    <!doctype html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<meta
    			name="viewport"
    			content="width=device-width, initial-scale=1.0"
    		/>
    		<link href="./output.css" rel="stylesheet" />
    	</head>
    	<body>
    		<h1 class="text-3xl font-bold underline">Hello world!</h1>
    	</body>
    </html>
    ```
