# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full Stack Open course.

## Deployed Application
- **Live URL**: [https://fs-pokedex-g5vf.onrender.com/](https://fs-pokedex-g5vf.onrender.com/)

## CI/CD Pipeline
The project uses GitHub Actions for continuous integration (linting, build, Jest unit tests, Playwright end-to-end tests) and continuous deployment to Render.
Automatic deployments and semantic release tagging are skipped if the commit message contains `#skip`.

## Exercise 11.21: Custom CI/CD Pipeline Repository
- **Bloglist CI/CD Repository**: [https://github.com/GilbertIrumva/bloglist-ci-cd](https://github.com/GilbertIrumva/bloglist-ci-cd)

## Commands

Start by running `npm install` inside the project folder:

- `npm start`: run the webpack dev server
- `npm test`: run unit tests (Jest)
- `npm run eslint`: run ESLint
- `npm run build`: make a production build
- `npm run start-prod`: run the production build with Node/Express
- `npm run test:e2e`: run Playwright end-to-end tests
