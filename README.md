[![npm version](https://img.shields.io/npm/v/@pachun/YOUR_PACKAGE_NAME.svg)](https://www.npmjs.com/package/@pachun/YOUR_PACKAGE_NAME)
[![cov](https://pachun.github.io/YOUR_PACKAGE_NAME/badges/coverage.svg)](https://github.com/pachun/YOUR_PACKAGE_NAME/actions)

# A template for creating npm packages for RN/Expo tools

1. Create a new GitHub repository named `your-package-name`
1. Set the NPM_TOKEN github secret in that GitHub repository
1. [Follow the steps here to set up the code coverage reporting badge](https://github.com/marketplace/actions/coverage-badge) in that GitHub repository
1. Clone this repository
1. `mv expo-react-native-npm-package-template your-package-name`
1. `cd your-package-name`
1. `rm -rf .git && git init .`
1. Edit package.json
1. Write tests in `tests/my-test.test.ts`
1. Export library code from `src/index.ts`
1. Edit README.md (replace `YOUR_PACKAGE_NAME`)
1. Add the remote you created above, as `origin`
1. `git push origin main`
