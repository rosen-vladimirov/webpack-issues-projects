# ns-dev-webpack-issue-865

Sample project reproducing issue: https://github.com/NativeScript/nativescript-dev-webpack/issues/865

Steps to reproduce:
1. `tns run android`
2. Click on the buttons - only `BUTTON IN MAIN-PAGE` is working, others are not.

Without webpack:
1. Check app/main-page.js file and uncomment `non-webpack` section and comment `webpack` section.
2. Use `tns run android --no-bundle`
3. Click on the buttons - all of them are working.