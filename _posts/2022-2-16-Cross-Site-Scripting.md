---
title: Cross Site Scripting | XSS
layout: post
categories: [Web-Vulnerabilities,XSS]
tags: [Vulnerability,XSS]
toc: false
published: true
---

# Cross Site Scripting | XSS

| Content             |
| ------------------- |
| 📚 What Is XSS ?    |
| 🤔 Why XSS Happen ? |
| 🧬 XSS Types        |
|  ⚔ Impact           |
| 🔎 How To Find      |
| 🛺 Automate         |
| 🛠 Tools             |
| 📕 Referance        |
| 🔬 Labs             |

## 📚 What Is XSS ?

Cross-site scripting (also known as **XSS** NOT **CSS**) is a **Client-side** web security vulnerability that allows an attacker to compromise the interactions that users have with a vulnerable application.
Cross-site scripting works by manipulating a vulnerable web site so that it returns malicious JavaScript to users.

![](https://i.imgur.com/HI5gt1d.png)

Learn **JavaScript** From [here](https://www.w3schools.com/js/) 

---

## 🤔 Why Xss Happen ?

XSS happen because developer trusted more users
doesn't put any validation or sanitization for every input that reflects in HTML code or stored in the database and back again to display in HTML code or in DOM code like source and sinks

---

## 🧬 XSS Types


### 1. Reflected XSS | RXSS | Non-persistent.
First type is **RXSS** happen where the malicious script comes from the current **HTTP Request.**


**Example-1:**
![](https://i.imgur.com/L7RUORO.png)
Paramter **Search** Reflected in this HTML page
![](https://i.imgur.com/6hCGuqa.png)
After seeing source code found that it doesn't encode any special charachters like <,>,',".
![](https://i.imgur.com/JlZ9Q3L.png)
Ensure that any html tag will work like bold tag
![](https://i.imgur.com/7jLOeFg.png)
Try to execute XSS using script tag bingoo it works well
This is Reflected XSS


### 2. Stored XSS  | SXSS | Persistent.
Second type is **SXSS** happen where the malicious script comes from the website's **DataBase**.

**Example-2:**
So as we said Stored XSS should be saved in the database first to achieve this type of xss

![](https://i.imgur.com/zQp93Ij.png)
enter values in cooment,name,email and website press "Post Comment"
![](https://i.imgur.com/g4ApvG2.png)
in this page there are two input data saved
name and comment

![](https://i.imgur.com/U68SP4T.png)

![](https://i.imgur.com/tK4IABn.png)

![](https://i.imgur.com/VoXzCiT.png)



### 3. Blind XSS | BXSS.
Third type is a **Blind XSS** is a type of **Stored XSS** in which the attacker’s input is saved by the server and is reflected in the developer’s application. Basically, the attacker’s payload is executed on the application used by team members or admins.

Normally I use **XSSHunter** for finding Blind XSS. There are more tools available on the Internet that are: Burp Collaborator, KnoXSS, bXSS Hunter and many more.

You can know more about XssHunter from [Here](https://xsshunter.com/features)

### 4. DOM-based XSS.
Fourh type is where the vulnerability exists in client-side code rather than server-side code.

I will Discuess about it in another part soon | إن شاء الله

### 5. Self XSS
Self Cross site scripting(XSS) is a vulnerability in web applications which gives the ability of executing JS as the same user and not to other users.

**Severity :** Self-XSS only=>Low, Self-XSS + escalation=>Low-medium

it may be **Reflected**, **Stored** and **DOM**


at the end there are many Q&A from portswagger



### What is the difference between reflected XSS and stored XSS? 
Reflected XSS arises when an application takes some input from an HTTP request and embeds that input into the immediate response in an unsafe way. With stored XSS, the application instead stores the input and embeds it into a later response in an unsafe way.

### What is the difference between reflected XSS and self-XSS? 
Self-XSS involves similar application behavior to regular reflected XSS, however it cannot be triggered in normal ways via a crafted URL or a cross-domain request. Instead, the vulnerability is only triggered if the victim themselves submits the XSS payload from their browser. Delivering a self-XSS attack normally involves socially engineering the victim to paste some attacker-supplied input into their browser. As such, it is normally considered to be a lame, low-impact issue.

---

## ⚔ Impact

There is a reason why it has been in **OWASP for 2013** and **2017**. XSS can have huge implications for a web application and its users. **User accounts can be hijacked**, **credentials** could be **stolen**, **sensitive data** could be **exfiltrated**, and lastly, access to your client computers can be obtained.

---

## 🔎 How To Find

1. easiest way to find xss through your recon

- [ ] Collect subdomains from [**subfinder**, **assetfinder**, **findomain** and etc ..]
- [ ] Collect urls for each subdomain [ **hakrawler**, **gauplus**, **waybackurls** and **gospider**]
- [ ] Filter all urls using [**uro**](https://github.com/s0md3v/uro)
- [ ] Use [**gf**](https://github.com/tomnomnom/gf) to classifiy your paramters
- [ ] Now use [**kxss**](https://github.com/Emoe/kxss) to find any url parameter is vulnerable
- [ ] Now you can use [**dalfox**](https://github.com/hahwul/dalfox) to create your poc for any xss found 

---
2. By using this **bash script**

```ruby
#!/bin/bash

hakrawler -url "${1}" -plain -usewayback -wayback | grep "${1}" | grep "=" | egrep -iv ".(jpg|jpeg|gif|css|tif|tiff|png|ttf|woff|woff2|ico|pdf|svg|txt|js)" | qsreplace -a | kxss | grep -Eo "(http|https)://[a-zA-Z0-9./?=_-]*" | dalfox pipe -b https://your.xss.ht
```
---
3. Using **Burp Scanner** & **Acunetix**
---
4. All these three ways to find xss 90% will be **duplicated** because there are a lot of people do that before you i prefer to do this **manually** with each paramter and enumerate for hidden paramters using tools like [Arjun](https://github.com/s0md3v/Arjun),[x8](https://github.com/Sh1Yo/x8) and [Burp paraminer extension](https://portswigger.net/bappstore/17d2949a985c4b7ca092728dba871943).

## 🛠 Tools
Most tools are also suitable for blind XSS attacks:

[**XSSStrike**](https://github.com/s0md3v/XSStrike): Very popular but unfortunately not very well maintained
[**xsser**](https://github.com/epsylon/xsser): Utilizes a headless browser to detect XSS vulnerabilities
[**kxss**](https://github.com/Emoe/kxss) to find any url parameter is vulnerable
[**Dalfox**](https://github.com/hahwul/dalfox): Extensive functionality and extremely fast thanks to the implementation in Go
[**XSpear**](https://github.com/hahwul/XSpear): Similar to Dalfox but based on Ruby
[**domdig**](https://github.com/fcavallarin/domdig): Headless Chrome XSS Tester

## 📕 Referance

[**portswigger**](https://portswigger.net/web-security/cross-site-scripting)
[**OWASP**](https://owasp.org/www-community/attacks/xss/)
[**PayloadsAllTheThings**](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection)
[**hacktricks**](https://book.hacktricks.xyz/pentesting-web/xss-cross-site-scripting)
[**hackingarticles**](https://www.hackingarticles.in/comprehensive-guide-on-cross-site-scripting-xss/)
[**Ebrahem Hegazy**](https://www.youtube.com/watch?v=xiw_O5shcK4&list=PLv7cogHXoVhXvHPzIl1dWtBiYUAL8baHj&index=29) From **29Ep** : **35Ep**

## 🔬 Labs
[**portswigger**](https://portswigger.net/web-security/cross-site-scripting)
[**OWASP Broken Web Applications Project**](https://sourceforge.net/projects/owaspbwa/) Install this Machine and will have a lot of Labs like **DVWA**, **BWAPP** and **Webgoat** etc
