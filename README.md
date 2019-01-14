# GhostBlogAzure
## Prerequisite
Create your own Azure Account.

## Your Ghost blog ready for Azure app service deployment. 
<a href="https://azuredeploy.net/" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
<p>
</p>

## Why GhostBlogAzure?
The current version of Ghost(2.10.0) is not compatible with Azure App Service. GhostBlogAzure is a production-ready template which can be hosted directly on Azure App Service. I will try to maintain the ghost version updated. All contributions are welcome.

## Usage
### 1. Fork or Clone this repository.
### 2. Branch out from the branch "master".
```bash
git checkout master
git checkout -b my_blog
```
### 3. Install npm modules.
```bash
npm install
```
### 4. Initialize your database.
```bash
node db.js
```
### 5 Run
```bash
npm start
```
### 5. Customize everything you want in your content folder.

