---
date: "2021-10-29T00:00:00Z"
external_link: ""
image:
  caption: Twitter page of the covidbrasilbot
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/covidbrasilbot
# slides: example
summary: A Twitter bot that reports the number of confirmed cases and deaths by COVID-19 in Brazil using rtweet and Github Actions.
tags:
- COVID-19
- Twitter
- Bot
- R
title: covibrasilbot: a Twitter bot
url_code: "https://github.com/ramongss/covidbrasilbot/"
url_pdf: ""
url_slides: ""
url_video: ""
links:
- name: Twitter
  url: https://twitter.com/covidbrasilbot
---
The Twitter bot [@covidbrasilbot](https://www.twitter.com/covidbrasilbot) posts daily reports about the number of confirmed cases and deaths caused by COVID-19 in Brazil using [{rtweet}](https://docs.ropensci.org/rtweet/) and [GitHub Actions](https://docs.github.com/en/actions).

In the [Github Repo](https://github.com/ramongss/covidbrasilbot/) contains a [GitHub Action](https://github.com/features/actions) that runs on schedule (every day at 00:30 UTC). It executes the R code that retrieves the COVID-19 data from [@brasil_io](https://twitter.com/brasil_io), summarizes the information, generates the graphs with the confirmed cases and deaths info, and creates a "micro-report" to be posted. The report and the graphs are posted to [@covidbrasilbot](https://www.twitter.com/covidbrasilbot) on Twitter using [{rtweet}](https://docs.ropensci.org/rtweet/) package.

The [@covidbrasilbot](https://www.twitter.com/covidbrasilbot) was inspired by my other [COVID-19 AutoReport Project](https://ramongss.github.io/project/covid19-autoreport/) and the [@londonmapbot](https://twitter.com/londonmapbot) created by [@mattdray](https://twitter.com/mattdray).
