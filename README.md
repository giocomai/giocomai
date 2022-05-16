### Hi there 👋

Here you'll find mostly packages for the R programming language I've been working on. Some of them have been created for the European Data Journalism Network - EDJNet, many others have been developed for a variety of more or less serious reasons.


They include:

- [`tidywikidatar`](https://github.com/EDJNet/tidywikidatar) - Interact with Wikidata and get tidy data frames in response (it's also on CRAN)
- [`ganttrify`](https://github.com/giocomai/ganttrify) - Create beautiful Gantt charts with ggplot2 (far from perfect, but apparently very popular, with hundreds of Github users kind enough to give it a star)
- [`castarter`](https://github.com/giocomai/castarter) - castarter - Content analysis starter toolkit for R (it's the first "big" package I made for R... it shows my inexperience when I wrote most of the codebase back in 2015, but it still works nicely and colleagues and I use it quite regularly; it has plenty of functionalities, and even if it could use a more comprehensive vignette, it should still be usable by novice users)
- [`castarter2`](https://github.com/giocomai/castarter2) - castarter2 - Content analysis starter toolkit for R (still underdevelopment and not yet really functional... it should deal with many of the issues of the old castarter and allow for more flexibility, based on a more modern codebase)
- [`latlon2map`](https://github.com/giocomai/latlon2map) - Facilitates matching lat/lon data with administrative units and other geographic shapes (it also includes a lot of convenience functions for downloading and caching geo-spatial datasets... not a beauty, but it gets its job done and I use it in so many of my everyday projects)
- [`rbackupr`](https://github.com/giocomai/rbackupr) - An R package to backup to Google Drive with limited permissions, useful e.g. for uploads from remote servers; speedy, thanks to local caching of metadata (not fully documented, but reasonably functional)
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
- [When Europeans go the cinema, what do they watch?](https://datavis.europeandatajournalism.eu/obct/giocomai/2018-04-EuropeanCinema/) - An interactive exploration of cinema-goers' habits in Europe based on twenty years of data (1996-2016) on 40 996 films (just visuals, no dataset).


## Packages that kind of work, but not really
- [`gpx2pdf`](https://github.com/giocomai/gpx2pdf) - R package and shiny interface to create a pdf printout based on a gpx track (you know, with elevation charts and black and white maps? I made it for a very specific projects and started to transform into an R package but it still shows that it's half way through... perhaps still useful if somebody aims to achieve something like it)

## Contributions to tidyverse and other packages

I am happy to have contributed to some of the most used R packages. These are small contributions, but I remain nonetheless proud to be featured in the "acknowledgments" section of the release notes of [`tidyr` (version 1.0)](https://www.tidyverse.org/blog/2019/09/tidyr-1-0-0/#thanks) and [`readr` (version 2.0)](https://www.tidyverse.org/blog/2021/07/readr-2-0-0/#acknowledgements). I have also contributed to other packages, such as [`workflowr`](https://github.com/workflowr/workflowr) and [`rtweet`](https://github.com/ropensci/rtweet/pull/378).

## Some blog posts

- [Animating ‘One Degree Warmer’ time series with ggplot2 and gganimate](https://medium.com/european-data-journalism-network/animating-one-degree-warmer-time-series-with-ggplot2-and-gganimate-7460862fcd7e) (9 November 2018)
- [European Elections 2019 and Italy's varying size](https://medium.com/european-data-journalism-network/european-elections-2019-and-italys-varying-size-fb4ed07d4ff6) - (11 June 2019)
- [How to feel lucky on a Monday morning: calculating the travel distance between places and each point of the European population grid](https://medium.com/european-data-journalism-network/how-to-feel-lucky-on-a-monday-morning-b73f4235320d) (27 November 2019)
- [How to find the population-weighted centre of local administrative units](https://medium.com/european-data-journalism-network/how-to-find-the-population-weighted-centre-of-local-administrative-units-a0d198fc91f7)” (27 March 2020)
- [Beautiful Gantt charts with ggplot2](https://medium.com/european-data-journalism-network/beautiful-gantt-charts-with-ggplot2-80ccd8c2c788) - 4 June 2020
- [Google Earth Studio as a data visualisation tool (with R)](https://medium.com/european-data-journalism-network/google-earth-studio-as-a-data-visualisation-tool-with-r-9501ddd6869)” (8 October 2020)
- [A new R package for exploring the wealth of information stored by Wikidata: tidywikidatar](https://medium.com/european-data-journalism-network/a-new-r-package-for-exploring-the-wealth-of-information-stored-by-wikidata-fe85e82b6440) (23 April 2021)
- [Visualising risk: a modern implementation of the Risk Characterisation Theatre](https://medium.com/european-data-journalism-network/visualising-risk-a-modern-implementation-of-the-risk-characterization-theatre-2ea860fe08e7)” (29 April 2021)
- [Finding gendered street names. A step-by-step walkthrough with R](https://medium.com/european-data-journalism-network/finding-gendered-street-names-a-step-by-step-walkthrough-with-r-7608c2d36a77) (16 July 2021)
- [The data you need to win the Olympics if you go NUTS](https://medium.com/european-data-journalism-network/the-data-you-need-to-win-the-olympics-if-you-go-nuts-6d03b9df34e6) (3 August 2021)


## About me

More about me on my website, [giorgiocomai.eu](https://giorgiocomai.eu/)
