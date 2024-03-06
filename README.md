[![Netlify Status](https://api.netlify.com/api/v1/badges/19d379cc-d0f4-4765-9d26-95cc94e3efcc/deploy-status)](https://app.netlify.com/sites/ohstudioclone/deploys)
# OH.Studio Clone
A [clone](ohstudioclone.netlify.app) of the the [oh.studio](https://oh.studio/) website by Oli Harris

## Why?
To practice my frontend skills using a bottom-up approach by first adding the basic styles, then designing sub-components, block-level components then finishing with the whole page

## Content
The following clone includes 4 different pages:
1. home at index.html
2. profile at profile.html
3. contact at contact.html
4. others (non-valid) at 404.html

## New Learnings
### netlify _redirects
I learned to work with the `_redirects` file in netlify to give a better look to the links. No more `.html`! So the `index.html` or `profile.html` redirects to `/` or `/profile` respectively. 

![image](https://github.com/yilverdeja/oh-studio-clone/assets/29952939/4eba364e-817e-4b18-8e42-47d1f6839e6a)

In addition, I also added a `404.html`. When any page that does not exist tries to get access, a `404` error is thrown, and the `404.html` page is displayed while keeping the path intact to the incorrect url entered. So trying to go to `/profil` will keep the path the same, but the `404.html` page will appear.

![image](https://github.com/yilverdeja/oh-studio-clone/assets/29952939/6bc7b590-61c6-475f-849d-b19d646383ea)


## Todo
In order to finish the complete clone, these are the following things that are missing on this site:
* the `/projects/:project` pages
* optimized images using webp
* urls to the correct link items, and links to the correct images
* remove inline styling! (sorry, slipped 🍌 in the end and my styling process began to falter)
