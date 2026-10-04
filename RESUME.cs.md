---
schema_version: 11
type: notmine-sample
category_override: none
file_count: 22
file_extensions: js:4, json:4, noext:4, sh:3, css:2, md:2, html:1, ico:1, svg:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 1034
total_lines: 300
metrics_lm: 2026-10-01 16:41:06
move_to_legacy_percent: 80
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

Ukázková aplikace Node.js a React pro tutoriál Jenkins "Build a Node.js and React app with npm". Obsahuje jednoduchou stránku "Welcome to React", test, `Jenkinsfile` a skripty `test.sh`, `deliver.sh` a `kill.sh` ve `jenkins/scripts`. Jde o oficiální ukázku bez vlastního vývoje.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [jenkins-docs/simple-node-js-react-npm-app](https://github.com/jenkins-docs/simple-node-js-react-npm-app)

- Zdroj určen podle: remote `sunamo/simple-node-js-react-npm-app` je podle GitHub API fork tohoto repa, README je původní z Jenkins dokumentace, hash `.gitattributes`, `.gitignore` a `public/favicon.ico` je shodný s originálem (`package.json` a `src/App.js` se liší, protože upstream mezitím vývoj změnil)..

Převzato z článku: [Build a Node.js and React app with npm (Jenkins)](https://www.jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/)

- Článek určen podle: README repa odkazuje na tento tutoriál Jenkins.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **80 %** — oficiální Jenkins ukázka, kterou lze znovu stáhnout z GitHubu

- Kopie jenkins-docs/simple-node-js-react-npm-app; poslední obsahová změna je z 2026-05-29.
- Stejný obsah je i v repu Jenkins_Projects\simple-node-js-react-npm-app.
- Vlastní kód téměř žádný.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
