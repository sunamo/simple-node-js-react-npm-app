# simple-node-js-react-npm-app

## Short description

Ukázková appka Node.js a React (create-react-app) z tutoriálu Jenkins User Documentation Build a Node.js and React app with npm. Obsahuje Jenkinsfile, skripty test.sh, deliver.sh a kill.sh pro fáze Test a Deliver a Taskfile.yml s tasky dev a rel. Slouží jako cvičný CI/CD příklad.

This repository is for the
[Build a Node.js and React app with npm](https://jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/)
tutorial in the [Jenkins User Documentation](https://jenkins.io/doc/).

The repository contains a simple Node.js and React application which generates
a web page with the content "Welcome to React" and is accompanied by a test to
check that the application renders satisfactorily.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `scripts` subdirectory
contains shell scripts with commands that are executed when Jenkins processes
the "Test" and "Deliver" stages of your Pipeline.
