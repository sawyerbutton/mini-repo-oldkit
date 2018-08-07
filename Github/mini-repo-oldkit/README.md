# MiniRepoOldkit

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Bug related with angular-devkit/build-angular:0.6.8 version

Added a component library,
trying to import 
```javascript
@import "~ng-zorro-antd/src/ng-zorro-antd.less";
```
into styles.less file,
when running ng serve, there is a fail.
```bash
ERROR in ./src/styles.less (./node_modules/raw-loader!./node_modules/postcss-loader/lib??embedded!./node_modules/less-loader/dist/cjs.js??ref--15-3!./src/styles.less)
Module build failed: 

/* You can add global styles to this file, and also import other style files */
@import "~ng-zorro-antd/src/ng-zorro-antd.less";
^
'~ng-zorro-antd/src/ng-zorro-antd.less' wasn't found. Tried - /Users/admin/Github/mini-repo-oldkit/src/~ng-zorro-antd/src/ng-zorro-antd.less,npm://~ng-zorro-antd/src/ng-zorro-antd.less,~ng-zorro-antd/src/ng-zorro-antd.less
      in /Users/admin/Github/mini-repo-oldkit/src/styles.less (line 2, column 0)

```

## Thanks for Angular team^.^, keep in touch in related issue.

