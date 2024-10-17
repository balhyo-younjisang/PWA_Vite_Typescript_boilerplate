<h1 align="center">
PWA Vite React Boilerplate
</h1>
<div>&nbsp</div>
<div align='center'>
<a href='https://pwa-vite-react-boilerplate.netlify.app/'>
<img width='480' src='https://user-images.githubusercontent.com/39476147/184496091-35faa26b-4591-45bc-90cb-6a215f600e2d.png'/>
</a>
</div>
<div>&nbsp</div>

<div flex align='center'>
<img height=30 src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" />
<img height=30 src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" />
</div>


<div>&nbsp</div><div>&nbsp</div><div>&nbsp</div>

# Boilerplate Techstack
This boilerplate is already preinstalled with:
* *[Vite Plugin PWA](https://vite-plugin-pwa.netlify.app/)* to generate the manifest JSON for *[progressive web app (PWA)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)*.
* *[Vite.js](https://vitejs.dev/)* frontend tooling to build for production.
* *[React.js](https://reactjs.org/)* with TypeScript support.

<div>&nbsp</div><div>&nbsp</div><div>&nbsp</div>

# How To Use
## Generate GitHub repository
1. Generate your repository from this template: *[Click Here](https://github.com/balhyo-younjisang/PWA_Vite_Typescript_boilerplate/generate)*
2. Clone code to your to remote repository: `git clone https://github.com/user-name/repository-name`

Note: supply your GitHub user-name and repository-name.



## Development
The following terminal commands are from *[Vite.js command line interface](https://vitejs.dev/guide/#command-line-interface)*. Also check the *[package.json](https://github.com/MengLinMaker/PWA-Vite-React-Boilerplate/blob/main/package.json)* file "scripts" section for all command line scripts.

Note: *[npm](https://www.npmjs.com/)* can also be replaced with *[yarn](https://yarnpkg.com/)* or *[pnpm](https://pnpm.io/)*...



### Run development website locally
```
npm run dev
```
* There is no PWA functionality in development mode.



### Build production files - to "dist" folder
```
npm run build
```
* Ensure there are no TypeScript errors, otherwise complilation will be aborted.
* Build files will be placed in the "dist" folder by default.
* To change build folder, add this line to *[vite.config.ts](https://github.com/MengLinMaker/PWA-Vite-React-Boilerplate/blob/main/vite.config.ts)* `defineConfig`:
```javascript
build: {
  outDir: './build-directory'
},
```



### Run production build website locally
```
npm run preview
```


