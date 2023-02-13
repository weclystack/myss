+++
categories = ["Bug Hunter"]
date = 2023-02-02T02:00:00Z
description = ""
image = "/images/screenshot-2.png"
title = "How to host ezXSS in cPanel "
type = "featured"

+++
**_What is ezxss? ezxss is the same as the ezxss version of xss hunter, we can host it, manage it privately on our server and no less, ezxss can send reports via_**

**_e-mail and telegram bots._**

[ezXSS demos](https://demo.ezxss.com/manage/login )

## Instalasi ezXSS

**_1. You can clone or downloads the repo from the official ezxss_**

[**_https://github.com/ssl/ezXSS_**](https://github.com/ssl/ezXSS "https://github.com/ssl/ezXSS")

**_2. upload the files that you have cloned or those that you have downloaded to      cpanel._**

**_3. create a database and database user in your cpanel_**

**_if you don't know how to create a database you can_** [**_click here_**](https://www.jagoanhosting.com/tutorial/cpanel/user-database-di-cpanel)

**_4. extract the file and replace the file named .env.example to .env and don't forget to change the contents of the env file with the database name, db user, db password_**

**_5. after that you can access_** [**_https://example.com/manage/install_**](https://example.com/manage/install "https://example.com/manage/install")

## ezXSS display

![](/images/screenshot-5.png)![](/images/screenshot-4.png)![](/images/screenshot-2.png)

## ezXSS features

* Easy to use dashboard with statistics, payloads, view/share/search reports
* Payload generator
* Instant alerts via mail, Telegram or custom callback URL
* Custom javascript payloads
* Custom payload links to distinguish insert points
* Block, whitelist and other filters
* Share reports with a direct link, via email or with other ezXSS users
* Secure your login with Two-factor (2FA)
* The following information can be collected on a vulnerable page:
  * The URL of the page
  * IP Address
  * Any page referer (or share referer)
  * The User-Agent
  * All Non-HTTP-Only Cookies
  * All Locale Storage
  * All Session Storage
  * Full HTML DOM source of the page
  * Page origin
  * Time of execution
  * Payload URL
  * Screenshot of the page
  * Extract additional defined pages

###### **this is how to host ezXSS on cpanel, that's all I can say in this article, I hope it's     useful bye.**