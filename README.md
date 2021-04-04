# Quality of JS packages

## Definition
This project is an open-source tool which aims to analyze Javascript packages.  

The main idea is to crawl the top most famous Javascript packages and to analyze each of them, in order to produce a global report.

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