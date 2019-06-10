# Netlify CMS starter for Gridsome

## Install this starter

### Initialize App

1. `gridsome create my-gridsome-site https://github.com/davidleininger/gridsome-netlifycms-starter.git`
2. `cd my-gridsome-site` to open folder
3. Run `yarn` to install dependencies
3. `gridsome develop` to start local dev server at http://localhost:8080

### Update Config to use Netlify CMS

Update _src/admin/config.yml_ backend repo with `your_name/repo_name`

### Connect GitHub and Netlify

1. Create new site on Netlify and connect to GitHub Repo
2. Create new app on **GitHub** _Settings > Developer Settings > OAuth Apps_
3. Add `Client ID` and `Client Secret` to **Netlify** _General > Access Control > OAuth_
4. Navigate to netlify URL `/admin`

## Demo
[https://cms-gridsome-demo.netlify.com](https://cms-gridsome-demo.netlify.com)

Have Fun!
