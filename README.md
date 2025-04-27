# UpDowntime

Uptime for downtime.


**Table of Contents**

* [Project Overview](#project-overview)
* [changelog](#changelog)

## Project Overview

At work, we chart on the different patient hospital transfer cases that we handle from day to day in a patient charting application that exists as a web app.

However on occasion, this application goes down for one reason or another, but we still need to continue to handle the current cases we have as well as still handle new transfer requests even when we're in downtime.

Our company does set up all up with Google Workspace Enterprise accounts.





## changelog

1. create project directory "UpDowntime" and initialize an empty `git` repository inside of that directory (project root)

```zsh
mkdir UpDowntime;
cd UpDowntime && git init;
```

2. install google's apps-script CLI tool `clasp` as well as Google Apps Script types

```zsh
npm init
npm install --save-dev google/clasp
npm install --save-dev @types/google-apps-script
```