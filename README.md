 [React](https://reactjs.org/docs/getting-started.html)

npm
 ```bash
 npx create-react-app my-app
```
Yarn
```bash
 yarn create react-app project-name
```
QUICK REACT INSTALL
  ```bash
  cd Desktop
  git clone https://github.com/foisal-hossen/react-empty-project.git
  cd react-empty-project
  rm -fr .git
  npm i
  code .
  npm start
 ```
  
  
  [React Router](https://reactrouter.com/en/main/start/tutorial)

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

-------------------------------------------------------------
[ReaChart](https://recharts.org/en-US/guide)

* `npm install reacharts`
* `yarn add recharts` 

 [Tailwind](https://tailwindcss.com/docs/installation)
 
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
[daisyUI](https://daisyui.com/docs/install/)
```bash
npm i daisyui
```
```css
plugins: [require("daisyui")],
```

	
[forms](https://v1.tailwindcss.com/components/forms)
```bash
	npm install -D @tailwindcss/forms
  ```
	```css
	require('@tailwindcss/forms'),
```

[FONT AWASOME](https://fontawesome.com/start)

 1.  npm i --save @fortawesome/fontawesome-svg-core
	 @fortawesome/free-solid-svg-icons
	 @fortawesome/react-fontawesome

 1.1 yarn add @fortawesome/fontawesome-svg-core
	 yarn add @fortawesome/free-solid-svg-icons
	 yarn add @fortawesome/react-fontawesome

 2.import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
   import { faCoffee } from '@fortawesome/free-solid-svg-icons'
-------------------------

_redirects
/* /index.html 200

-------------------------------------------------

 1. npm i 
 
 1.1 npm i node-module
 
 2. npm install -g nodemon
 
 3.npm i colors mongodb


-------------------------------------fIRE bASE----------------------------

 1.npm install firebase
 
 ----------------Express js----------------------
 
 mkdir myapp
 npm init --y
 npm i express cors nodemon colors mongodb
