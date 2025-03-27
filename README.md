# Mushu clip website

Static website showing a clip of a funny moment in a Twitch stream.

This is a repository with a single HTML file that is used to deploy a static website using [Azure Static Web Apps](https://learn.microsoft.com/en-us/azure/static-web-apps/).

> Azure Static Web Apps publishes a website to a production environment by building apps from an Azure DevOps or GitHub repository.

This repository serves as the source of the website.

## General description

The website source is located in the `/src` directory. It consists of plain HTML and CSS. No framework is used for this project. The only other file under the source directory is a [JSON configuration file for Azure Static Web Apps](https://learn.microsoft.com/en-us/azure/static-web-apps/configuration), used in this project for [showing a custom 404 page](https://learn.microsoft.com/en-us/azure/static-web-apps/configuration).

The website is deployed via an Action that was configured when [creating the Static Web App resource](https://learn.microsoft.com/en-us/azure/static-web-apps/get-started-portal?tabs=vanilla-javascript&pivots=github) in Azure.
