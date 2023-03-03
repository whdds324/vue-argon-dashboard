# [Vue Argon Dashboard 2](http://demos.creative-tim.com/vue-argon-dashboard/?ref=readme-vad) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https://www.creative-tim.com/product/vue-argon-dashboard&text=Check%20Vue%Argon%20Dashboard%20made%20by%20@CreativeTim%20#webdesign%20#dashboard%20#argondesign%20#vue%20https://www.creative-tim.com/product/vue-argon-dashboard)

![version](https://img.shields.io/badge/version-3.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/vue-argon-dashboard.svg)](https://github.com/creativetimofficial/vue-argon-dashboard/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/vue-argon-dashboard.svg)](https://github.com/creativetimofficial/vue-argon-dashboard/issues?q=is%3Aissue+is%3Aclosed)

![Image](https://s3.amazonaws.com/creativetim_bucket/products/156/original/vue-argon-dashboard.jpg)

View [all components here](https://www.creative-tim.com/learning-lab/vue/alerts/argon-dashboard/).

**초기 설정 꿀팁**<br />
1. node 설치 > 버전확인 [node -v] >  
2. git 설치
3. vscode 설치
4. 소스내려받기 https://github.com/whdds324/bootstrap-vue-argon-dashboard.git
5. 프로젝트 루트에서 > npm install
6. local 올리기 > npm serve
7. npm serve 시 [error:0308010C:digital envelope routines::unsupported] 에러 발생할 경우 node 버전 다운그레이드 해야함(https://ahn3330.tistory.com/45)
8. 저는 16.13.0 .버전 사용


**Documentation built by Developers**<br />
Each element is well presented in very complex documentation.
You can read more about the [documentation here](https://www.creative-tim.com/learning-lab/vue/overview/argon-dashboard/).

**Example Pages**<br />
If you want to get inspiration or just show something directly to your clients, you can jump-start your development with our pre-built example pages. Every page is spaced well, with attractive layouts and pleasing shapes. Vue Argon Dashboard 2 has everything you need to quickly set up an amazing project.

View [example pages here](https://demos.creative-tim.com/vue-argon-dashboard/).

**HELPFUL LINKS**

- View [Github Repository](https://github.com/creativetimofficial/vue-argon-dashboard)
- Check [FAQ Page](https://www.creative-tim.com/faq)

## Table of Contents

- [Versions](#versions)
- [Demo](#demo)
- [Quick Start](#quick-start)
- [Documentation](#documentation)
- [File Structure](#file-structure)
- [Browser Support](#browser-support)
- [Resources](#resources)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions)
- [Licensing](#licensing)
- [Useful Links](#useful-links)

## Versions

[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/vue-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/vue-argon-dashboard?ref=readme-vad)

| VueJS |
| ----- |

| [![Vue Argon Dashboard 2](https://s3.amazonaws.com/creativetim_bucket/products/156/orginal/vue-argon-dashboard.jpg)](http://demos.creative-tim.com/vue-argon-dashboard/?ref=readme-vad)

## Demo

- [Profile](https://demos.creative-tim.com/vue-argon-dashboard/#/profile?ref=readme-vad)
- [Sign In](https://demos.creative-tim.com/vue-argon-dashboard/#/sign-in?ref=readme-vad)
- [Sign Up](https://demos.creative-tim.com/vue-argon-dashboard/#/sign-up?ref=readme-vad)

[View More](https://demos.creative-tim.com/vue-argon-dashboard/#/dashboard-default?ref=readme-vad).

## Quick start

Quick start options:

- Download from [Creative Tim](https://www.creative-tim.com/product/vue-argon-dashboard?ref=readme-vad).

## Terminal Commands

1. Download and Install NodeJs LTS version from [NodeJs Official Page](https://nodejs.org/en/download/).
2. Navigate to the root ./ directory of the product and run `npm install` to install our local dependencies.

## Documentation

The documentation for the Vue Argon Dashboard 2 is hosted at our [website](https://www.creative-tim.com/learning-lab/vue/overview/argon-dashboard/?ref=readme-vad).

### What's included

Within the download you'll find the following directories and files:

```
vue-argon-dashboard
    ├── public
    │   ├── favicon.png
    │   └── index.html
    ├── src
    │   ├── assets
    │   │   ├── css
    │   │   ├── fonts
    │   │   ├── img
    │   │   ├── js
    │   │   └── scss
    │   ├── components
    │   │   ├── ArgonAlert.vue
    │   │   ├── ArgonAvatar.vue
    │   │   ├── ArgonBadge.vue
    │   │   ├── ArgonButton.vue
    │   │   ├── ArgonCheckbox.vue
    │   │   ├── ArgonInput.vue
    │   │   ├── ArgonPagination.vue
    │   │   ├── ArgonPaginationItem.vue
    │   │   ├── ArgonProgress.vue
    │   │   ├── ArgonRadio.vue
    │   │   ├── ArgonSnackbar.vue
    │   │   ├── ArgonSocialButton.vue
    │   │   ├── ArgonSwitch.vue
    │   │   └── ArgonTextarea.vue
    │   ├── examples
    │   │   ├── Cards
    │   │   ├── Charts
    │   │   ├── Navbars
    │   │   ├── PageLayout
    │   │   ├── Sidenav
    │   │   ├── Breadcrumbs.vue
    │   │   ├── Configurator.vue
    │   │   └── Footer.vue
    │   ├── router
    │   ├── store
    │   ├── views
    │   │   ├── components
    │   │   ├── Billing.vue
    │   │   ├── Dashboard.vue
    │   │   ├── Home.vue
    │   │   ├── Profile.vue
    │   │   ├── Rtl.vue
    │   │   ├── Signin.vue
    │   │   ├── Signup.vue
    │   │   ├── Tables.vue
    │   │   └── VirtualReality.vue
    │   ├── App.vue
    │   ├── argon-dashboard.js
    │   └── main.js
    ├── .browserslistrc
    ├── .eslintrc.js
    ├── .gitignore
    ├── babel.config.js
    ├── CHANGELOG.md
    ├── ISSUE_TEMPLATE.md
    ├── LICENSE
    ├── package.json
    └── README.md
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources

- [Live Preview](https://demos.creative-tim.com/vue-argon-dashboard/#/dashboard-default?ref=readme-vad)
- [Download Page](https://www.creative-tim.com/product/vue-argon-dashboard?ref=readme-vad)
- Documentation is [here](https://www.creative-tim.com/learning-lab/vue/overview/argon-dashboard/?ref=readme-vad)
- [License Agreement](https://www.creative-tim.com/license?ref=readme-vad)
- [Support](https://www.creative-tim.com/contact-us?ref=readme-vad)
- Issues: [Github Issues Page](https://github.com/creativetimofficial/vue-argon-dashboard/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Vue Argon Dashboard 2. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Vue Argon Dashboard 2. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/product/vue-argon-dashboard?ref=readme-vad).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us?ref=readme-vad) instead of opening an issue.

## Licensing

- Copyright 2022 [Creative Tim](https://www.creative-tim.com?ref=readme-vad)
- Creative Tim [license](https://www.creative-tim.com/license?ref=readme-vad)

## Useful Links

- [More products](https://www.creative-tim.com/templates?ref=readme-vad) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free?ref=readme-vad) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new?ref=readme-vad) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
