Installing various plugin for supporting camera for taking picture and showing picture:
    Reference of Image site : https://devdactic.com/ionic-2-images/  
            
    https://ionicframework.com/docs/v3/native/camera/
    https://ionicframework.com/docs/v3/native/file/
    https://ionicframework.com/docs/v3/native/file-transfer/
    https://ionicframework.com/docs/v3/native/file-path/

For the issue: Not allowed to load local resource           (resolved)
    uninstall webview : ionic cordova plugins rm cordova-plugin-ionic-webview
    install old one : ionic cordova plugins add cordova-plugin-ionic-webview@1.2.1
    cordova clean android
    Refered by https://stackoverflow.com/questions/52055126/not-allowed-to-load-local-resource-ionic-3-android