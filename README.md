# Frontend User Profile Theme for Grow

This Liferay DXP theme is created to extend the default, out of the box Liferay User Profile theme: https://github.com/liferay/liferay-portal/tree/7.0.x/modules/apps/foundation/frontend-theme/frontend-theme-user-profile

## How to use the theme
1) Install the Liferay Theme Generator as per these steps: https://dev.liferay.com/develop/tutorials/-/knowledge_base/7-0/themes-generator
2) Create a theme and replace the `src` folder created by default with the one of this repo
3) All changes to the theme's styling and functionalities can be done in the `$theme_root_folder/src` folder
4) To deploy, open a command prompt window or terminal on `$theme_root_folder` and run `gulp build` and `gulp deploy`
5) Once deployed in Liferay, ensure the theme is selected for the given set of pages / page

Tip: To quickly test whether all is connected and running, try adding this rule:

`#wrapper {
    background: red;
}`

at the bottom of the *_custom.scss* file and run steps 5-6: the final result should be a red background in the page

## Documentation
See https://dev.liferay.com/develop/tutorials/-/knowledge_base/7-0/themes-and-layout-templates

## Technologies and frameworks added to the default Liferay theme