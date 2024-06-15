# npm Documentation

[![Publish](https://github.com/npm/documentation/actions/workflows/publish.yml/badge.svg)](https://github.com/npm/documentation/actions/workflows/publish.yml)

This is the documentation for [https://docs.npmjs.com/](https://docs.npmjs.com/).

[This repository](https://github.com/npm/documentation) contains the content for our documentation site, and the GitHub Actions workflows that generate the site itself.

## Quick start

1. `npm install` to download gatsby, our theme, and the dependencies
2. `npm run develop`: starts the test server at `http://localhost:8000`.
3. Update the content - it's Mdx, which is like markdown - in the `content` directory.
4. Review your content at `http://localhost:8000`. (Gatsby watches the filesystem and will reload your content changes immediately.)
5. Once you're happy, commit it and open a pull request at https://github.com/npm/documentation.
6. A CI workflow run will publish your PR to a GitHub Preview Page.
7. Once the content is reviewed, merge the pull request. That will [deploy the site](https://github.com/npm/documentation/actions/workflows/publish.yml).

Do you want to know more? Check out our [contributing guide](CONTRIBUTING.md).

## License

The npm product documentation in the content, and static folders are licensed under a [CC-BY 4.0 license](LICENSE).

All other code in this repository is licensed under a [MIT license](LICENSE-CODE).

When using the GitHub logos, be sure to follow the [GitHub logo guidelines](https://github.com/logos).


## How To Work With Git

1. git checkout main
2. git pull
3. git checkout -b bug-00-branch-name
4. git add . 
5. git commit
6. git checkout main
7. git pull
8. git checkout bug-00-branch-name
9. git merge main
10. git checkout main
11. git merge bug-00-branch-name
12. git pull
13. git push
14. git branch -d bug-00-branch-name

