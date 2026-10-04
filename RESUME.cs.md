---
schema_version: 10
type: notmine_sample
file_count: 23
avg_lines_per_file: 974
total_lines: 300
metrics_lm: 2026-10-01 16:41:08
move_to_legacy_percent: 85
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: https://github.com/jenkins-docs/simple-node-js-react-npm-app
origin_status: found
origin_checked: 2026-10-01
article_source_url: https://www.jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/
article_status: found
article_checked: 2026-10-03
last_build_ok: yes
last_build_date: 2026-10-02
last_tests_run_date: not run
covered_lines: 0
---

## Description

Ukázková appka Node.js a React (create-react-app) z tutoriálu Jenkins User Documentation Build a Node.js and React app with npm. Obsahuje Jenkinsfile, skripty test.sh, deliver.sh a kill.sh pro fáze Test a Deliver a Taskfile.yml s tasky dev a rel. Slouží jako cvičný CI/CD příklad.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [jenkins-docs/simple-node-js-react-npm-app](https://github.com/jenkins-docs/simple-node-js-react-npm-app)

- Zdroj určen podle: původní README z Jenkins dokumentace; hash shoda package.json, public/manifest.json, src/App.js a src/index.js s dřívějším commitem 5579f39 upstreamu (HEAD je mezitím přepsaný na Vite) a favicon.ico s HEAD; složka JavaScript_Projects má stejný projekt jako fork

Převzato z článku: [Build a Node.js and React app with npm (Jenkins docs)](https://www.jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/)

- Článek určen podle: README uvadi tento tutorial, stranka overena.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **85 %** — oficiální Jenkins ukázka, duplicita stejnojmenného repa v JavaScript_Projects

- Kopie jenkins-docs/simple-node-js-react-npm-app, k tomu jen Taskfile.yml (poslední změna 2026-07-04).
- Stejný zdroj je i v JavaScript_Projects\simple-node-js-react-npm-app.
- Nic vlastního zde není.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
