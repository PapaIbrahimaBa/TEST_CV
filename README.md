# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
-creer un projet react nommer 001 avec vite (pas avec npm create...app)  noter toute les etapes de *creation expliquer le role les dosssiers et certains types indispensables au projet
*creer votre CV avec les composants svts info perso, competences et experiences on aura 3 fichiers 
        MES ETAPES
Pour creer le projet j'ai utilise npm create vite@latest 001
reponse au question : J'ai mis React comme framework, JS comme langage, eslint et No pour install
cd 001 entrer dans le dossier
npm install : Telecharge les dependances (creer node_modules)
npm run dev lance le projet 
ouvrir http://localhost:5173 
Les fichiers indispensables : index.html, package.json, main.jsx, app.jsx 
export default veut dire : « ce fichier met cette fonction à disposition des autres fichiers ».
import on importe le fichier de exemple : infoPerso.jsx a App.jsx 