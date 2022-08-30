# Astro Crash Course

### Traversy Media

[video tutorial link](https://www.youtube.com/watch?v=Oi9z5gfIHJs)

[youtube channel link](https://www.youtube.com/c/TraversyMedia)

<br>

## Setup

<br>

### Dev Setup

intall dependencies.

```powershell
$ npm i
```

running dev server.

```powershell
$ npm run dev
```

<br>

### Buiding Production Site

installing dependencies and building the project.

```powershell
$ npm i
$ npm run build
```

previewing the production build locally.

```powershell
$ npm run preview
```

<br>

## Deployment

### Deployed on [Netlify](https://www.netlify.com/)

To deploy on netlify, add the project to your github and choose the repo in your netlify dashboard.

just make sure that:

- Build command: `npm run build`
- and Publish directory: `dist`

site url:
[https://astro-crash-course-tm.netlify.app/](https://astro-crash-course-tm.netlify.app/)
