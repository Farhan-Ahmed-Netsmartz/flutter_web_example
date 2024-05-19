# flutter_web_example

Flutter project configured for deployment on the web through GitHub Pages and a custom domain.

[See this repo for actual hosted project](https://github.com/davefaliskie/flutter-website)

## Deploying on Web

```
make deploy-web
```

## Watch The Video
[![Watch the video](https://img.youtube.com/vi/iOra0bxlWdE/maxresdefault.jpg)](https://youtu.be/iOra0bxlWdE)


---
flutter clean
flutter pub get
flutter build web --base-href /flutter-website/ --release

cd .\build\web\
git init
git add .
git commit -m "Deploy this"
