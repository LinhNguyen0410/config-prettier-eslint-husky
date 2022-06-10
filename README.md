# Package Installed

        prettier

        eslint

        babel-eslint

        eslint-config-react-app

        eslint-config-prettier

        eslint-plugin-prettier


> https://prettier.io/playground/

# Husky setup
        yarn add husky --dev

        yarn husky install

        yarn add lint-staged

**Add pre-commit to husky** : yarn husky add .husky/pre-commit "your commit".

**Add script for package.json** : 

        "lint-staged": {
            "*.ts,tsx": "eslint --fix ",
            "*.{ts,tsx,css,md,html,json}": "prettier --cache --write"
        }