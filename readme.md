> -   [English](#english)
> -   [فارسی](#فارسی)

English
=======

This repository is a
    [git-scrape](https://simonwillison.net/2020/Oct/9/git-scraping/) of the courses offered by Sharif University of Technology, started from the fall semester of 2020 (1399 in Jalali). The data includes each department's available courses, and details about these courses (the maximum capacity of the course, the professor, the prerequisites, the number of registered students, ...).

The code that scrapes and generates this data is available [here](https://github.com/NightMachinary/.shells/blob/master/scripts/zshlang/auto-load/others/scraping/sharif.zsh).

The latest version of the course lists can be viewed [here](https://nightmachinary.github.io/sharif_course_list/).

## Basic usage example

- Install [Refined Github](https://github.com/sindresorhus/refined-github#install).
- (Optional step; Skip if you just want to see the latest data.)
  - Select the date at which you want to view the data from [the commit list](https://github.com/NightMachinary/sharif_course_list/commits/master).
  - Click on `Browse files`.
- Go to the file corresponding to the department you want to check, e.g., [علوم ریاضی](https://github.com/NightMachinary/sharif_course_list/blob/master/%D8%B9%D9%84%D9%88%D9%85%20%D8%B1%DB%8C%D8%A7%D8%B6%DB%8C.html).
- You can click on the `preview` button to preview the HTML file and see the course list at that date.
- You can, of course, use your own git-fu to do fancy analyses with the versioned data. The above is just the simplest possible use case.

<div dir="rtl">

فارسی
=====

این ریپو لیست درس‌های ارائه‌شده توسط دانشگاه شریف را با استفاده از تکنیک [git-scrape](https://simonwillison.net/2020/Oct/9/git-scraping/) نگه می‌دارد (شروع از ترم پاییز ۱۳۹۹). برای دیدن لیست دروس در تاریخ‌های مختلف، به کامیت تاریخ مورد نظر بروید.
