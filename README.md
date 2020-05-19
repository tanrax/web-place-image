# Install

``` sh
npm install -g parcel-bundler
npm install tailwindcss
```

# Render css

``` sh
npx tailwind build css/tailwinds/main.css -o css/tailwinds/dist.css
```

# Dev

``` sh
parcel index.html --out-dir docs
```

# Production

``` sh
parcel build index.html --out-dir docs
```
