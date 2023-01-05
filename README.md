 > # [React](https://reactjs.org/docs/getting-started.html)

### [npm](https://www.npmjs.com/)
 ```bash
 npx create-react-app my-app
```
### [Yarn](https://yarnpkg.com/getting-started/install)
```bash
 yarn create react-app project-name
```
> ## QUICK REACT INSTALL
  ```bash
  git clone https://github.com/foisal-hossen/react-empty-project.git
  cd react-empty-project
  rm -fr .git
  npm i
  code .
  npm start
 ```
  
  > # [React Router](https://reactrouter.com/en/main/start/tutorial)

```bash
 npm install react-router-dom
```
```js
import {creatBrowserRouter} from 'react-router-dom'
	
 const router = createBrowserRouter([
	{
	path:'/',
	}
	])
	
  <RouterProvider router={router}></RouterProvider>
```

> # [ReaChart](https://recharts.org/en-US/guide)

* `npm install reacharts`
* `yarn add recharts` 

> # [Tailwind](https://tailwindcss.com/docs/installation)
 ###   implement in react
 ```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
```css
content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  ```
```css
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```
```bash
npm run start
```
> ### [daisyUI](https://daisyui.com/docs/install/)
```bash
npm i daisyui
```
```css
plugins: [require("daisyui")],
```	
> # [forms](https://v1.tailwindcss.com/components/forms)
   ### tailwind forms
```bash
	npm install -D @tailwindcss/forms
  ```
```css
	require('@tailwindcss/forms'),
```

> # [FONT AWASOME](https://fontawesome.com/start)

### npm

```bash
npm i --save @fortawesome/fontawesome-svg-core
npm i @fortawesome/free-solid-svg-icons
npm i @fortawesome/react-fontawesome
```
### Yarn
```bash
yarn add @fortawesome/fontawesome-svg-core
yarn add @fortawesome/free-solid-svg-icons
yarn add @fortawesome/react-fontawesome
```
```bash
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faCoffee } from '@fortawesome/free-solid-svg-icons'
```
---

 > ###  _redirects 
 ```css
  /* /index.html 200
```
other uses npm pakage
 - ` npm i `
 
 - ` npm i node-module`
 
 - ` npm install -g nodemon`
 
 - `npm i colors mongodb`


> # [Firebase](https://console.firebase.google.com/u/0/project/_/config)

```base
 npm install firebase
 ```
> # [Express js](https://expressjs.com/en/starter/installing.html)
 ```bash
 mkdir myapp
 npm init --y
 npm i express cors nodemon colors mongodb
```
