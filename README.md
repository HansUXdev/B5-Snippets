# Bootstrap 5 for [open-vsx](https://open-vsx.org/)

The first and (currently only) bootstrap 5 snippet extension.
Published on the ONLY [open source registry](https://open-vsx.org/about) for VS Code extensions.

Learn more about open source versions of vscode such as [vscodium](https://vscodium.com/), [GitPod's IDE](https://www.gitpod.io/docs/ide/) and more.

## Notes & Roadmap
Bootstrap 5 is currently in alpha and this extension does not implement all the component yet (see the todo list below).

Unlike a lot of other snippets, this extension aims to balence user simplicity, with power and flexibility by keeping the **total number of snippets to a minimum**. 

In terms of **user simplicity**, other Bootstrap 4 snippets have 5 different snippets for the grid, whereas this will have 3, but each is more powerful.

## Roadmap
* Each snippet with eventually have a gif demo (soon).
* When Bootstrap gets out of alpha, I will create snippets for templates, such as `b5-$-marketing`, and possibly if [requested](https://github.com/HansUXdev/B5-Snippets/issues/1) or [sponsored](https://github.com/sponsors/HansUXdev/).

## Features

#### Templates/Layout

Trigger | Description
--- | ---
b5-**$** | Shortcut for bootstrap cdn css & js files
**!**b5-**$** | Shortcut creating an html document with cdn scripts included
**!**b5-**$**-layout-name | Common layouts (coming soon).
**!**b5-**$**-marketing | Shortcut creating a marketing template (soon).

#### Grid

Trigger | Description
--- | ---
b5-**container** | Grid container with options for -fluid, px, gy and more.
b5-**row** | Powerful row, `${1| ,row-cols-2,row-cols-3, auto,justify-content-md-center,md,lg,xl,xxl|}`. Default to row with optional utility classes. 
b5-**col** | Pretty much all your need covered and more. Ex: `col${1| ,-1,-2,-3,-4,-5,-6,-sm,-md,-lg,-xl,-xxl|}${2| ,-auto,-1,-2,-3,-4,-5,-6,-7,-8,-9,-10,-11,-12`

#### Navbar

Trigger | Description
--- | ---
b5-**navbar-default** | Navbar default
b5-**nav-item** | item with link and options for common pages such as Home, About, Blog, Contact.
b5-**navlink** | link
b5-**nav-dropdown** | dropdown
b5-**nav-dropdown toggle** | Navbar toggle
b5-**navbar-scollspy** | coming soon...



#### Button

Trigger | Description
--- | ---
b5-**btn** | Button with link
b5-**btn-o** | Button with outline
b5-**btn-group** | More buttons coming soon...

<!-- #### Bgroup
Trigger | Description
--- | ---
b5-**bgroup-default** | Bgroup default
b5-**bgroup-dropdown-vertical** | Bgroup dropdown vertical
b5-**bgroup-dropdown** | Bgroup dropdown
b4-**bgroup-size** | Bgroup size
b4-**bgroup-toolbar** | Bgroup toolbar -->

<!-- #### Dropdown

Trigger | Description
--- | ---
b4-**dropdown-alignment** | Dropdown alignment
b4-**dropdown-anchor** | Dropdown anchor
b4-**dropdown-button** | Dropdown button
b4-**dropdown-colored** | Dropdown colored
b4-**dropdown-default** | Dropdown default
b4-**dropdown-sized** | Dropdown sized
b4-**dropdown-split** | Dropdown split
b4-**dropdown-up-split** | Dropdown up split
b4-**dropdown-up** | Dropdown up -->

#### Card

Trigger | Description
--- | ---
b4-**card** | Card
b4-**card-align** | Card align
b4-**card-align** | more coming soon...

#### Carousel

Trigger | Description
--- | ---
b4-**carousel-caption** | Carousel caption
b4-**carousel-default** | Carousel default

#### Collapse

Trigger | Description
--- | ---
b5-btn-reveal | Reveals content on click
b5-**collapse-Multiple** | Collapses multiple targets (soon...)

#### Progress

Trigger | Description
--- | ---
b4-**progress** | progress bar



## Todo
- [ ] Breadcrumb
- [ ] Nav
- [ ] Alert
- [ ] Badge
- [ ] Button group
- [ ] Dropdown
- [ ] Form
- [ ] Media
- [ ] Responsive
- [ ] Figure
- [ ] List
- [ ] Tooltip
- [ ] Modal
- [ ] Pagination
- [ ] Popover
- [ ] Typography


<!-- ## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them. -->

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something -->

## Known Issues
No serious issue known at the moment.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...


# **Enjoy!**


## Supporting Developers 
If you use this a lot or want to see it improve consider giving it a star or  becoming a [githup sponsor](https://github.com/sponsors/HansUXdev/). 

I author does **a lot more** than just publishing a json file for snippets.

Here are just a few things he's working on, while taking care of his 👶 as a full-time single father, job hunting & competing in hackathons...

### Educational Repos
Trigger | Description & Info
--- | ---
[JavaScript-First](https://github.com/HansUXdev/JavaScript-First) | An Open Source Book that teaches anyone how to code with JavaScript using the node.js runtime environment rather than a browser and by the end, you will build a server and a website using JavaScript..
[Learn Mongo GitPod](https://github.com/HansUXdev/LearnMongoGitPod)| A repo designed to teach mongoDB to people with zero experiance and zero config, meaning you can learn on virtually any device that has a browser that GitPod can run on! This 🤞may🤞 become part of Free Code Camp [[1](https://forum.freecodecamp.org/t/how-is-new-content-created-at-fcc/416191/3)], [[2](https://github.com/freeCodeCamp/CurriculumExpansion/issues/103)].

### Future Snippets & Extensions
Name | Description
--- | ---
Code Slides | A snippet extension for creating educational slides with [vscode-reveal](https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal) and a custom theme. (not public yet)
Foundation 6 Snippets| This will start as a snippets for [sites](https://get.foundation/sites/docs/) and then be updated for [email](https://get.foundation/emails). If sponsored, I will extend this to eventually replace the [CLI](https://github.com/foundation/foundation-cli) and [building blocks](https://get.foundation/building-blocks/) by implementing a custom feature that writes install kits in a similar way the [web boilerplate](https://marketplace.visualstudio.com/items?itemName=jamesqquick.web-boilerplate) writes an html, css, and js file.  (not started yet)

### Social Entrepreneurship: Open Source Non-Profit
I'm in the process of founding a non-profit dedicated to promoting open source by doing the following and can only commit to the first two without proper sponsorship:
Name | Description
--- | ---
Creating open source curriculum | Getting open source curriculum into the hands for high school students.
CTE Coding Students | Bringing industry professionals into the class room to inspire them (via zoom). I already did this as a teacher by bringing people from Riot Games / Carvana, Choice Hotels, Auth0, and many others into my classroom. Now I want to streamline this for more schools.
Free Coding Classes on Twitch | I stream open source classes for an introductory javaScript class every week to test the open source curriculum I write. Think of it as a free bootcamp online. I also despritely need a better computer that doesn't require iced gel packs to be able to stream 😅.... 
Lobbying for Open Source Certification | When I taught in a public CTE high school, I couldn't believe that a multiple choice test like th MTA certifications were approved by the state over open source certifications such as Free Code Camp's. I know enough school board members and a few house members to help get the ball rolling but, it's a lot of leg work and I don't want to commit to this without funding...
Laptop | Donating 4G latops/tablets to students struggling with remote academic life. Having taught a few students with bad internet, etc, this is especially important to me but I don't have the resources to address this without funding.
