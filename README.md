# Convertisseur de Fichiers Multimédias

Application web permettant de convertir facilement des images et vidéos entre différents formats (JPG, PNG, WEBP, MP4, MOV, etc.).

Projet développé par [Amaury Meiller](https://meillerweb.fr).

## Fonctionnalités

- 🖼️ Upload de fichiers par glisser-déposer ou sélection
- 🧠 Détection automatique du type de fichier
- 🔁 Conversion entre différents formats
- 📥 Téléchargement du fichier converti
- 🌙 Mode sombre
- 📱 Interface responsive

## Technologies utilisées

- [Next.js](https://nextjs.org/) - Framework React
- [TypeScript](https://www.typescriptlang.org/) - Typage statique
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [FFmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) - Traitement de médias côté client
- [React Dropzone](https://react-dropzone.js.org/) - Gestion du drag & drop

## Installation

### Prérequis

- Node.js 16.x ou supérieur
- npm ou yarn

### Étapes d'installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/amaurymeiller/convertisseur.git
   cd convertisseur
   ```

2. Installez les dépendances :
   ```bash
   npm install
   # ou
   yarn install
   ```

3. Lancez le serveur de développement :
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

4. Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur pour voir l'application.

## Déploiement

L'application peut être facilement déployée sur Vercel, Netlify ou GitHub Pages.

### Déploiement sur Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Famaurymeiller%2Fconvertisseur)

## Comment utiliser

1. Faites glisser une image ou une vidéo dans la zone de dépôt ou cliquez pour sélectionner un fichier
2. Choisissez le format de sortie souhaité dans la liste déroulante
3. Ajustez les options de qualité si nécessaire
4. Cliquez sur "Convertir"
5. Une fois la conversion terminée, téléchargez le fichier converti

## Limites actuelles

- La taille maximale des fichiers dépend des ressources du navigateur client
- Certaines conversions peuvent prendre du temps en fonction de la taille du fichier et de la puissance de l'appareil
- La conversion de vidéos est plus limitée que celle des images

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

1. Forkez le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/amazing-feature`)
3. Committez vos changements (`git commit -m 'Add some amazing feature'`)
4. Pushez vers la branche (`git push origin feature/amazing-feature`)
5. Ouvrez une Pull Request

## Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

## Contact

Amaury Meiller - [meillerweb.fr](https://meillerweb.fr)
#   c o n v e r t i s s e u r  
 