# Plan checklist
- [ ] Finish plan
- [ ] List all features
 - Description
 - Dependencies
 - Order
- Front-end
 - [ ] Sitemap
 - [ ] Front-end framework
  - Bootstrap
  - Bootstrap 4 aplha http://blog.getbootstrap.com/2015/08/19/bootstrap-4-alpha/
  - Foundation
  - Others
 - [ ] Dependency manager
  - Bower
  - DuoJS http://duojs.org/
   - for JS and CSS, no config file, just require or @import a github repo
  - Some back-end dependency manager that has all the packages we need
- Back-end
 - [x] Nette, PHP
 - [ ] File structure (depends on framework)
 - [ ] Dependency manager
  - Composer
   - would make sense as it's meant for PHP and we need ot for Nette
  - NPM
   - could be used as front-end as well as back-end
- Deployment
 - Gulp
 - [ ] List necessary tasks (minification, concatenation, ...)
 - GOAL: use one command that does all or uses other tools (e.g. npm install (installs npm and composer dependencies), npm test launches nette tester)
 - Use travis for building (build matrix, ensure compatibility with different setups (DBs, PHP versions, ...)
 - (maybe) Use own CI
  - [ ] list reasons
 - Choose tools to monitor things we don't want to check (Code quality, test coverage, commit revisions, etc.)
  - [ ] List
- Development
 - [x] Git Flow https://guides.github.com/introduction/flow/
 - [x] Semantic Versioning http://semver.org/
 - Github features https://guides.github.com/
  - Issues
  - Wiki
  - PRs
