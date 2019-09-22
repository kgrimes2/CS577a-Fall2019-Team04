# Introduction

This is the code for [the team #4 website for CS577 F19](https://greenbay.usc.edu/csci577/fall2019/projects/team04/).

This project is built by CircleCI, and any commit to the `master` branch will trigger deployment to the production site. Please use caution when merging with `master`!

## Status

[![CircleCI](https://circleci.com/gh/kgrimes2/CS577a-Fall2019-Team04.svg?style=svg&circle-token=019ff32b06be7d283305ce250914427ad56212bf)](https://circleci.com/gh/kgrimes2/CS577a-Fall2019-Team04)
[![npm version](https://img.shields.io/npm/v/startbootstrap-simple-sidebar.svg)](https://www.npmjs.com/package/startbootstrap-simple-sidebar)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-simple-sidebar/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-simple-sidebar)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-simple-sidebar/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-simple-sidebar?type=dev)

## Contents

```
.
├── .circleci [1]
├── .git [2]
├── .gitignore [3]
├── CMN
├── Development
├── Exploration
├── FD
├── Foundations
├── PR
├── README.md
├── Valuation
├── css [4]
├── images [5]
├── index.html
├── node_modules [6]
├── package-lock.json [7]
├── package.json [7]
└── vendor [6]
```

[1] CI/CD files for easy deployment to USC server

[2] Version control files

[3] Files to be excluded by Git

[4] Stylesheets for the website to look nice

[5] Various images for the website, including team member headshots

[6] JavaScript dependencies to make building the site easier

[7] Determines which dependencies to include in project

## Building

1. Get the code:

```bash
$ git clone git@github.com:kgrimes2/CS577a-Fall2019-Team04.git
$ cd CS577a-Fall2019-Team04
```

2. Build

```bash
$ npm install
```

3. Test

```bash
$ npm test
```

## Contributing

1. Fork the code
2. Create a feature branch
3. Make your changes
4. Open a pull request
