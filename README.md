# hello-cordova-vuejs
A cordova template with vuejs2.x for creating cordova app.

# How to use

1. install with commond
 ```shell
cordova create your-cordova-project com.example.hello HelloC-V --template hello-cordova-vuejs
```

2. install cordova dependence
```shell
cd your-cordova-project/
cordova platform add browser
cordova run browser
```

# Start with project

install app dependence
```shell
cd your-cordova-project/myApp/
npm install
npm run dev
```

build with android or ios
```shell
cd your-cordova-project/myApp/
npm run build
cd ../
cordova paltform add android #cordova add ios
cordova build android #cordova build ios
```

# Todo
* Maybe use [Vue Material
](http://github.com/vuematerial/vue-material) or [MDUI](https://github.com/zdhxiong/mdui) for UI 
* add demo with Nativ Api

# Contributing
Please make sure to read the [Contributing Guide](https://github.com/vuematerial/vue-material/blob/master/.github/CONTRIBUTING.md) before making a pull request.

# Donate
Buy me a cup of coffee
![donate](https://raw.githubusercontent.com/jeeinn/pics/master/alipay-wepay.png)