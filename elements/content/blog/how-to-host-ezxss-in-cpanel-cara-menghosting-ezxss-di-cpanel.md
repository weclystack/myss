+++
categories = ["Bug Hunter"]
date = 2023-02-02T02:00:00Z
description = ""
image = "/images/screenshot-2.png"
title = "How to host ezXSS in cPanel (Cara menghosting ezXSS di cPanel)"
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

   **_if you don't know how to create a database you can_** [**_click here_**](https://www.jagoanhosting.com/tutorial/cpanel/user-database-di-cpanel "https://www.jagoanhosting.com/tutorial/cpanel/user-database-di-cpanel) 

**_4. extract the file and replace the file named .env.example to .env and don't forget to change the contents of the env file with the database name, db user, db password_**

**_5. after that you can access_** [**_https://example.com/manage/install_**](https://example.com/manage/install "https://example.com/manage/install")

## ezXSS display

![](/images/screenshot-5.png)![](/images/screenshot-4.png)![](/images/screenshot-2.png)

## ezXSS features

**_* Easy to use dashboard with statistics, payloads, view/share/search reports_**

**_* Payload generator_**

**_* Instant alerts via mail, Telegram or custom callback URL_**

**_* Custom javascript payloads_**

**_* Custom payload links to distinguish insert points_**

**_* Block, whitelist and other filters_**

**_* Share reports with a direct link, via email or with other ezXSS users_**

**_* Secure your login with Two-factor (2FA)_**

**_* The following information can be collected on a vulnerable page:_**

  **_* The URL of the page_**

  **_* IP Address_**

  **_* Any page referer (or share referer)_**

  **_* The User-Agent_**

  **_* All Non-HTTP-Only Cookies_**

  **_* All Locale Storage_**

  **_* All Session Storage_**

  **_* Full HTML DOM source of the page_**

  **_* Page origin_**

  **_* Time of execution_**

  **_* Payload URL_**

  **_* Screenshot of the page_**

  **_* Extract additional defined pages_**

**_* its just ez :-)_**

######  **this is how to host ezXSS on cpanel, that's all I can say in this article, I hope it's     useful bye.**