# Azure Hello World Node.js App

This is a sample Node.js 22 LTS web app using Express.js. It displays a simple "Hello World" message and is ready for deployment to Azure.

## Running Locally

1. Install dependencies:
   ```powershell
   npm install
   ```
2. Start the server:
   ```powershell
   npm start
   ```
3. Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Deploying to Azure

You can deploy this app to Azure App Service using the Azure Tools extension in VS Code.

1. Install the [Azure Tools extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack) in VS Code.
2. Sign in to your Azure account in VS Code.
3. Right-click the project folder and select **Deploy to Web App**.
4. Follow the prompts to create a new Web App or select an existing one.

For more details, see the [official Azure Node.js deployment guide](https://docs.microsoft.com/azure/app-service/quickstart-nodejs?tabs=windows).
