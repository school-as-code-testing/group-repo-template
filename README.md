<!-- BEGIN HEADER -->


# Group Repo Template

> - [Issues](https://github.com/school-as-code-testing/group-repo-template/issues): [`help-wanted`](https://github.com/school-as-code-testing/group-repo-template/issues?q=is%3Aopen+label%3Ahelp-wanted), [`question`](https://github.com/school-as-code-testing/group-repo-template/issues?q=is%3Aopen+label%3Aquestion)
> - [Discussions](https://github.com/school-as-code-testing/group-repo-template/discussions/)
> - [Deliverables](https://github.com/school-as-code-testing/group-repo-template/projects/1)
> <details>
> <summary>Tech Support</summary>
>
> [![Rubber Ducky](./assets/rubber-ducky.png)](https://rubberduckdebugging.com/)
>
>  </details>


<!-- END HEADER -->

A repository for group study

<!-- BEGIN TOC -->

- [Getting Started](#getting-started)
- [Class Calendar](#class-calendar)
- [Modules](#modules)
- [Learners](#learners)
- [Shared Notes](./shared-notes)
  - [Vocabulary](./vocabulary) (_[PRs](https://github.com/school-as-code-testing/group-repo-template/pulls?q=label%3Avocabulary)_)
  - [Snippets](./snippets) (_[PRs](https://github.com/school-as-code-testing/group-repo-template/pulls?q=label%3Asnippets)_)
  - [Chill Zone](./chill-zone)
- [Guidebook](./guidebook)

<!-- END TOC -->

---

## Getting Started

<!-- a guide to using this repository -->

<details>
<summary>expand/collapse</summary>
<br>

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

</details>

---

## Modules

<!-- BEGIN MODULES -->
  <ol start="1">

<li><h3><a href="https://github.com/hackyourfuturebelgium/precourse/tree/master/.study" style="display: inline">precourse</a></h3>  <ul><li><p>    0 chapters   | <a href="https://github.com/school-as-code-testing/group-repo-template/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aprecourse">deliverables</a>     | <a href="https://github.com/school-as-code-testing/group-repo-template/milestone/1">milestone</a>  </p></li></ul></li>
<li><h3><a href="https://github.com/hackyourfuturebelgium/workflows/tree/master/.study" style="display: inline">workflows</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/group-repo-template/projects/1?card_filter_query=label%3Adeliverable+milestone%3Aworkflows">deliverables</a>    | <a href="https://github.com/school-as-code-testing/group-repo-template/issues?q=milestone%3Aworkflows+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/group-repo-template/milestone/2">milestone</a> </p></li></ul></li>
<li><h3><a href="https://github.com/hackyourfuturebelgium/welcome-to-js/tree/master/.study" style="display: inline">welcome-to-js</a></h3>  <ul><li><p>    2 chapters   | <a href="https://github.com/school-as-code-testing/group-repo-template/projects/1?card_filter_query=label%3Adeliverable+milestone%3Awelcome-to-js">deliverables</a>    | <a href="https://github.com/school-as-code-testing/group-repo-template/issues?q=milestone%3Awelcome-to-js+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/group-repo-template/milestone/5">milestone</a> </p></li></ul></li>
<li><h3><a href="https://github.com/hackyourfuturebelgium/debugging" style="display: inline">debugging</a></h3>  <ul><li><p>    4 chapters   | <a href="https://github.com/school-as-code-testing/group-repo-template/projects/1?card_filter_query=label%3Adeliverable+milestone%3Adebugging">deliverables</a>    | <a href="https://github.com/school-as-code-testing/group-repo-template/issues?q=milestone%3Adebugging+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/group-repo-template/milestone/6">milestone</a>  </p></li></ul></li>
<li><h3><a href="https://github.com/hackyourfuturebelgium/behavior-strategy-implementation/tree/master/.study" style="display: inline">behavior-strategy-implementation</a></h3>  <ul><li><p>    3 chapters   | <a href="https://github.com/school-as-code-testing/group-repo-template/projects/1?card_filter_query=label%3Adeliverable+milestone%3Abehavior-strategy-implementation">deliverables</a>    | <a href="https://github.com/school-as-code-testing/group-repo-template/issues?q=milestone%3Abehavior-strategy-implementation+label%3Acheck-in">check-ins</a>     | <a href="https://github.com/school-as-code-testing/group-repo-template/milestone/7">milestone</a> </p></li></ul></li>
</ol><br>


[TOP](#group-repo-template)
<!-- END MODULES -->

---

## Learners

<!-- BEGIN LEARNERS -->
  <ul  style="list-style-type:none;">

</ul><br>


[TOP](#group-repo-template)
<!-- END LEARNERS -->
