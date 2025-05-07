# WizeE (formerly Cline) – Autonomous Coding Agent for VSCode

## Development Setup

1. **VS Code Extensions**

    - When opening the project, VS Code will prompt you to install recommended extensions
    - These extensions are required for development - please accept all installation prompts
    - If you dismissed the prompts, you can install them manually from the Extensions panel

2. **Local Development**
    - Run `npm run install:all` to install dependencies
    - Run `npm run test` to run tests locally
    - Before submitting PR, run `npm run format:fix` to format your code

## Run locally


1. Clone the repository:
    ```bash
    git clone git@github.com:fulldiveVR/cline.git
    ```
2. Open the project in VSCode:
    ```bash
    code cline
    ```
3. Install the necessary dependencies for the extension and webview-gui:
    ```bash
    npm run install:all
    ```
4. Launch by pressing `F5` (or `Run`->`Start Debugging`) to open a new VSCode window with the extension loaded. (You may need to install the [esbuild problem matchers extension](https://marketplace.visualstudio.com/items?itemName=connor4312.esbuild-problem-matchers) if you run into issues building the project.)

</details>

## License

[Apache 2.0 © 2025 Cline Bot Inc.](./LICENSE)
