### Hi there 👋

Here you'll find mostly packages for the R programming language I've been working on. Some of them have been created for the European Data Journalism Network - EDJNet, many others have been developed for a variety of more or less serious reasons.


They include:

- [`tidywikidatar`](https://github.com/EDJNet/tidywikidatar) - Interact with Wikidata and get tidy data frames in response (it's also on CRAN)
- [`ganttrify`](https://github.com/giocomai/ganttrify) - Create beautiful Gantt charts with ggplot2 (far from perfect, but apparently very popular)
- [`castarter`](https://github.com/giocomai/castarter) - castarter - Content analysis starter toolkit for R (it's the first "big" package I made for R... it shows my relative inexperience, but it still works nicely and colleagues and I use it quite regularly; it has plenty of functionalities, and even if it could use a more comprehensive vignette, it should still be usable by novice users)
- [`castarter2`](https://github.com/giocomai/castarter2) - castarter2 - Content analysis starter toolkit for R (still underdevelopment and not yet really functional... it should deal with many of the issue of the old castarter and allow for more flexibility, based on a more modern codebase)
- [`latlon2map`](https://github.com/giocomai/latlon2map) - Facilitates matching lat/lon data with administrative units and other geographic shapes (it also includes a lot of convenience functions for downloading and caching geo-spatial datasets... not a beauty, but it gets its job done and I use it in so many of my everyday projects)
- [`riskviewer`](https://github.com/EDJNet/riskviewer) - riskviewer - Show risks and probability in real world contexts (conceptually, this may be one of the most valuable things I've worked on. Check out the [theoretical background](https://edjnet.github.io/riskviewer/articles/introduction.html) - and give a quick spin to the shiny app [showcasing a basic functionality](https://riskviewer.europeandatajournalism.eu/) - unfortunately, the package does not yet work consistently but I hope to make it better)
- [`networkedwebsitesdetector`](https://github.com/giocomai/networkedwebsitesdetector) -  A structured approach for finding networked websites (I don't even know what to say... this is kind of great, but also I never had the time to really polish and finalise it, so...)
- [`genderedstreetnames`](https://github.com/giocomai/genderedstreetnames) - Automatically find the gender of street names, manually fix what the automatic part got wrong. (Kind of cool and with a nice vignette. Not in active development, as I am working a new [`streetnamer`](https://github.com/giocomai/streetnamer) with plenty more)
- [`shinyshoppinglist`](https://github.com/giocomai/shinyshoppinglist) - A shopping list app made in R shiny (this is really basic, but also, it actually works)

## API wrappers

- [`zoteror`](https://github.com/giocomai/zoteror) -  Access the Zotero API in R (it does what it says on the tin, reasonably functional with a clear README... I may put it on CRAN one day)
- [`plausibler`](https://github.com/giocomai/plausibler) - Access Plausible Analytics API from R 
- [`huecontroller`](https://github.com/giocomai/huecontroller) - Control Philips Hue lights using the R programming language (so... one night I was on my couch, and wanted to soften the lights, but didn't want to get up, so I ended up writing an R package to control lights... it even has a reasonably functional Shiny app, but it's only intensity and warmth for the time being - setting colour is possible, but not yet integrated in the shiny app)


## Datasets

- [`tifkremlinen`](https://github.com/giocomai/tifkremlinen) - A corpus with all items published on the website of the Kremlin (1999-2020) - (it even has a hex logo, and a [DOI](https://discuss-data.net/dataset/5eb1481e-ae89-45bf-9c88-03574910730a/), so it's surely serious stuff; to be honest, I do have big plans about expanding this one)
- [`olympics2020nuts`](https://github.com/EDJNet/olympics2020nuts`) - Retrieve details about Olympics 2020 medalists via Wikipedia and Wikidata (check out the readme for more details as well as [this nice map](https://edjnet.github.io/olympics2020nuts/medalists_map.html))
- [`european_routes`](https://github.com/EDJNet/european_routes) - Matching data from Eurostat's datasets on flights to hubs with coordinates and data on train routes, [see also step-by-step process](https://edjnet.github.io/european_routes/)
- [`lau_centres`](https://github.com/EDJNet/lau_centres) -  Population-weighted centres of local administrative units and consistent concordance with NUTS regions ([website with all details](https://edjnet.github.io/lau_centres/))


## Packages that kind of work, but not really
- [`rbackupr`](https://github.com/giocomai/rbackupr) - An R package to backup folders to Google Drive with limited permissions (it kind of works, but I don't really recommend it for broad use at this stage)
- [`gpx2pdf`](https://github.com/giocomai/gpx2pdf) - R package and shiny interface to create a pdf printout based on a gpx track (you know, with elevation charts and black and white maps? I made it for a very specific projects and started to transform into an R package but it still shows that it's half way through... perhaps still useful if somebody aims to achieve something like it)

## Contributions to tidyverse and other packages

I am happy to have contributed to some of the most used packages in the R ecosystems. These are small contributions, but I remain nonetheless proud to be featured in the "acknowledgment" section of the release notes of [`tidyr` (version 1.0)](https://www.tidyverse.org/blog/2019/09/tidyr-1-0-0/#thanks) and [`readr` (version 2.0)](https://www.tidyverse.org/blog/2021/07/readr-2-0-0/#acknowledgements). I have also contributed to other packages, such as [`workflowr`](https://github.com/workflowr/workflowr), 

## About me

More about me on my website, [giorgiocomai.eu](https://giorgiocomai.eu/)
