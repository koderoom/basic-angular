# BasicAngular

* Generate Additional Module
```
    ng g m route --spec=false --flat=true
```

* Generate Component
```
    ng g c home --spec=false --module=route
    ng g c page1 --spec=false --module=route
    ng g c page2 --spec=false --module=route
```


* [Angular Cli](https://github.com/angular-schule/angular-cli-ghpages)

```
    npm i angular-cli-ghpages --save-dev
    ng build --prod --base-href "https://koderoom.github.io/basic-angular/"
    npx ngh --dir=dist/basic-angular
```
