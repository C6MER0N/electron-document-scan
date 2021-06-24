# Cross-platform Desktop Document Scanner 

The sample demonstrates how to create a desktop document scanning app with [Electron](http://electron.atom.io/docs/latest/tutorial/quick-start) and [Dynamic Web TWAIN SDK](https://www.dynamsoft.com/web-twain/overview/) for **Windows, Linux and macOS**.

## Requirements
1. Download [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/downloads).
2. Copy the `Resources` folder from `Dynamic Web TWAIN SDK <version number>\Resources` to your Electron project directory.

## A Basic Electron Application
Referring to [https://github.com/electron/electron-quick-start](https://github.com/electron/electron-quick-start), a basic Electron application needs just these files:

- package.json - Points to the app's main file and lists its details and dependencies.
- main.js - Starts the app and creates a browser window to render HTML. This is the app's main process.
- index.html - A web page to render. This is the app's renderer process.

## How to Run the Project

1. Install **Electron**:

    ```bash
    npm install -g electron
    ```
2. Copy `Resources` folder to `app` folder.
2. Get a [30-day FREE trial license](https://www.dynamsoft.com/customer/license/trialLicense) and update the following line in `Resources/dynamsoft.webtwain.config.js`:

    ```js
    Dynamsoft.DWT.ProductKey = 'LICENSE-KEY';
    ```

3. Run the app:

    ```
    cd app
    electron .
    # Or 
    # npx electron .
    ```

    ![electron document scanner](https://www.dynamsoft.com/codepool/img/2021/06/electron-document-scanner.png)


## Blog
[Cross-platform Document Scan Application with Electron](http://www.codepool.biz/crossplatform-document-scan-electron.html)
