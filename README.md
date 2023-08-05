# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

---------------------><---------------------

## Déploiement sur GitHub Pages

Vous pouvez accéder à cette application en ligne en utilisant GitHub Pages. Pour déployer cette application à partir du dossier `src`, suivez ces étapes :

1. Assurez-vous que l'application fonctionne correctement localement en utilisant la commande `yarn start` pour lancer le serveur de développement.

2. Dans le fichier `package.json` de ce projet, assurez-vous que la propriété `"homepage"` est configurée avec le lien GitHub Pages de la forme `https://votre-utilisateur.github.io/votre-repo`, en remplaçant "votre-utilisateur" par votre nom d'utilisateur GitHub et "votre-repo" par le nom de ce repository.

3. Dans le terminal, exécutez la commande `yarn build` pour créer une version optimisée de l'application pour la production.

4. Installez le package `gh-pages` en exécutant la commande `yarn add gh-pages`.

5. Dans le fichier `package.json`, ajoutez le script `"deploy"` qui utilisera `gh-pages` pour déployer l'application sur GitHub Pages.

6. Déployez l'application en exécutant la commande `yarn deploy`. Cela créera une branche `gh-pages` dans ce repository contenant les fichiers optimisés de l'application.

7. Attendez quelques instants pour que GitHub Pages mette à jour votre site, puis accédez à l'application déployée en utilisant le lien GitHub Pages de la forme `https://votre-utilisateur.github.io/votre-repo`.

N'hésitez pas à me poser des questions si vous avez besoin d'aide supplémentaire ou rencontrez des problèmes lors du processus de déploiement.

---------------------><---------------------
# Site Web - OpenClassrooms

Ce projet a été créé dans le cadre d'une formation sur OpenClassrooms pour apprendre à développer des applications web avec React.

## Description du Projet

Ce site web a été réalisé à l'aide de Create React App, une plateforme de démarrage officielle de React développée par Facebook. Il s'agit d'un site de vente de plantes où les utilisateurs peuvent explorer différentes plantes, les ajouter au panier et effectuer des achats.

Le site utilise React pour construire l'interface utilisateur et gérer les interactions avec l'utilisateur. Il est conçu pour être réactif, ce qui signifie qu'il s'adapte automatiquement à différentes tailles d'écran, offrant ainsi une expérience utilisateur fluide aussi bien sur les ordinateurs de bureau que sur les appareils mobiles.

## Fonctionnalités du Site

- Affichage de la liste des plantes disponibles pour la vente, avec leurs caractéristiques et prix.
- Possibilité d'ajouter des plantes au panier en spécifiant la quantité souhaitée.
- Vue du panier avec la liste des articles sélectionnés et le montant total à payer.
- Possibilité de supprimer des articles du panier ou de modifier leur quantité.

## Installation et Lancement du Projet

Pour utiliser ce projet localement, suivez les étapes suivantes :

1. Cloner le dépôt GitHub sur votre machine locale.
2. Assurez-vous que Node.js et yarn sont installés sur votre système.
3. Dans le dossier du projet, exécutez la commande `yarn install` pour installer les dépendances.
4. Ensuite, lancez le projet avec la commande `yarn start`. Le site web sera accessible à l'adresse [http://localhost:3000](http://localhost:3000) dans votre navigateur.

## En savoir plus

Pour en savoir plus sur React et la création d'applications web avec Create React App, consultez la documentation officielle de React : [React Documentation](https://reactjs.org/).

Ce projet a été réalisé dans le cadre de la formation sur OpenClassrooms. Si vous souhaitez en savoir plus sur la formation et les projets réalisés, consultez [OpenClassrooms](https://openclassrooms.com/).

N'hésitez pas à explorer le code source du projet pour mieux comprendre comment il fonctionne et à apporter vos propres améliorations !

Merci d'avoir visité ce projet ! 😊
