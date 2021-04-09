# Quality of JS packages

## Definition
This project is an open-source tool which aims to analyze Javascript packages.  

The main idea is to crawl the top most famous Javascript packages and to analyze each of them, in order to produce a global report.  

Here you can access to the online report: [https://www.qualityofjspackages.com/](https://www.qualityofjspackages.com/)

## Composition
This project is composed of:

| Project             | Description                                 | Techno             |
|---------------------|---------------------------------------------|--------------------|
| [the packages crawler](https://github.com/wallet77/qualityofjspackages-crawler) | Produce a very detailed report per package | Node.js    |
| [data generator](https://github.com/wallet77/qualityofjspackages-data-generator) | Generate a small report with aonly aggregated data | Node.js    |
| [website](https://github.com/wallet77/qualityofjspackages-website) | Graphical representation of the report | Vue.js, apexcharts    |

## Overview

![Overview diagram](https://github.com/wallet77/qualityofjspackages/blob/main/schema/overview.png)

## Motivation
1. Evaluate the state of JS packages quality  
In order to improve something, we must monitor it.
To build a better ecosystem we should detect quality issues and work on areas of improvement.

2. Improve webperf and reduce the environmental impact of the web  
By reducing packages size, load time, and complexity we can improve performance. But not only!
At the same time, we can reduce our impact on the environment by reducing electrical consumption, bandwidth, etc.

3. Quality ≠ quantity  
A lot of tools that aim to evaluate package quality actually focus on quantitative metrics like:
- number of downloads
- number of GitHub stars
- number of contributors
- number of open/closed issues
- etc.

Quality has nothing to do with quantity!

4. Choose the right package  
Javascript ecosystem has become more and more complex and bigger over time. A lot of packages are available on NPM registry and some of them achieve the same goal.
In order to find the best package, we must evaluate them in terms of quality.

## Inspiration

A few years ago [HTTP archive](https://httparchive.org/) was created to crawl the top sites on the web.  
They record a lot of information in order to analyze this data to identify trends of the web.  
This work is useful to anticipate issues we will face in the near future or to change our way of thinking about the web.  

In addition, if something is not analyzed and monitored then it's not visible, and as long as it's hidden we have no power to act on it. This is the main principle behind observability.

This idea of qualityofJSpackages is based on the same concept but only for the smallest pieces of the web. As everything is built with Javascript, it's relevant to analyze the top Javascript packages in order to detect quality issues and trends.

Many thanks to people who work on webperf, or software quality in general, and who have inspired me a lot:
- Tammy Everts
- Steve Souders
- Addy Osmani
- Ilya Grigorik
- and many others

## Contributing

As with every open-source project, it needs your help to grow and improve ;)  
You can help by many ways:

**Crawler**
- if you know Node.JS and Node.js packages ecosystem
- if you have any idea about metrics we can collect

**Website**
- if you know VueJS or apexcharts and want to improve the report visualization
- if you want to work on the UI/UX
- if you want to work on translations

**Mobile**
- if you want to create an app
- if you want to work on the responsive design