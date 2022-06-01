# DOB Production Release for Employment Landing Page
This is a package of all the assets needed for the redesign of the DOB Employment Landing page. 

## A few general details:
- CSS is loaded from a jsdelivr remote link. No need to add directly to the site. These are served behind a production CDN.
- Fontawesome is also loaded from a jsdelivr remote link. TTF font files are preloaded. Also behind a prod CDN.
- CSS should load and provide at least mostly functional IE11 support. Fonts may not work, icons may not load, and some layout properties may not function as intended. IE11 is officially being retired as of June 15, 2022 and has been an unstable, unsupported and unsafe browser to use for any reason since 2021 - the end of support for IE. NYSDS does not support IE functionality. Please upgrade your browser. Microsoft Edge has a "View in IE11" function if you require IE11 for some reason.

## For the employment.html file
1. For the section commented as 1. - please add all code to the <pre><head></pre> tag for the page template being used for this page only. This section includes opengraph meta tags for social media promotion as well as the remote css and font files.
2. For the section commented as 2. - please replace the <pre><div id="dobcontent_inner" role="main"></div> contents with everything in  <main class="nysds-normalize mx-8 md:mx-20" id="main-site-content-for-skiplink"></main></pre>  The search box is included here as well.

## Images
All images are in a folder **/images/nysds** and should be placed on the server to be reachable at https://budget.ny.gov/images/nysds/{{image here}}

## Problems?
Email [jeffrey.knaack@ogs.ny.gov]