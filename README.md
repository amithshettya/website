# About
This is my personal website and blog, where I share my thoughts and experiences.

# Techstack
- Svelte
- TailwindCSS
- Vite
- GitHub Pages

# Dependencies
To build svelte as static site install pacakge
```
npm i -D @sveltejs/adapter-static
```

# Develop locally
npm run dev

# Release
## Generate static files
npm run build

## Copy build to github pages
cp -r build/* ../amithshettya.github.io

## Push changes
cd amithshettya.github.io
git add .
git commit -m "<version number> <month day>"
git push 