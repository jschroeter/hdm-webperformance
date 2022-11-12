# hdm-webperformance exercise

This repository contains a static web page with some typical performance issues. A exercise for students of my lecture [Rich Media Systems at Stuttgart Media University](https://www.hdm-stuttgart.de/studierende/stundenplan/vorlesungsverzeichnis/vorlesung_detail?vorlid=5213920) is to find these issues and improve the loading experience for the users.

## Setup
1. open https://vscode.dev/github/jschroeter/hdm-webperformance; you should see Visual Studio Code with all the files
2. when you commit your changes for the first time you'll get asked if you want to create a fork. Select yes.
3. Open your new repository in GitHub and enable GitHub Pages in the repository settings, see https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site. Select the `main` branch and root folder.

After a few seconds you should be able to access the page via
`https://<your-username>.github.io/hdm-webperformance/`

Whenever you commit & push something to the main branch, the page will be published again. It might take a few seconds.

## Excercise
- open the page with a slow internet connection (e.g. network throtteling of browser dev tools) and observe how the page loads and renders
- run and check web performance analysis with tools like https://web.dev/measure/, https://WebPageTest.org and [Lighthouse](https://developers.google.com/web/tools/lighthouse/)
- implement improvements

lol