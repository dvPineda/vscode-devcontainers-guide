# 🚀 vscode-devcontainers-guide
This repository is a comprehensive guide to working with Visual Studio Code's DevContainers. This project provides a containerized development environment where you can work on your Next.js app built with TypeScript, ESLint, and Tailwind CSS.

## 📚 Prerequisites
Before you get started, make sure you have installed the following:
- [Visual Studio Code](https://code.visualstudio.com/)
- [DevContainers extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

## 🚀 Getting Started
Follow the steps below to get your development environment set up:

1. **Clone the repository**

   Clone this repository into your desired folder:

   ```
   git clone https://github.com/dvPineda/vscode-devcontainers-guide.git
   ```
   
2. **Open the repository in a DevContainer**

   Use the command palette (F1) in Visual Studio Code and select `Dev Containers: Open Folder in Container...` Then, navigate to the cloned repository.
   Choose the [Default Linux Universal](https://github.com/devcontainers/templates/tree/main/src/universal) configuration

4. **Run the Next.js application**

   Within the container, you can now run the Next.js application:

   ```
   npm run dev
   ```


## 🛠️ Technologies Used
- [Next.js](https://nextjs.org/) - A React framework for production.
- [TypeScript](https://www.typescriptlang.org/) - Static type definitions for JavaScript.
- [ESLint](https://eslint.org/) - Pluggable JavaScript linter.
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework.

## 🙌 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License
[MIT](https://choosealicense.com/licenses/mit/)
