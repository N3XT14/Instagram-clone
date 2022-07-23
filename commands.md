* flutter pub outdated
    > List outdated packages
* flutter upgrade outdated_package
    > upgrade the outdated packages
* flutter clean
    > performs cleanup of dependencies
* flutter pub get
    > Will add get package
* flutter run -d edge --web-renderer html
    > if --web-renderer html is not provided then it will load canvas which causes lots of issue on flutter web
    > In case of release it will using html only.
* if(!mounted) return
    > When a BuildContext is used from a StatefulWidget, the mounted property must be checked after an asynchronous gap.