---
title: Upload a Theme
sub: Uploading a theme is as easy as 1, 2, 3...uhh and maybe more.
description: Want to submit your theme to our Showcase? Follow these instructions slow & carefully to get your theme featured for free!
status: none
---
# Submit your work
Want to submit your theme to our [Showcase](https://betterdocs.us/themes/)? Follow these instructions slow & carefully.

### Steps
I promise it doesn't take long :)

1. [Create a new file](https://github.com/MrRobotjs/BetterDocs-React/new/master/src/themes)
2. Name has to **match** your theme name. 
    > Make sure it's a markdown file ".md" and that it's [Kebab Case style](http://wiki.c2.com/?KebabCase). `[REQUIRED]`
3. Follow the following format for the file
```md
---
  title: {Theme Name}
  author: {Author Name}
  description: A SHORT Description
  download: https://github.com/
  github: https://github.com/{Author Name}/
  support:
  discord_server: https://discord.gg/INVITE
  demo: https://raw.githack.com
  thumbnail:
  images:
    - name: {Theme Name} Preview
      image: https://imgur.com/upload # Direct image link should only be used here. Imgur isn't required but if it isn't used then further inspection will happen
    - name: {Theme Name} Preview - {Image Name}
      image: https://imgur.com/upload # Direct image link should only be used here. Imgur isn't required but if it isn't used then further inspection will happen
  status:
  auto:
  featured: 
  style: dark
  tags: []
  ghcommentid: # DON'T CHANGE
  layout: product # DON'T CHANGE
---
  # A full description of your theme. All Markdown is allowed.
```
  4. Submit. You're done!

## Helpful information
Here's is some helpful information to inform you what each field does.
  - **title** - The name of your theme. `[REQUIRED]`
  - **author** - The name of the author of the theme. `[REQUIRED]`
  - **description** - Short paragraph describing the content and/or purpose of the theme that will appear in the permalink of your page and other places on the site. `[REQUIRED]`
  - **download** - The direct link to the file to be downloaded. `[REQUIRED]`
  - **github** - The link to your [Github](https://github.com/) profile. This will link your name right under the title of your theme. `[OPTIONAL]`
  - **support** - A link to allow people to get support. (In most cases it should be the [Github issue](https://guides.github.com/features/issues/) url) `[OPTIONAL]`
  - **discord_server** - A Discord server invite to allow people to get support or give feedback for the theme. `[OPTIONAL]`
  - **demo** - This is a direct url to the file so the [demo](https://betterdocs.us/demo/dark.html?theme=INSERT-URL-HERE) can work. For Github it need's to be the **raw** url but to fix the MIME type issue you will need to use [githack](https://raw.githack.com) for the url instead (or https://www.jsdelivr.com/?docs=gh). `[OPTIONAL]`
  - **thumbnail** - A direct link to an image that will be the thumbnail and shown on the [themes page](https://betterdocs.us/themes/). (16:9) `[REQUIRED]`
  - **images** - A list of images that show a preview of your theme. [Imgur](https://imgur.com) is highly recommended for compressed images and reliability. `[OPTIONAL]`
  - **status** - Values: `Updated/Oudated`. The current status of your theme.
  - **featured** - Values `True/False`. Remove entirely or leave as false. Only used for featured themes that are chosen.
  - **auto** - If your theme is hosted on [Github](https://github.com) then add `true` to allow users to automatically down the file (or even the entire repo) instead of just' visiting the site, if hosted elsewhere leave blank or remove it entirely. `[REQUIRED]`
  - **style** - Values: `dark/light`. This specifies the setting for the [demo](https://betterdocs.us). `[REQUIRED (if using demo)]`
  - **tags** - Tags are in an array and can be seperated with commas "," like so `[tag1,tag2]`. `[OPTIONAL]`
  - **ghcommentid** - ~~The ID of the issue related to your theme so it can be used in our comments system~~. `[REQUIRED]` 
  - **layout** - Used by the [Jekyll](https://github.com//MrRobotjs/BetterDocs/) version of this website. `[REQUIRED]` 

### How to set as Featured
*Note: the BetterDocs team will choose featured themes, leave as `featured: false` when first posting or remove entirely instead.*

  1. If your theme is chosen as featured, here’s what to do next:

  2. Change `featured: false` to `featured: true` or if it doesn't exist yet then add it.

## Changed your mind / need to edit your submission?
If you want to edit anything in your submission later, simply edit the `.md` file by submitting another PR.

## Old website
The old website will always be up on [Github Pages](https://betterdocs.netlify.com/)