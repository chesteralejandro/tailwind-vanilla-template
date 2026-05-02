# {{PROJECT_NAME}}

{{PROJECT_DESCRIPTION}}

<br />

## 📋 Prerequisites

- Node.js
- NPM
- VS Code
- Live Server Extension (VS Code)

## ⚙️ Setup & Installation

- Install dependencies

    ```bash
    npm install
    ```

- Check the import in `src/input.css`

    ```bash
    @import "tailwindcss";
    ```

- Start the Tailwind CLI build process.

    ```bash
    npm run tailwind
    ```

    > Behind the scene, this will run:

    ```bash
    npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
    ```

- Link the `src/output.css` in you HTML file and start using Tailwind.

    ```html
    <!doctype html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<meta
    			name="viewport"
    			content="width=device-width, initial-scale=1.0"
    		/>
    		<link href="./src/output.css" rel="stylesheet" />
    	</head>
    	<body>
    		<h1 class="text-3xl font-bold underline">Hello world!</h1>
    	</body>
    </html>
    ```

- Start the `Live Server` by clicking `Go Live` button at the bottom.

## 🛠️ Tech Stack

- HTML
- Tailwind CSS

## 📁 Folder Structure

```
📁 root/
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── README.md
└── 📁 src/
    ├── input.css
    └── output.css
```

## 🗒️ Official Docs

[https://tailwindcss.com/docs/installation/tailwind-cli](https://tailwindcss.com/docs/installation/tailwind-cli)
