# Chrome Extension Boilerplate
Chrome Extension Boilerplate with React, Tailwind, Webpack

## Steps to setup:
Clone the repo, or run the starter command:
```sh
npx @athreelabs/chromex-react-tailwind-webpack-starter <your-project-root-dir>
```

Open terminal in the project folder and run: 
```sh
npm install
```
To build for production, run:
```sh
npm run build
```
This will create a _'build'_ folder in the root directory which will have the bundled files. Then add the extension to Chrome from the _'build'_ directory.

To view the popup page (index.html in this case), open the following link in Chrome:<br>
_chrome-extension://\<extension-ID\>/index.html_

(optional) During development, run the following command to watch and recompile whenever a file changes:
```sh
npm run dev
```

## License
MIT
