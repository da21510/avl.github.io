---
layout: default
title: 網頁軟體工程師考試
description: Web Developer Exam
---

## 考試指示
> **注意:**
> 為節省時間，我們強烈建議您在**考試前**先設置一個空白的網頁 (列： Django, Rails, Node.js) 

1. 你有**2.5小時**盡量完成網頁功能。
1. 考試時間開始時，我們會 email 你需要開發的功能。
1. 選幾個羨慕：
	1. 請自由選擇你想要開發的功能，最能表現你的能力，沒有先後次序。

1. 讓您選擇您最熟悉的語言和架構。
	1. 選擇你最熟悉的程式語言和架構。
	1. 我們主要架構用 **JS, Express, Node, and React Redux**
	1. RWD 加分。
1. 我們想看的是一個前後端可以使用的網站，功能可以去後端完整測試使用最好。
1. 我們鼓勵你重複使用現有的架構像是 Redux、Bootstrap，不需要從零開始。
1. 請上架並提供 URL：
	1. 自備伺服器
	1. 或是 Cloud server, 比如 AWS, Heroku.

## 考試結果如何被評估
* 考試目的是準確的用實際面測量實力，題目跟工作上的應用類似。
* 你的考試成就會決定你的職位與薪資。
	* 越多可完整使用的功能，分數越高。

### 我們重視：
1. **數度.** 多快速能架構好有各功能的網頁？
1. **品質.** 其他工程師很容易瞭解並維修你寫的代碼？

### 我們會看：
1. 你的 web app live demo URL。
	1. 網頁是否可以使用，功能規格是依照指示。
	1. 我們希望考試不要有bug，實際做出來的羨慕少一點品質好一點。
1. 你在GitHub，GitLab上傳的代碼。（以後申請工作可以用）

<br>

---

## For Positions
1. [Full Stack Developer]({{ site.baseurl }}/recruit/jd_fullstackdev.html)
1. [Front-End Developer]({{ site.baseurl }}/recruit/jd_frontenddev.html)
1. [Back-End Developer]({{ site.baseurl }}/recruit/jd_backenddev.html)

## Exam Instructions
> **IMPORTANT:**
> We HIGHLY recommend you setup a live web server with a blank static web page (e.g. Django, Rails, Node.js) **BEFORE** your exam. It will save you a lot of time during the exam. (e.g. Django, Rails, Node.js) 

1. You will have **2.5 hours**.
1. You will be given a list of web app features at the start of the exam via email.
1. **Pick a few features.**
	1. Choose a few features to implement:

1. **Any framework.** You choose the programming language and framework.
	1. Choose language and framework you are the most familiar and proficient in.
	1. However, we primarily use **JS, Express, Node, and React Redux**
	1. **Modern RWD.** Bonus points for fully responsive web / mobile design.
1. **Quality over quantity.** We value working prototypes, so make sure your site is live and running before you move onto additional features.
1. **Reuse and leverage.** We highly encourage you to reuse other people's work, like Bootstrap and Redux. Don't reinvent the wheel.
1. **Self or cloud host.** We will ask you to spin up and host your app for 1 week.
	1. Your own self hosted server.
	1. Cloud server, e.g. AWS, Heroku. 

## How You Will Be Evaluated
* Our exam is designed to be an accurate reflection of the type of work you will be doing at our fast growing, lean startup.
* Your Engineer Level (E0-10) and therefore salary package will be decided by the completeness of your web app and the quality of your work.
	* The more functional features you are able to complete on our checklist, the higher your engineering/salary level.

### We value:
1. **Speed.** How quickly can you build a working app with a list of features?
1. **Code Quality.** How easy is it for other engineers to maintain your app?

### We will look at:
1. Your live web app with features as described by the exam, hosted on your own computer. 你的 web app live demo URL。
	1. **Functional and working.** We value functional, working prototypes, so make sure your site is live and running before you move onto additional features. Before your exam date to save time, we recommend setting a blank single page site on your development machine accessible on the web. 網頁是否可以使用，功能規格是依照指示。
	1. **Quality over quantity.** We would rather you focus on fewer features that are working and bug-free, rather than a bunch of broken, buggy features. 
1. Your code, hosted on Github. (This can serve as a portfolio for your future interviews and resume.)

## Pre-Exam Preparation 考前準備
> **IMPORTANT:**
> We highly, HIGHLY recommend you setup a live web server with a blank static web page (e.g. Django, Rails, Node.js) **BEFORE** your exam. It will save you a lot of time during the exam. 為節省時間，我們強烈建議您在**考試前**先設置一個空白的網頁.

1. **Development Environment. 開發環境.** Setup a linux-based development environment. We recommend MacOS or Ubuntu. 預先準備好網頁開發環境，使用你習慣的語言、架構、前後端、DB。
	1. Setup JavaScript or any language you wish to use.
	1. Setup any web framework you’re most familiar with (e.g. Django, React.js, Node.js)
	1. Setup a database you are most familar with to store customer data. Both SQL or no SQL database are OK. 提前先建立好 DB 環境。
	1. Setup IDEs or any developer tools to maximize your efficiency during the exam. 預先設定好幫助開發的軟體，例如：Gulp.js, Webpack, ESLint, Jest, Mocha, Chai, Jasmine, TypeScripte, Babel, EJS。
1. **Self or Cloud Hosted Test.** Make sure you can host a webpage from your development box or cloud on the world wide web.
	1. Open a port that is more secure than commonly scanned ports (e.g. Port 22)
	1. Make sure firewall configured so you can see your web page outside of your local area or cloud network.
1. **GitHub or GitLab Account.** Make sure you have a public GitHub/GitLab account that you can host your exam submission code for us to evaluate.
1. **How to prepare. 如何準備.**
	1. Be prepared to implement a database. 熟悉如何設立 DB（SQL, MongoDB 環境）。
	1. Be prepared to implement both front- and back- end developement. A common stack is: JS, Express, Node, HTML, CSS, React. 準備設立網頁前後端，使用 JS, Express, Node, HTML, CSS, React (AJAX, JSON, REST) 或類似。
	1. There are no tricks or brain teasers. You will be building a website with user and admin functions, like a shopping site, a booking site, or a news site. 沒有陷阱或腦筋急轉彎。 你將建立一個具有用戶使用和管理員管制功能的網站。比方說一個購物、訂機票/旅館或是看新聞的平台。
	1. Create a Facebook Login account and a Google Developer account and have key ready. You will need to implement an OAuth for user login management. 請先建立 FB Login 和 Google Developer 帳號和 key。你會需要設立使用者登入功能。 
	1.  Be familiar with how to connect to an API. 熟悉如何連接 API，像是 Google Maps 地圖、Stripe、寄 email SendGrid、Firebase, etc. 

## How to Submit 如何交卷

> **IMPORTANT:**
> Please submit your exam (complete the form) regardless of whether you have a live site. 不管進度，請使用以下問卷提交你的網頁 live demo URL。
> The form collects your GitHub URL. We want to see your source code regardless of the progress you've made.

1. Upload code to public GitHub or GitLab account. 上傳進度到GitHub 或 GitLab.
1. Run your app in production for 1 week. 
1. **Please submit exam by clicking "Submit Exam" below.**

<br>

[Submit Exam]({{ site.exam_submit_form_url }}){: .btn#page-btn}