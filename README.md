
<h1 align="center">Mobile App Landing for GitHub Pages for SyncedCounter application</h1>

## Made for [SyncedCounter.app](https://syncedcounter.app)

### Based on the original [template created by Sandoche](https://github.com/sandoche/Mobile-app-landingpage-template) and adapted to use with GitHub Actions:
```
.github/workflows/jekyll.yml
```
##

## 📖 How to use

### The normal way

1. Fork this project
2. Edit `_config.yml`, feel free to commut/uncomment what you need (google analtytics, or github for example)
3. Edit `_data/app.yml` with your app data
4. Update the text from `_data/strings.yml`, you can customize there the footer's links
5. Edit icons and screenshots inside the `_images` folder and `icon.png` in the root
6. Edit `_src/index.js` to update the product hunt modal (or to remove it) and to remove the darkmode plugin if you don't want it
7. Deploy (on netlify, gitpages or surge, they are all free)


## ⚙️ How to run

### Pre-requisites
- NodeJS
- Ruby, Bundler

### Install
```
npm install
bundler install
```

### Development
```
npm start
```

### Build
```
npm run build
```

### Update gem version (Gemfile.lock)
```
   bundle install
```

### More documentation
This templates uses [Jekyll-webpack-boilerplate](https://github.com/sandoche/Jekyll-webpack-boilerplate), read more documentation there.

