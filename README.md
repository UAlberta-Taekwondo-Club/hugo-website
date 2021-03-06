# UAlberta Taekwondo Hugo Website

- **Hugo is no longer being used because it's too difficult to change the theme code**

- [https://ualberta-taekwondo-club.github.io/hugo-website/](https://ualberta-taekwondo-club.github.io/hugo-website/)

- Built on [Hugo](https://gohugo.io/)
- Using [Raditian hugo theme](https://themes.gohugo.io/themes/raditian-free-hugo-theme/)

## Initial setup

### [Install Hugo](https://gohugo.io/getting-started/installing/)

- `hugo.exe` for hugo v0.98.0 on windows 64-bit has already been installed in this Github repo

1. Go to https://github.com/gohugoio/hugo/releases
2. Scroll down to **Assets** and download the `.zip` file for your operating system
3. Extract the `hugo.exe` file

## Run website server locally

1. Open a terminal and type the following commands:
2. `cd` into the `/hugo-website` folder
   - For example, type `cd C:/Downloads/hugo-website`
3. Type `hugo server` or `./hugo server`
   - Note that the `hugo` here is the `hugo.exe` file that must be downloaded
4. Go to http://localhost:1313/

## Hugo commands

| Hugo command                | Description                |
| --------------------------- | -------------------------- |
| `hugo new site <site name>` | Creates a new hugo website |
| `hugo server`               | Run hugo website           |

## Links

- [Deploying website to Github Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [Configure Google Analytics](https://gohugo.io/templates/internal/#google-analytics)
