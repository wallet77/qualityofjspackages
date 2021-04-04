# Quality of JS packages

## Definition
This project is an open-source tool which aims to analyze Javascript packages.  

The main idea is to crawl the top most famous Javascript packages and to analyze each of them, in order to produce a global report.

## Composition
This project is composed of:

| Project             | Description                                 | Techno              |
|---------------------|---------------------------------------------|--------------------|
| [the packages crawler](https://github.com/wallet77/qualityofjspackages-crawler) | Produce a very detailed report per package | Node.js    |
| [data generator](https://github.com/wallet77/qualityofjspackages-data-generator) | Generate a small report with aonly aggregated data | Node.js    |
| [website](https://github.com/wallet77/qualityofjspackages-website) | Graphical representation of the report | Vue.js, apexcharts    |

## Overview

![Overview diagram](https://github.com/wallet77/qualityofjspackages/blob/main/schema/overview.png)
