---
title: Web Vulnerabilities WriteUps
layout: post
categories: [Writeups,Web-Vulnerabilities-Writeups]
tags: [Writeups,XSS,CSP,SQLI,Open-Redirect,IDOR,HPP,Information-disclosure,CORS,SOP,XXE,DOS,html-injection,S3,clickjacking,host-header-injection,SSRF,os-command-injection,CSRF,LFI,LFD,path-traversal,RFI,file-upload]
toc: false
published: true
---

## Cross Site Scripting (XSS)

- [From P5 to P2 to 100 BXSS](https://medium.com/@mohameddaher/from-p5-to-p5-to-p2-from-nothing-to-1000-bxss-4dd26bc30a82)
- [Google Acquisition XSS (Apigee)](https://medium.com/@TnMch/google-acquisition-xss-apigee-5479d7b5dc4)
- [DOM-Based XSS at accounts.google.com by Google Voice Extension](http://www.missoumsai.com/google-accounts-xss.html)
- [XSS on Microsoft.com via Angular Js template injection](https://medium.com/@impratikdabhi/reflected-xss-on-microsoft-com-via-angular-template-injection-2e26d80a7fd8)
- [Researching Polymorphic Images for XSS on Google Scholar](https://blog.doyensec.com/2020/04/30/polymorphic-images-for-xss.html)
- [Netflix Party Simple XSS](https://medium.com/@kristian.balog/netflix-party-simple-xss-ec92ed1d7e18)
- [Stored XSS in google nest](https://medium.com/bugbountywriteup/stored-xss-in-google-nest-a82373bbda68)
- [Self XSS to persistent XSS on login portal](https://medium.com/@nnez/always-escalate-from-self-xss-to-persistent-xss-on-login-portal-54265b0adfd0)
- [Universal XSS affecting Firefox ](https://0x65.dev/blog/2020-03-30/cve-2019-17004-semi-universal-xss-affecting-firefox-for-ios.html)
- [XSS WAF Character limitation bypass like a boss](https://medium.com/bugbountywriteup/xss-waf-character-limitation-bypass-like-a-boss-2c788647c229)
- [Self XSS to Account Takeover ](https://medium.com/@ch3ckm4te/self-xss-to-account-takeover-72c89775cf8f)
- [Reflected XSS on Microsoft subdomains ](https://medium.com/bugbountywriteup/reflected-xss-on-microsoft-com-subdomains-4bdfc2c716df)
- [The tricky XSS](https://smaranchand.com.np/2020/02/the-tricky-xss/)
- [Reflected XSS  in AT&T](https://medium.com/@godofdarkness.msf/reflected-xss-in-at-t-7f1bdd10d8f7)
- [XSS on Google using Acunetix ](https://www.acunetix.com/blog/web-security-zone/xss-google-acunetix/)
- [Exploiting websocket application wide XSS](https://medium.com/@osamaavvan/exploiting-websocket-application-wide-xss-csrf-66e9e2ac8dfa)
- [Reflected XSS with  HTTP Smuggling ](https://hazana.xyz/posts/escalating-reflected-xss-with-http-smuggling/)
- [XSS on Facebook instagram CDN server bypassing signature protection ](https://www.amolbaikar.com/xss-on-facebook-instagram-cdn-server-bypassing-signature-protection/)
- [XSS on Facebook's Acquisition Oculus](https://www.amolbaikar.com/xss-on-facebooks-acquisition-oculus-cdn-server/)
- [XSS on sony Subdomain ](https://medium.com/@gguzelkokar.mdbf15/xss-on-sony-subdomain-feddaea8f5ac)
- [Exploiting Self XSS ](https://footstep.ninja/posts/exploiting-self-xss/)
- [Effortlessly Finding Cross Site Scripting inclusion XSSI ](https://medium.com/bugbountywriteup/effortlessly-finding-cross-site-script-inclusion-xssi-jsonp-for-bug-bounty-38ae0b9e5c8a)
- [Bugbounty a DOM XSS](https://jinone.github.io/bugbounty-a-dom-xss/)
- [Blind XSS : a mind Game ](https://medium.com/@dirtycoder0124/blind-xss-a-mind-game-to-win-the-battle-4fc67c524678?)
- [FireFox IOS QR code reader XSS(CVE-2019-17003)](https://payatu.com/blog/nikhil-mittal/firefox-ios-qr-code-reader-xss-(cve-2019-17003))
- [HTML injection to XSS](https://evanricafort.blogspot.com/2019/12/html-injection-to-xss-bypass-in.html)
- [CVE-2020-13487 Authenticated Stored Cross-site Scripting in bbPress](https://hackerone.com/reports/881918)
- [XSS at error page of repository code ](https://medium.com/@navne3t/150-xss-at-error-page-of-respository-code-4fc628892742)
- [XSS like a Pro](https://www.hackerinside.me/2019/12/xss-like-pro.html)
- [How I turned self XSS to stored XSS via CSRF](https://medium.com/@abhishake100/how-i-turned-self-xss-to-stored-via-csrf-d12eaaf59f2e)
- [XSS Stored on Outlook web](https://medium.com/@elmrhassel/xss-stored-on-outlook-web-outlook-android-app-ad4bd46b8823)
- [XSS Bug 20 Chars Blind XSS Payload](https://medium.com/@mohameddaher/how-i-paid-2-for-1054-xss-bug-20-chars-blind-xss-payloads-12d32760897b)
- [XSS in AMP4EMAIL(DOM clobbering)](https://research.securitum.com/xss-in-amp4email-dom-clobbering/)
- [DOM Based XSS bug bounty writeup](https://hacknpentest.com/dom-based-xss-bug-bounty-writeup/)
- [XSS will never die ](https://medium.com/@04sabsas/xss-will-never-die-eb3584081a5f)
- [5000 USD XSS issue at avast desktop antivirus](https://medium.com/bugbountywriteup/5-000-usd-xss-issue-at-avast-desktop-antivirus-for-windows-yes-desktop-1e99375f0968)
- [XSS to account takeover](https://noobe.io/articles/2019-10/xss-to-account-takeover)
- [How Paypal helped me to generate XSS](https://medium.com/@pflash0x0punk/how-paypal-helped-me-to-generate-xss-9408c0931add)
- [Bypass Uppercase filters like a PRO(XSS advanced methods)](https://medium.com/@Master_SEC/bypass-uppercase-filters-like-a-pro-xss-advanced-methods-daf7a82673ce)
- [Stealing login credentials with reflected XSS ](https://medium.com/@mehulcodes/stealing-login-credentials-with-reflected-xss-7cb450bf5710)
- [bughunting xss on cookie popup warning ](https://victoni.github.io/bug-hunting-xss-on-cookie-popup-warning/)
- [XSS is love](https://nirmaldahal.com.np/xss-is-love/)
- [Oneplus XSS vulnerability in customer support portal](https://medium.com/@tech96bot/oneplus-xss-vulnerability-in-customer-support-portal-d5887a7367f4)
- [Exploiting cookie based XSS by finding RCE ](https://noobe.io/articles/2019-09/exploiting-cookie-based-xss-by-finding-rce)
- [Stored XSS on zendesk via macros ](https://medium.com/@hariharan21/stored-xss-on-zendesk-via-macros-part-2-676cefee4616)
- [XSS in ZOHO main](https://www.hackerinside.me/2019/09/xss-in-zoho-mail.html)
- [DOM based XSS in private program](https://www.mohamedharon.com/2019/09/dom-based-xss-in-private-program.html)
- [Bugbounty writeup : Take Attention and get stored XSSS](https://medium.com/@04sabsas/bugbounty-writeup-take-attention-and-get-stored-xss-495dd6eab07e)
- [How I xssed admin account ](https://gauravnarwani.com/how-i-xssed-admin-account/)
- [Clickjacking XSS on google ](https://websecblog.com/vulns/clickjacking-xss-on-google-org/)
- [Stored XSS on laporbugid](https://learn.hackersid.com/2019/08/stored-xss-on-laporbugid.html)
- [Leveraging angularjs based XSS to privilege escalation](https://www.shawarkhan.com/2019/08/leveraging-angularjs-based-xss-to-privilege-escalation.html)
- [How I found XSS by searching in shodan](https://blog.usejournal.com/how-i-found-xss-by-searching-in-shodan-6943b799e648)
- [Chaining caache poisining to stored XSS](https://medium.com/@nahoragg/chaining-cache-poisoning-to-stored-xss-b910076bda4f)
- [XSS  to RCE ](https://medium.com/@hungrybytes/xss-to-rce-in-e20b2bc55f94)
- [XSS on twitter worth 1120](https://medium.com/@bywalks/xss-on-twitter-worth-1120-914dcd28ee18)
- [Reflected XSS in ebay.com](https://medium.com/@madguyyy/reflected-xss-in-ebay-com-60a9d61e26cd)
- [Cookie based XSS exolpoitation 2300 bug bounty ](https://medium.com/@iSecMax/сookie-based-xss-exploitation-2300-bug-bounty-story-9bc532ffa564)
- [What do netcat -SMTP-self XSS have in common ](https://medium.com/bugbountywriteup/what-do-netcat-smtp-and-self-xss-have-in-common-stored-xss-a05648b72002)
- [XSS on google custom search engine ](https://thesecurityexperts.wordpress.com/2019/07/11/xss-on-google-custom-search-engine/)
- [Story of a Full Account Takeover vulnerability N/A to Accepted ](https://medium.com/@nandwanajatin25/story-of-a-stored-xss-to-full-account-takeover-vulnerability-n-a-to-accepted-8478aa5e0d8e)
- [Yeah I got p2 in 1 minute stored XSS via markdown editor ](https://medium.com/@schopath/yeah-i-got-p2-in-1-minute-stored-xss-via-markdown-editor-7872dba3f158)
- [Stored XSS on indeed ](https://cyberzombie.in/stored-xss-on-indeed/)
- [Self XSS to evil XSS](https://medium.com/@saadahmedx/self-xss-to-evil-xss-bcf2494a82a4)
- [How a classical XSS can lead to persistent  ATO vulnerability](https://hackademic.co.in/how-a-classical-xss-can-lead-to-persistent-ato-vulnerability/)
- [Reflected XSS in tokopedia train ticket ](https://visat.me/security/reflected-xss-in-tokopedia-train-ticket/)
- [Bypassing XSS filter and stealing user credit card data](https://medium.com/@osamaavvan/bypassing-xss-filter-and-stealing-user-credit-card-data-100f247ed5eb)
- [Googleplex.com blind XSS](https://websecblog.com/vulns/googleplex-com-blind-xss/)
- [Reflected XSS on error page ](https://noobe.io/articles/2019-06/reflected-xss-on-error-page)
- [How I was able to get private ticket response panel and fortigate web panel via blind XSS ](https://pwnsec.ninja/2019/06/06/how-i-was-able-to-get-private-ticket-response-panel-and-fortigate-web-panel-via-blind-xss/)
- [Unicode vs WAF](https://medium.com/bugbountywriteup/unicode-vs-waf-xss-waf-bypass-128cd9972a30)
- [Story of URI based XSS with some simple google dorking ](https://medium.com/@nandwanajatin25/story-of-a-uri-based-xss-with-some-simple-google-dorking-e1999254aa55)
- [Stored XSS on edmodo](https://medium.com/@matarpan33r/stored-xss-on-edmodo-67b244824fa5)
- [XSSed my way to 1000](https://gauravnarwani.com/xssed-my-way-to-1000/)
- [Try harder for XSS](https://medium.com/@fbotes2/try-harder-for-xss-7aa3657255a1)
- [From parameter pollution to XSS](https://medium.com/@momenbasel/from-parameter-pollution-to-xss-d095e13be060)
- [MIME  sniffing XSS](https://www.komodosec.com/post/mime-sniffing-xss)
- [Stored XSS on techprofile Microsoft  ](https://medium.com/@kang_ali/stored-xss-on-techprofile-microsoft-d21757588cc1)
- [Tale of a wormable Twitter XSS](https://www.virtuesecurity.com/tale-of-a-wormable-twitter-xss/)
- [XSS attacks google bot index manipulation](http://www.tomanthony.co.uk/blog/xss-attacks-googlebot-index-manipulation/)
- [From Reflected XSS to Account takeover ](https://medium.com/a-bugz-life/from-reflected-xss-to-account-takeover-showing-xss-impact-9bc6dd35d4e6)
- [Stealing local storage data through XSS](http://blog.h4rsh4d.com/2019/04/stealing-local-storage-data-through-xss.html)
- [CSRF attack can lead to stored XSS](https://medium.com/bugbountywriteup/csrf-attack-can-lead-to-stored-xss-f40ba91f1e4f)
- [XSS Reflected (filter bypass)](https://medium.com/bugbountywriteup/xss-reflected-xss-bypass-filter-de41d35239a3)
- [XSS protection bypass on hackerone private program](https://medium.com/@bughunter.sec7/how-i-was-able-to-bypass-xss-protection-on-hackerones-private-program-8914a31339a9)
- [Just 5 minutes to get my 2nd Stored XSS on edmodo.com](https://medium.com/@ZishanAdThandar/just-5-minute-to-get-my-2nd-stored-xss-on-edmodo-com-fe2ee559e00d)
- [Multiple XSS in  skype.com ](https://medium.com/@jayateerthag/multiple-xss-in-skype-com-2-18cfed39edbd)
- [Obtaining XSS using moodle featured and minor bugs ](https://medium.com/@daniel.thatcher/obtaining-xss-using-moodle-features-and-minor-bugs-2035665989cc)
- [XSS on 403 forbidden bypass akamai WAF](https://medium.com/@bughunter.sec7/xss-403-forbidden-bypass-akamai-security-write-up-b341f588efb5)
- [How I was turn self XSS into reflected XSS](https://medium.com/@heinthantzin/how-i-was-able-to-turn-self-xss-into-reflected-xss-850e3d5a2beb)
- [A Tale of 3 XSS](https://gauravnarwani.com/a-tale-of-3-xss/)
- [Stored XSS on Google.com](https://medium.com/@bughunter.sec7/stored-xss-on-google-com-e7ac12f03b8e)
- [Stored XSS in the Guides gameplaersion (www.dota2.com)](https://medium.com/@bughunter.sec7/stored-xss-in-the-guides-gameplayversion-www-dota2-com-775fa9a1889b)
- [Admin google.com reflected XSS](https://buer.haus/2015/01/21/admin-google-com-reflected-cross-site-scripting-xss/)
- [Paypal Stored security bypass ](https://blog.it-securityguard.com/bugbounty-paypal-stored-xss-security-bypass/)
- [Paypal DOM XSS main domain](https://blog.it-securityguard.com/bugbounty-paypal-dom-xss-main-domain/)
- [Bugbounty  : The 5k$ Google XSS](https://blog.it-securityguard.com/bugbounty-the-5000-google-xss)
- [Facebook stored XSS](https://buer.haus/2014/06/16/facebook-stored-cross-site-scripting-xss-badges/)
- [Ebay mobile reflected XSS](https://thehackerblog.com/ebay-mobile-reflected-xss-disclosure-writeup/index.html)
- [Magix bugbounty XSS writeup](https://www.rcesecurity.com/2014/04/magix-bug-bounty-magix-com-rce-sqli-and-xara-com-lfi-xss/)
- [Abusing CORS for an XSS on flickr ](https://whitton.io/articles/abusing-cors-for-an-xss-on-flickr/)
- [XSS on google groups ](https://manuel-sousa.blogspot.com/2013/11/xss-google-groups-groupsgooglecom.html)
- [Oracle XSS](http://blog.shashank.co/2013/11/oracle-xss.html)
- [Content types and XSS Facebook Studio](https://whitton.io/articles/content-types-and-xss-facebook-studio/)
- [Admob Creative image XSS](https://bitquark.co.uk/blog/2013/07/19/admob_creative_image_xss)
- [Amazon Packaging feedback XSS](https://bitquark.co.uk/blog/2013/07/03/amazon_packaging_feedback_xss)
- [PaypalTech XSS ](https://www.rcesecurity.com/2013/04/paypal-bug-bounty-paypaltech-com-xss/)
- [Persistent XSS on my world](https://whitton.io/archive/persistent-xss-on-myworld-ebay-com/)
- [Google VRP XSS in device management](https://sites.google.com/securifyinc.com/vrp-writeups/gsuite/bookmark-xss-device-management)
- [Google VRP XSS](https://sites.google.com/securifyinc.com/vrp-writeups/hire-with-google/xsses)
- [Google VRP Blind XSS](https://sites.google.com/securifyinc.com/vrp-writeups/hire-with-google/blind-xss)
- [WAZE XSS](https://sites.google.com/securifyinc.com/vrp-writeups/waze/waze-xss)
- [Referer Based XSS](https://medium.com/@arbazhussain/referer-based-xss-52aeff7b09e7)
- [How we invented the Tesla DOM XSS](https://labs.detectify.com/2017/07/27/how-we-invented-the-tesla-dom-doom-xss/)
- [Stored XSS on rockstar game](https://medium.com/@arbazhussain/stored-xss-on-rockstar-game-c008ec18d071)
- [How I was able to bypass strong XSS protection in well known website imgur.com](https://medium.com/bugbountywriteup/how-i-was-able-to-bypass-strong-xss-protection-in-well-known-website-imgur-com-8a247c527975)
- [Self XSS to Good XSS](https://medium.com/@arbazhussain/self-xss-to-good-xss-clickjacking-6db43b44777e)
- [That escalated quickly : from partial CSRF to reflected XSS to complete CSRF to Stored XSS](https://medium.com/@ciph3r7r0ll/that-escalated-quickly-from-partial-csrf-to-reflected-xss-to-complete-csrf-to-stored-xss-6ba8103069c2)
- [XSS using dynamically generated js file](https://medium.com/@arbazhussain/xss-using-dynamically-generated-js-file-a7a10d05ff08)
- [Bypassing XSS filtering at anchor Tags](https://medium.com/@arbazhussain/bypassing-xss-filtering-at-anchor-tags-706dde7b8090)
- [XSS by tossing cookies](https://wesecureapp.com/blog/xss-by-tossing-cookies/)
- [Coinbase angularjs dom XSS via kiteworks](http://www.paulosyibelo.com/2017/07/coinbase-angularjs-dom-xss-via-kiteworks.html)
- [Medium Content spoofing and XSS](https://ahussam.me/Medium-content-spoofing-xss/)
- [Managed Apps and music a tale of two XSSes in Google play](https://ysx.me.uk/managed-apps-and-music-a-tale-of-two-xsses-in-google-play/)
- [Making an XSS triggered by CSP bypass on twitter ](https://medium.com/@tbmnull/making-an-xss-triggered-by-csp-bypass-on-twitter-561f107be3e5)
- [Escalating XSS in phantomjs image rendering to SSRF](https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/)
- [Reflected XSS in Simplerisk](https://www.seekurity.com/blog/general/reflected-xss-vulnerability-in-simplerisk/)
- [Stored XSS in the heart of the russian email provider](https://www.seekurity.com/blog/general/stored-xss-in-the-heart-of-the-russian-email-provider-giant-mail-ru/)
- [How I built an XSS worm on atmail](https://www.bishopfox.com/blog/2017/06/how-i-built-an-xss-worm-on-atmail/)
- [XSS on bugcrowd and so many other websites main domain](https://blog.witcoat.com/2018/05/30/xss-on-bugcrowd-and-so-many-other-websites-main-domain/)
- [Godaddy XSS affects parked domains redirector Processor](https://www.seekurity.com/blog/write-ups/godaddy-xss-affects-parked-domains-redirector-processor/)
- [Stored XSS in Google image search](https://sites.google.com/site/bugbountybughunter/home/stored-xss-in-google-image-search)
- [A pair of plotly bugs stored XSS abd AWS metadata](https://ysx.me.uk/a-pair-of-plotly-bugs-stored-xss-and-aws-metadata-ssrf/)
- [Near universal XSS in mcafee web gateway](https://blog.ettic.ca/near-universal-xss-in-mcafee-web-gateway-cf8dfcbc8fc3)
- [Penetrating Pornhub XSS vulns](https://www.jonbottarini.com/2017/03/16/penetrating-pornhub-xss-vulns-galore-plus-a-cool-shirt/)
- [How I found a 5000 Google maps XSS by fiddling with protobuf](https://medium.com/@marin_m/how-i-found-a-5-000-google-maps-xss-by-fiddling-with-protobuf-963ee0d9caff)
- [Airbnb when bypassing json encoding XSS filter WAF CSP and auditior turns into eight vulnerabilities](https://buer.haus/2017/03/08/airbnb-when-bypassing-json-encoding-xss-filter-waf-csp-and-auditor-turns-into-eight-vulnerabilities/)
- [Lightwight markup a trio of persistent XSS in gitlab](https://ysx.me.uk/lightweight-markup-a-trio-of-persistent-xss-in-gitlab/)
- [XSS ONE BAY](https://whitehatnepal.tumblr.com/post/153333332112/xssonebay)
- [SVG XSS in unifi](https://guptashubham.com/svg-xss-in-unifi-v5-0-2/)
- [Stored XSS in unifi V4.8.12 controller](https://guptashubham.com/stored-xss-in-unifi-v4-8-12-controller/)
- [Turning self XSS into good XSS v2](https://httpsonly.blogspot.com/2016/08/turning-self-xss-into-good-xss-v2.html)
- [SWF XSS DOM Based XSS](https://guptashubham.com/swf-xss-dom-based-xss/)
- [XSS filter bypass in Yahoo Dev flurry](https://guptashubham.com/xss-filter-bypass-in-yahoo-dev-flurry-com/)
- [XSS on Flickr](https://guptashubham.com/xss-on-flickr/)
- [Two vulnerabilities makes an exploit XSS and csrf in bing](https://medium.com/bugbountywriteup/two-vulnerabilities-makes-an-exploit-xss-and-csrf-in-bing-cd4269da7b69)
- [Runkeeper stored XSS](https://www.seekurity.com/blog/general/runkeeper-stores-xss-vulnerability/)
- [Google sleeping XSS awakens 5k bounty](https://blog.it-securityguard.com/bugbounty-sleeping-stored-google-xss-awakens-a-5000-bounty/)
- [Poisoning the well compromising godaddy customer support with blind XSS](https://thehackerblog.com/poisoning-the-well-compromising-godaddy-customer-support-with-blind-xss/index.html)
- [UBER turning self XSS to good XSS](https://whitton.io/articles/uber-turning-self-xss-into-good-xss/)
- [XSS on facebook via png content types](https://whitton.io/articles/xss-on-facebook-via-png-content-types/)
- [Cloudflare XSS](https://ahussam.me/Cloudflare-xss/)
- [How I found XSS Vulnerability in Google ](https://zombiehelp54.blogspot.com/2015/09/how-i-found-xss-vulnerability-in-google.html)
- [XSS to RCE](https://matatall.com/xss/rce/bugbounty/2015/09/08/xss-to-rce.html)
- [One payload to XSS them all](https://ahussam.me/One-payload-to-xss-them/)
- [Self XSS on komunitas](https://medium.com/@bughunter.sec7/self-xss-on-komunitas-bukalapak-com-b8a28dce4fbd)
- [Reclected XSS on alibabacloud](https://medium.com/@bughunter.sec7/reflected-xss-on-alibabacloud-com-4e652fcca22f)
- [Self XSS on komunitas bukalapak](https://medium.com/@bughunter.sec7/self-xss-on-komunitas-bukalapak-com-b8a28dce4fbd)
- [A real XSS in OLX](https://medium.com/@paulorcchoupina/a-real-xss-in-olx-7727ae89c640)
- [Self XSS using IE adobes](https://medium.com/@80vul/from-http-domain-to-res-domain-xss-by-using-ie-adobes-pdf-activex-plugin-9f2a72a87aff)
- [Stealing local storage through XSS](http://blog.h4rsh4d.com/2019/04/stealing-local-storage-data-through-xss.html)
- [1000 USD in 5mins Stored XSS in Outlook](https://omespino.com/write-up-1000-usd-in-5-minutes-xss-stored-in-outlook-com-ios-browsers/)
- [OLX reflected XSS](https://medium.com/@abaykandotcom/olx-bug-bounty-reflected-xss-adb3095cd525)
- [My first stored XSS on edmodo.com](https://medium.com/@ZishanAdThandar/my-first-stored-xss-on-edmodo-com-540a33349662)
- [Hack your form new vector for BXSS](https://medium.com/@GeneralEG/hack-your-form-new-vector-for-blind-xss-b7a50b808016)
- [How I found Blind XSS vulnerability in redacted.com](https://medium.com/@newp_th/how-i-find-blind-xss-vulnerability-in-redacted-com-33af18b56869)
- [3 XSS in protonmail for iOS](https://medium.com/@vladimirmetnew/3-xss-in-protonmail-for-ios-95f8e4b17054)
- [XSS in edmodo wihinin 5 mins](https://medium.com/@valakeyur/xss-in-edmodo-within-5-minute-my-first-bug-bounty-889e3da6167d)
- [Stil work redirect Yahoo subdomain XSS](https://www.mohamedharon.com/2019/02/still-work-redirect-yahoo-subdomain-xss.html)
- [XSS in azure devOps](https://5alt.me/2019/02/xss-in-azure-devops/)
- [Shopify reflected XSS](https://medium.com/@modam3r5/reflected-xss-at-https-photos-shopify-com-ea696db3915c)
- [Muliple Stored XSS on tokopedia](https://apapedulimu.click/multiple-stored-xss-on-tokopedia/)
- [Stored XSS on edmodo](https://medium.com/@futaacmcyber/stored-xss-on-edmodo-11a3fbc6b6d0)
- [A unique XSS scenario 1000 Bounty](https://medium.com/@rohanchavan/a-unique-xss-scenario-1000-bounty-347f8f92fcc6)
- [Protonmail XSS Stored](https://medium.com/@ChandSingh/protonmail-xss-stored-b733031ac3b5)
- [Chaining tricky ouath exploitation to stored XSS](https://medium.com/@nahoragg/chaining-tricky-oauth-exploitation-to-stored-xss-b67eaea4aabd)
- [Antihack XSS to php uplaod](https://blog.saycure.io/2019/01/24/antihack-xss-2-php-upload/)
- [Reflected XSS in zomato](https://medium.com/@sudhanshur705/reflected-xss-in-zomato-f892d6887147)
- [XSS through SWF file](https://medium.com/@friendly_/xss-through-swf-file-4f04af7b0f59)
- [Hackyourform BXSS](https://generaleg0x01.com/2019/01/13/hackyourform-bxss/)
- [Reflected XSS on ASUS](https://medium.com/@thejuskrishnan911/reflected-xss-on-asus-568ce0541171)
- [Stored XSS via Alternate text at zendesk support](https://medium.com/@hariharan21/stored-xss-via-alternate-text-at-zendesk-support-8bfee68413e4)
- [How I stumbled upon a stored XSS : my first bug bounty story](https://medium.com/@parthshah14031998/how-i-stumbled-upon-a-stored-xss-my-first-bug-bounty-story-2793300d82bb)
- [Cookie based Self XSS to Good XSS](https://medium.com/bugbountywriteup/cookie-based-self-xss-to-good-xss-d0d1ca16dd0e)
- [Reflected XSS on amazon](https://medium.com/@newp_th/reflected-xss-on-ws-na-amazon-adsystem-com-amazon-f1e55f1d24cf)
- [XSS worm  : a creative use of web application vulnerability ](https://blog.compass-security.com/2018/12/xss-worm-a-creative-use-of-web-application-vulnerability/)
- [Google code in XSS](https://websecblog.com/vulns/google-code-in-xss/)
- [Self XSS on indeed.com](https://medium.com/@sampanna/self-xss-in-indeed-com-e0c99c104cba)
- [How I accidentally found XSS in Protonmail for iOS app](https://www.secu.ninja/2018/12/04/how-to-accidentally-find-a-xss-in-protonmail-ios-app/)
- [XML XSS in yandex.ru by accident](https://medium.com/@0ktavandi/xml-xss-in-yandex-ru-by-accident-7e63c692b4c0)
- [Critical Stored XSS vulnerability](https://www.hackerinside.me/2018/11/critical-stored-xss-vulnerability.html)
- [XSS bypass using META tag in realestate.postnl.nl ](https://medium.com/bugbountywriteup/xss-bypass-using-meta-tag-in-realestate-postnl-nl-32db25db7308)
- [Edmodo XSS bug](https://medium.com/@sameerphad72/edmodo-xss-bug-9c0fc9bdd0bf)
- [XSS in hiden input fields](https://portswigger.net/blog/xss-in-hidden-input-fields)
- [How I discovered XSS that affected over 20 uber subdomains](https://blog.fadyothman.com/how-i-discovered-xss-that-affects-over-20-uber-subdomains/)
- [DOM based XSS or why you should not rely on cloudflare too much](https://medium.com/bugbountywriteup/dom-based-xss-or-why-you-should-not-rely-on-cloudflare-too-much-a1aa9f0ead7d)
- [XSS in dynamics 365](https://medium.com/@tim.kent/xss-in-dynamics-365-25c800aac473)
- [XSS deface with html and how to convert the html into charcode](https://medium.com/@ariffadhlullah2310/xss-deface-with-html-and-how-to-convert-the-html-into-charcode-f0c62dd5ef3f)
- [Cookie based injection XSS making explitable with exploiting other vulns](https://medium.com/@agrawalsmart7/cookie-based-injection-xss-making-exploitable-with-out-exploiting-other-vulns-81132ca01d67)
- [XSS with put in ghost blog](https://www.itsecguy.com/xss-with-put-in-ghost-blog/)
- [XSS using a Bug in safari and why blacklists are stupid](https://labs.detectify.com/2018/10/19/xss-using-a-bug-in-safari-and-why-blacklists-are-stupid/)
- [Magic XSS with two parameters](https://medium.com/@m4shahab1/magic-xss-with-two-parameters-463559b03949)
- [DOM XSS bug affecting tinder shopify Yelp](https://www.vpnmentor.com/blog/dom-xss-bug-affecting-tinder-shopify-yelp/)
- [Persistent XSS unvalidated open graph embed at linkedin.com](https://medium.com/@jonathanbouman/persistent-xss-unvalidated-open-graph-embed-at-linkedin-com-db6188acedd9)
- [My first 0day exploit CSP Bypass Reflected XSS](https://medium.com/@alicanact60/my-first-0day-exploit-csp-bypass-reflected-xss-bugbounty-c7efa4bed3d7)
- [Google Stored XSS in payments](https://medium.com/@brs.sgdc/google-stored-xss-in-payments-350cd7ba0d1b)
- [XSS on dropbox](https://www.kumar.ninja/2018/09/xss-surveydropboxcom.html)
- [Weaponizing XSS attacking internal domains ](https://medium.com/@rahulraveendran06/weaponizing-xss-attacking-internal-domains-d8ba1cbd106d)
- [How I XSSed UBER and bypassed CSP](https://medium.com/@efkan162/how-i-xssed-uber-and-bypassed-csp-9ae52404f4c5)
- [RXSS and CSRF bypass to Account takeover](https://nirmaldahal.com.np/r-xss-csrf-bypass-to-account-takeover/)
- [Another XSS in google collaboratory](https://blog.bentkowski.info/2018/09/another-xss-in-google-colaboratory.html)
- [How I bypassed AKAMAI waf in overstock.com ](https://medium.com/@0ktavandi/how-i-bypassed-akamai-kona-waf-xss-in-overstock-com-f205b0e71a0d)
- [Reflected XSS at philips.com](https://medium.com/@jonathanbouman/reflected-xss-at-philips-com-e48bf8f9cd3c)
- [XSS vulnerabilities in multiple iframe busters affecting top tier sites](https://randywestergren.com/xss-vulnerabilities-in-multiple-iframe-busters-affecting-top-tier-sites/)
- [Reflected DOM XSS and clickjacking silvergoldbull](https://medium.com/@maxon3/reflected-dom-xss-and-clickjacking-on-https-silvergoldbull-de-bt-html-daa36bdf7bf0)
- [Stored XSS vulnerability in h1 private](https://www.hackerinside.me/2018/09/stored-xss-vulnerability-in-h1c-private.html)
- [Authbypass SQLi and XSS](https://blog.securitybreached.org/2018/09/09/zol-zimbabwe-authbypass-sqli-xss/)
- [Stored XSS vulnerability in tumblr](https://www.hackerinside.me/2018/09/stored-xss-vulnerability-in-tumblr.html)
- [XSS in google code jam](https://websecblog.com/vulns/reflected-xss-in-google-code-jam/)
- [Mapbox XSS](https://www.mohamedharon.com/2018/08/mapboxxss.html)
- [My first valid XSS](https://medium.com/@nandwanajatin25/my-first-valid-xss-hackerone-f8ba0a7c647)
- [Stored XSS in webcomponents.org](https://websecblog.com/vulns/stored-xss-in-webcomponents-org/)
- [3 minutes XSS](https://medium.com/bugbountywriteup/3-minutes-xss-71e3340ad66b)
- [icloud.com DOM based XSS](https://medium.com/@musabalhussein/icloud-com-dom-based-xss-bugbounty-6f88cb865b18)
- [XSS at hubspot and in email areas](https://medium.com/@friendly_/xss-at-hubspot-and-xss-in-email-areas-674fa39d5248)
- [Self XSS leads to blind XSS and Reflected XSS](https://medium.com/@friendly_/self-xss-leads-to-blind-xss-and-reflected-xss-950b1dc24647)
- [Refltected XSS primagames.com](https://medium.com/@friendly_/reflected-xss-primagames-com-c7a641912626)
- [Stored XSS in gameskinny](https://medium.com/@friendly_/stored-xss-in-gameskinny-aa26c6a6ae40)
- [Blind XSS in Chrome experments Google](https://evanricafort.blogspot.com/2018/08/blind-xss-in-chrome-experiments-google.html)
- [Yahoo two XSSI vulnerabilities chained to steal user information (750$)](https://medium.com/@0xHyde/yahoo-two-xssi-vulnerabilities-chained-to-steal-user-information-750-bounty-e9bc6a41a40a)
- [How I found XSS on amazon](https://medium.com/@codingkarma/how-i-found-xss-on-amazon-f62b50f1c336)
- [A blind XSS in messengers twins](http://omespino.com/write-up-telegram-bug-bounty-whatsapp-n-a-blind-xss-stored-ios-in-messengers-twins-who-really-care-about-your-security/)
- [XSS in microsoft Subdomain](https://medium.com/@sudhanshur705/xss-in-microsoft-subdomain-81c4e46d6631)
- [Persistent XSS at ah.nl](https://medium.com/@jonathanbouman/persistent-xss-at-ah-nl-198fe7b4c781)
- [The 12000 intersection betwenn clickjaking , XSS and DOS](https://samcurry.net/the-12000-intersection-between-clickjacking-xss-and-denial-of-service/)
- [XSS in google collaboratory CSP bypass](https://blog.bentkowski.info/2018/06/xss-in-google-colaboratory-csp-bypass.html)
- [How I found blind XSS in apple](https://medium.com/@tahasmily2013m/how-i-found-blind-xss-in-apple-c890775e745a)
- [Reflected XSS on amazon.com](https://medium.com/@jonathanbouman/reflected-client-xss-amazon-com-7b0d3cec787)
- [How I found XSS in 360totalsecurity](https://medium.com/@tahasmily2013m/i-have-found-vulnerability-in-360totalsecurity-is-reflected-xss-in-3a6bd602bb5a)
- [The 2.5 BTC Stored XSS](https://medium.com/@khaled.hassan/the-2-5-btc-stored-xss-f2f9393417f2)
- [XSS Vulnerability in Netflix ](https://medium.com/@black_b/vulnerability-netflix-cross-site-scripting-xss-d44010142e2c)
- [A story of a UXSS via DOM XSS clickjacking in steam inventory helper](https://thehackerblog.com/steam-fire-and-paste-a-story-of-uxss-via-dom-xss-clickjacking-in-steam-inventory-helper/index.html)
- [How I found XSS via SSRF vulnerability](https://medium.com/@adeshkolte/how-i-found-xss-via-ssrf-vulnerability-adesh-kolte-873b30a6b89f)
- [Searching for XSS found ldap injection](https://www.nc-lp.com/blog/searching-for-xss-found-ldap-injection)
- [how I converted SSRF to XSS in a SSRF vulnerable JIRA](https://medium.com/@D0rkerDevil/how-i-convert-ssrf-to-xss-in-a-ssrf-vulnerable-jira-e9f37ad5b158)
- [Reflected XSS in Yahoo subdomain](https://www.mohamedharon.com/2018/05/reflected-xss-in-hk-yahoo.html)
- [Account takeover and blind XSS](https://blog.witcoat.com/2018/05/30/account-takeover-and-blind-xss-go-pro-get-bugs/)
- [How I found 5 stored XSS on a private program](https://cybristerboy.blogspot.com/2018/05/how-i-found-5-store-xss-on-private.html)
- [Persistent XSS to steal passwords(Paypal)](https://wesecureapp.com/blog/persistent-xss-to-steal-passwords-paypal/)
- [Self XSS + CSRF to stored XSS](https://medium.com/@renwa/self-xss-csrf-to-stored-xss-54f9f423a7f1)
- [Stored XSS in yahoo and subdomains ](https://medium.com/@ozil.hakim/stored-xss-in-yahoo-and-all-subdomains-bbcaa7c3b8d)
- [XSS in microsoft](https://medium.com/@hacker_eth/xss-in-microsoft-7a70416aee75)
- [Blind XSS at customer support panel](https://blog.hx01.me/2018/05/blind-xss-to-customer-support-panel.html)
- [Reflected XSS on stackoverflow](https://medium.com/@newp_th/reflected-xss-on-stack-overflow-b8366a855472)
- [Stored XSS in Yahoo](https://medium.com/@TheShahzada/stored-xss-in-yahoo-b0878ecc97e2)
- [XSS 403 forbidden Bypass](https://medium.com/@nuraalamdipu/xss-403-forbidden-bypass-write-up-e070de52bc06)
- [Turning self XSS into non self XSS via authorization issue at paypal](https://medium.com/@YoKoKho/turning-self-xss-into-non-self-stored-xss-via-authorization-issue-at-paypal-tech-support-and-brand-3046f52ac16b)
- [A story of stored XSS bypass](https://medium.com/@prial261/story-of-a-stored-xss-bypass-26e6659f807b)
- [Mangobaaz hacked XSS to credentials](https://blog.hx01.me/2018/04/mangobaaz-hacked-xss-to-credentials.html)
- [How I got stored XSS using file upload](https://medium.com/@vis_hacker/how-i-got-stored-xss-using-file-upload-5c33e19df51e)
- [Bypassing CSP to abusing XSS filter in edge](https://medium.com/bugbountywriteup/bypass-csp-by-abusing-xss-filter-in-edge-43e9106a9754)
- [XSS to session Hijacking](https://medium.com/@yassergersy/xss-to-session-hijack-6039e11e6a81)
- [Reflected XSS on www.zomato.com](https://www.mohamedharon.com/2018/04/reflected-xss-on-wwwzomatocom-by.html)
- [XSS in subdomain of yahoo](https://www.mohamedharon.com/2018/03/xss-in-subdomain-httpsyefgrantsyahoocom.html)
- [XSS in yahoo.net subdomain ](https://www.mohamedharon.com/2018/03/xss-in-sportstwcampaignyahoonet.html)
- [Reflected XSS moongaloop swf version 62x](https://www.mohamedharon.com/2018/03/reflected-xss-moogaloop-swf-version-62x.html)
- [Google adwords 3133.7 Stored XSS](https://medium.com/@Alra3ees/google-adwords-3133-7-stored-xss-27bb083b8d27)
- [How I found a surprising XSS vulnerability on oracle netsuite](https://medium.com/bug-bounty-hunting/how-i-found-a-surprising-xss-vulnerability-on-oracle-netsuite-2d48b7fcf0c8)
- [Stored XSS on snapchat](https://medium.com/@mrityunjoy/stored-xss-on-snapchat-5d704131d8fd)
- [How I was able to bypass XSS protection on h1 private program](https://blog.securitybreached.org/2018/02/02/how-i-was-able-to-bypass-xss-protection-on-hackerones-private-program/)
- [Reflected XSS possible](https://www.mohamedharon.com/2018/01/reflected-xss-possible-server-side.html)
- [XSS via angularjs template injection hostinger](https://blog.ibrahimdraidia.com/xss-via-angularjs-template-injection_hostinger/)
- [Microsoft follow feature XSS (CVE-2017-8514)](https://medium.com/@adeshkolte/microsoft-sharepoints-follow-feature-xss-cve-2017-8514-adesh-kolte-d78d701cd064)
- [XSS protection bypass made my quickest bounty ever](https://medium.com/@Skylinearafat/xss-protection-bypass-made-my-quickest-bounty-ever-f4fd970c9116)
- [Taking note XSS to RCE in the simplenote electron client](https://ysx.me.uk/taking-note-xss-to-rce-in-the-simplenote-electron-client/)
- [VMWARE official vcdx reflected XSS](https://medium.com/@honcbb/vmware-official-vcdx-reflected-xss-90e69a3c35e1)
- [How I pwned a company using IDOR and Blind XSS](https://www.ansariosama.com/2017/11/how-i-pwned-company-using-idor-blind-xss.html)
- [From Recon to DOM based XSS](https://medium.com/@abdelfattahibrahim/from-recon-to-dom-based-xss-f279602a14cf)
- [Local file read via XSS ](http://www.noob.ninja/2017/11/local-file-read-via-xss-in-dynamically.html)
- [Non persistent XSS at microsoft](https://medium.com/@adeshkolte/non-persistent-xss-at-microsoft-adesh-kolte-ad36b1b4a325)
- [A Stored XSS in google (double kill)](https://ysx.me.uk/app-maker-and-colaboratory-a-stored-google-xss-double-bill/)
- [Filter bypass to Reflected XSS on finance.yahoo.com (mobile version)](https://medium.com/@saamux/filter-bypass-to-reflected-xss-on-https-finance-yahoo-com-mobile-version-22b854327b27)
- [900$ XSS in yahoo : recon wins](https://medium.com/bugbountywriteup/900-xss-in-yahoo-recon-wins-65ee6d4bfcbd)
- [How I bypassed practos firewall and triggered an XSS vulnerability](https://medium.com/bugbountywriteup/how-i-bypassed-practos-firewall-and-triggered-a-xss-b30164a8f1dc)
- [Stored XSS to full information disclosure](https://guptashubham.com/stored-xss-to-full-information-disclosure/)
- [Story of parameter specific XSS](http://www.noob.ninja/2017/09/story-of-parameter-specific-xss.html)
- [Chaining self XSS with UI redressing leading to session hijacking](https://medium.com/bugbountywriteup/chaining-self-xss-with-ui-redressing-is-leading-to-session-hijacking-pwn-users-like-a-boss-efb46249cd14)
- [Stored XSS with arbitrary cookie installation](https://medium.com/@arbazhussain/stored-xss-with-arbitrary-cookie-installation-567931433c7f)
- [Reflective XSS and Open redirect on indeed.com subdomain](https://medium.com/@SyntaxError4/reflective-xss-and-open-redirect-on-indeed-com-subdomain-b4ab40e40c83)
- [How I found reflected XSS on Yahoo subdomain](https://medium.com/@SyntaxError4/how-i-found-reflective-xss-in-yahoo-subdomain-3ad4831b386e)
- [Dont just alert(1) because XSS is more fun](https://medium.com/@armaanpathan/dont-just-alert-1-because-xss-is-for-fun-f88cfb88d5b9)
- [UBER XSS by helpe of KNOXSS](https://medium.com/@Alra3ees/my-write-up-about-uber-cross-site-scripting-by-help-of-knoxss-b1b56f8d090)
- [Reflected XSS in Yahoo](https://medium.com/@TheShahzada/reflected-xss-in-yahoo-6e2b6b177448)
- [Reflected XSS on ww.yahoo.com](https://medium.com/@saamux/reflected-xss-on-www-yahoo-com-9b1857cecb8c)
- [XSS because of wrong content type header](https://bugbaba.blogspot.com/2017/08/xss-because-of-wrong-content-type-header.html)

## CSP

- [https://hackerone.com/reports/153666](https://hackerone.com/reports/153666)

- [https://hackerone.com/reports/225833](https://hackerone.com/reports/225833)

- [https://hackerone.com/reports/244766](https://hackerone.com/reports/244766)

- [https://hackerone.com/reports/244724](https://hackerone.com/reports/244724)

## SQLI

- [**SQL injection in Harvard subdomain**](https://noob3xploiter.medium.com/sql-injection-in-harvard-subdomain-be67a5dbf664)
- [**sqli in HackerOne (crit)**](https://hackerone.com/reports/363815)
- [**ssrf to sqli**](https://caesarevan23.medium.com/ssrf-external-service-interaction-for-find-real-ip-cloudflare-and-leads-to-sql-injection-c22c02243299)
- [https://hackerone.com/reports/519631](https://hackerone.com/reports/519631)
- [https://hackerone.com/reports/419017](https://hackerone.com/reports/419017)
- [https://ahussam.me/Blind-sqli-Hootsuite/](https://ahussam.me/Blind-sqli-Hootsuite/)
- [https://bitquark.co.uk/blog/2014/02/23/tesla_motors_blind_sql_injection](https://bitquark.co.uk/blog/2014/02/23/tesla_motors_blind_sql_injection) **' + sleep(10) + '**
- [https://bitquark.co.uk/blog/2014/08/31/popping_a_shell_on_the_oculus_developer_portal](https://bitquark.co.uk/blog/2014/08/31/popping_a_shell_on_the_oculus_developer_portal)
- [https://blog.parthmalhotra.com/pwning-child-company-to-get-access-to-parentcompanys-slack-team/](https://blog.parthmalhotra.com/pwning-child-company-to-get-access-to-parentcompanys-slack-team/)
- [https://blog.redforce.io/sql-injection-in-insert-update-query-without-comma/](https://blog.redforce.io/sql-injection-in-insert-update-query-without-comma/)
- [https://blog.redforce.io/sqli-extracting-data-without-knowing-columns-names/](https://blog.redforce.io/sqli-extracting-data-without-knowing-columns-names/)
- [https://blog.securitybreached.org/2018/09/08/sqli-bootcampnutanix-com-bug-bounty-poc/](https://blog.securitybreached.org/2018/09/08/sqli-bootcampnutanix-com-bug-bounty-poc/)
- [https://blog.securitybreached.org/2018/09/09/zol-zimbabwe-authbypass-sqli-xss/](https://blog.securitybreached.org/2018/09/09/zol-zimbabwe-authbypass-sqli-xss/)
- [https://blog.securitybreached.org/2018/09/10/sqli-login-bypass-autotraders/](https://blog.securitybreached.org/2018/09/10/sqli-login-bypass-autotraders/)
- [https://medium.com/@St00rm/sql-injection-via-stopping-the-redirection-to-a-login-page-52b0792d5592](https://medium.com/@St00rm/sql-injection-via-stopping-the-redirection-to-a-login-page-52b0792d5592)
- [https://buer.haus/2015/01/15/yahoo-root-access-sql-injection-tw-yahoo-com/](https://buer.haus/2015/01/15/yahoo-root-access-sql-injection-tw-yahoo-com/)
- [https://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html](https://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html)
- [https://jspin.re/fileupload-blind-sqli/](https://jspin.re/fileupload-blind-sqli/)
- [https://renaudmarti.net/posts/first-bug-bounty-submission/](https://renaudmarti.net/posts/first-bug-bounty-submission/)
- [https://twitter.com/0x01alka/status/816403077074976768](https://twitter.com/0x01alka/status/816403077074976768)
- [https://www.youtube.com/watch?v=8gm1z9bPJ7w](https://www.youtube.com/watch?v=8gm1z9bPJ7w)
- [https://blog.noob.ninja/exploiting-a-tricky-blind-sql-injection-inside-limit-clause/](https://blog.noob.ninja/exploiting-a-tricky-blind-sql-injection-inside-limit-clause/)
- [https://www.rcesecurity.com/2019/09/H1-4420-From-Quiz-to-Admin-Chaining-Two-0-Days-to-Compromise-an-Uber-Wordpress/](https://www.rcesecurity.com/2019/09/H1-4420-From-Quiz-to-Admin-Chaining-Two-0-Days-to-Compromise-an-Uber-Wordpress/)
- [https://NathOnSecurity.medium.com/hacking-the-nhs-for-fun-and-no-profit-90931029dcb4](https://nathonsecurity.medium.com/hacking-the-nhs-for-fun-and-no-profit-90931029dcb4)
- [https://abidafahd.medium.com/hacking-makes-me-forget-my-pain-b04bf51d0407](https://abidafahd.medium.com/hacking-makes-me-forget-my-pain-b04bf51d0407)
- [https://adeshkolte.medium.com/sql-injection-vulnerability-in-university-of-cambridge-b4c8d0381e1](https://adeshkolte.medium.com/sql-injection-vulnerability-in-university-of-cambridge-b4c8d0381e1)
- [https://ariffadhlullah2310.medium.com/sql-injection-bug-bounty-110e92e71ec3](https://ariffadhlullah2310.medium.com/sql-injection-bug-bounty-110e92e71ec3)
- [https://bathinivijaysimhareddy.medium.com/shodan-is-your-friend-if-you-lose-him-you-will-lose-many-657d07472f75](https://bathinivijaysimhareddy.medium.com/shodan-is-your-friend-if-you-lose-him-you-will-lose-many-657d07472f75)
- [https://frostnull.medium.com/sql-injection-through-user-agent-44a1150f6888](https://frostnull.medium.com/sql-injection-through-user-agent-44a1150f6888)
- [https://nuraalamdipu.medium.com/union-based-sql-injection-write-up-a-private-company-site-273f89a49ed9](https://nuraalamdipu.medium.com/union-based-sql-injection-write-up-a-private-company-site-273f89a49ed9)
- [https://orthonviper.medium.com/sql-injection-for-50-bounty-but-still-worth-reading-468442c1cc1a](https://orthonviper.medium.com/sql-injection-for-50-bounty-but-still-worth-reading-468442c1cc1a)
- [https://rojanrijal.medium.com/source-code-analysis-in-ysurvey-luminate-bug-c86dc29b70c4](https://rojanrijal.medium.com/source-code-analysis-in-ysurvey-luminate-bug-c86dc29b70c4)
- [https://saadahmedx.medium.com/sql-injection-c87a390afdd3](https://saadahmedx.medium.com/sql-injection-c87a390afdd3)
- [https://saadahmedx.medium.com/sql-injection-c87a390afdd3](https://saadahmedx.medium.com/sql-injection-c87a390afdd3)
- [https://infosecwriteups.com/a-five-minute-sql-i-16ab75b20fe4](https://infosecwriteups.com/a-five-minute-sql-i-16ab75b20fe4)
- [https://medium.com/sud0root/bug-bounty-writeups-exploiting-sql-injection-vulnerability-20b019553716](https://medium.com/sud0root/bug-bounty-writeups-exploiting-sql-injection-vulnerability-20b019553716)
- [https://hackerone.com/reports/1224660](https://hackerone.com/reports/1224660)
- [https://hackerone.com/reports/1109311](https://hackerone.com/reports/1109311)
- [https://hackerone.com/reports/374027](https://hackerone.com/reports/374027)
- [https://hackerone.com/reports/9921](https://hackerone.com/reports/9921)
- [https://hackerone.com/reports/319279](https://hackerone.com/reports/319279)
- [https://hackerone.com/reports/1069531](https://hackerone.com/reports/1069531)
- [https://hackerone.com/reports/924855](https://hackerone.com/reports/924855)
- [https://hackerone.com/reports/1039315](https://hackerone.com/reports/1039315)
- [https://hackerone.com/reports/786044](https://hackerone.com/reports/786044)
- [https://hackerone.com/reports/297478](https://hackerone.com/reports/297478)
- [https://hackerone.com/reports/295841](https://hackerone.com/reports/295841)


## Open Redirect


- [[Report-226408] Open Redirect on Shopify](https://hackerone.com/reports/226408)
- [[Report-211213] Open Redirect on Nextcloud](https://hackerone.com/reports/211213): 
- [https://xmpp.nextcloud.com///;@www.google.com](https://xmpp.nextcloud.com///;@www.google.com)
- [[Report-246897] Open Redirect on Twitter](https://hackerone.com/reports/246897): Eldeeb
- [[Report-103772] Open Redirect on Shopify](https://hackerone.com/reports/103772): .np
- [[Report-309058] Open Redirect on Wordpress](https://hackerone.com/reports/309058): @
- [[Report-260744] Open Redirect and XSS on Twitter](https://hackerone.com/reports/260744): https://dev.twitter.com/https:/%5cblackfan.ru/
- [[Report-320376] Open Redirect on HackerOne](https://hackerone.com/reports/320376): after index.php/XYZ
- [[Report-111968] Interstitial redirect bypass / Open Redirect on HackerOne Zendesk Session](https://hackerone.com/reports/111968)
- [[Report-244721] Open Redirect on Mail.Ru](https://hackerone.com/reports/244721)
- [[Report-236599] Open Redirect on ExpressionEngine](https://hackerone.com/reports/236599)
- [[Report-299403] Open Redirect on HackerOne](https://hackerone.com/reports/299403): RTLO
- [[Report-239503] Open Redirect & Information Disclosure on HackerOne](https://hackerone.com/reports/239503)
- [[Report-210875] Open Redirect via Host Header](https://hackerone.com/reports/210875)
- [[Report-119236] Open Redirect on Uber](https://hackerone.com/reports/119236): IP address to a single number
- [[Report-126203] Open Redirect on Uber](https://hackerone.com/reports/126203)
- [[Report-144525] Open Redirect bypass on New Relic](https://hackerone.com/reports/144525)
- [[Report-104087] Open Redirect bypass using svg on Slack](https://hackerone.com/reports/104087)
- [[Report-179568] Open Redirect via window.opener on Open-Xchange](https://hackerone.com/reports/179568)
- [Open Redirect to RCE on Google Hangouts Electron app](https://blog.bentkowski.info/2018/07/vulnerability-in-hangouts-chat-aka-how.html) & [RCE Tweet](https://twitter.com/mattaustin/status/1022648925902200832)
- Look for “Open redirect” (with Ctrl+f) in our [List of bug bounty writeups](https://pentester.land/list-of-bug-bounty-writeups.html)


## IDOR


1. [**IDOR in HackerOne**](https://n1ghtmar3.medium.com/how-i-found-my-first-idor-in-hackerone-5d5f17bb431) (Medium)
2. [**IDOR with Geolocation data not stripped from images**](https://hackerone.com/reports/906907) (h1)
3. [**IDOR in HackerOne**](https://n1ghtmar3.medium.com/how-i-found-my-first-idor-in-hackerone-5d5f17bb431) (Medium)
4. [**https://hackerone.com/reports/287789**](https://hackerone.com/reports/287789)
5. **https://appsecure.security/blog/how-i-could-have-hacked-your-uber-account**
6. [**https://footstep.ninja/posts/idor-via-websockets/**](https://footstep.ninja/posts/idor-via-websockets/)
7. [**https://georgeosterweil.com/2019-02-20-fbctf-idor/**](https://georgeosterweil.com/2019-02-20-fbctf-idor/)
8. [**Disclosing privately shared gaming clips of any user**](https://bugreader.com/rony@disclosing-privately-shared-gaming-clips-of-any-user-128)
9. [**Adding anyone including non-friend and blocked people as co-host in personal event!**](https://bugreader.com/binit@adding-anyone-including-non-friend-and-blocked-people-as-co-host-in-personal-event-181)
10. [**Page analyst could view job application details**](https://bugreader.com/rony@page-analyst-could-view-job-application-details-213)
11. [**Deleting Anyone's Video Poll**](https://bugreader.com/testgrounds@deleting-anyones-video-poll-175)
12. [**IDOR bug to See hidden slowvote of any user even when you dont have access right**](https://hackerone.com/reports/661978)
13. [**IDOR allow to extract all registered email**](https://hackerone.com/reports/302485)
14. [**Another image removal vulnerability on Facebook**](https://blog.darabi.me/2020/06/image-removal-vulnerability-on-facebook.html)
15. [**Gsuite Hangouts Chat 5k IDOR**](https://secreltyhiddenwriteups.blogspot.com/2018/07/gsuite-hangouts-chat-5k-idor.html)
16. [**How I pwned a company using IDOR and Blind XSS**](https://www.ansariosama.com/2017/11/how-i-pwned-company-using-idor-blind-xss.html)
17. [**Disclose Private Dashboard Chart's name and data in Facebook Analytics**](https://bugreader.com/jubabaghdad@disclose-private-dashboard-charts-name-and-data-in-facebook-analytics-184)
18. [**IDOR when editing users leads to Account Takeover without User Interaction at CrowdSignal**](https://hackerone.com/reports/915114) to Automattic - 177 upvotes, $650
19. [**IDOR leads to Edit Anyone's Blogs / Websites**](https://hackerone.com/reports/974222) to Automattic - 125 upvotes, $200
20. [**IDOR and statistics leakage in Orders**](https://hackerone.com/reports/544329) to Twitter - 108 upvotes, $289
21. [**IDOR in https://3d.cs.money/**](https://hackerone.com/reports/990878) to CS Money - 107 upvotes, $200
22. [**IDOR leading to downloading of any attachment**](https://hackerone.com/reports/668439) to BCM Messenger - 101 upvotes, $100
23. [**IDOR when moving contents at CrowdSignal**](https://hackerone.com/reports/915127) to Automattic - 75 upvotes, $550
24. [**http://galnagli.com/DoD_IDOR/**](http://galnagli.com/DoD_IDOR/)
25. [**https://hackerone.com/reports/230328**](https://hackerone.com/reports/230328)
26. [**IDOR to delete images from other stores**](https://hackerone.com/reports/404797) to Zomato - 48 upvotes, $600
27. [**IDOR in marketing calendar tool](https://hackerone.com/reports/797685) to Semrush - 48 upvotes, $500
28. [**IDOR when creating App on [platform.streamlabs.com/api/v1/store/whitelist] with user_id field**](https://hackerone.com/reports/983070) to Logitech - 47 upvotes, $100
29. [**IDOR with Geolocation data not stripped from images](https://hackerone.com/reports/906907) to IRCCloud - 36 upvotes, $200
30. [**IDOR in semrush academy**](https://hackerone.com/reports/783708) to Semrush - 35 upvotes, $505
31. [**Idor on the DELETE /comments/**](https://hackerone.com/reports/861849) to RGhost - 29 upvotes, $0
32. [**[NR Insights] IDOR - Modify the filter settings for any NR Insights dashboard through internal_api endpoint**](https://hackerone.com/reports/459443) to New Relic - 26 upvotes, $2500
33. [**IDOR in editing courses**](https://hackerone.com/reports/227522) to Maximum - 26 upvotes, $300
34. [**IDOR when editing email leads to Account Takeover on Atavist**](https://hackerone.com/reports/950881) to Automattic - 23 upvotes, $150
35. [**IDOR to view User Order Information**](https://hackerone.com/reports/287789) to BOHEMIA INTERACTIVE a.s. - 21 upvotes, $130
36. [**IDOR on deleting drafts on https://apps.topcoder.com/wiki/users/viewmydrafts.action via discardDraftId parameter**](https://hackerone.com/reports/868590) to Topcoder - 21 upvotes, $0
37. [**IDOR - Deleting other user's signature via /appsuite/api/snippet?action=update (although an error is thrown)**](https://hackerone.com/reports/199321) to Open-Xchange - 19 upvotes, $300

## HTTP Parameter Pollution

1. https://andresriancho.com/recaptcha-bypass-via-http-parameter-pollution/
2. [https://blog.mert.ninja/twitter-hpp-vulnerability/](https://blog.mert.ninja/twitter-hpp-vulnerability/)
3. [https://blog.securitybreached.org/2020/01/26/improper-input-validation-add-custom-text-and-urls-in-sms-send-by-snapchat-bug-bounty-poc/](https://blog.securitybreached.org/2020/01/26/improper-input-validation-add-custom-text-and-urls-in-sms-send-by-snapchat-bug-bounty-poc/)
4. https://medium.com/@bathinivijaysimhareddy/tale-of-account-takeovers-part-1-b24e1f3c3187
5. [https://logicbomb.medium.com/bugbounty-compromising-user-account-how-i-was-able-to-compromise-user-account-via-http-4288068b901f](https://logicbomb.medium.com/bugbounty-compromising-user-account-how-i-was-able-to-compromise-user-account-via-http-4288068b901f)
6. [https://medium.com/@momenbasel/from-parameter-pollution-to-xss-d095e13be060](https://medium.com/@momenbasel/from-parameter-pollution-to-xss-d095e13be060)
7. [https://medium.com/@sivakrishnasamireddi/how-i-earned-60k-from-private-program-71bd51554490](https://medium.com/@sivakrishnasamireddi/how-i-earned-60k-from-private-program-71bd51554490)
8. [https://hackerone.com/reports/105953](https://hackerone.com/reports/105953)

## Information Disc

1. [https://blog.carnal0wnage.com/2019/01/i-found-gcp-service-account-tokennow.html](https://blog.carnal0wnage.com/2019/01/i-found-gcp-service-account-tokennow.html) **GCP**
2. [https://blog.carnal0wnage.com/2020/03/what-is-your-gcp-infra-worthabout-700.html](https://blog.carnal0wnage.com/2020/03/what-is-your-gcp-infra-worthabout-700.html) **GCP**
3. [https://blog.assetnote.io/bug-bounty/2019/04/23/getting-access-zendesk-gcp/](https://blog.assetnote.io/bug-bounty/2019/04/23/getting-access-zendesk-gcp/) **GCP**
4. [https://aaronesau.com/blog/posts/5](https://aaronesau.com/blog/posts/5) **Debug**
5. [https://addictivehackers.blogspot.com/2019/08/from-github-recon-to-account-takeover.html](https://addictivehackers.blogspot.com/2019/08/from-github-recon-to-account-takeover.html) **ATO**
6. [https://medium.com/@pratiky054/graphql-bug-to-steal-anyones-address-fc34f0374417](https://medium.com/@pratiky054/graphql-bug-to-steal-anyones-address-fc34f0374417) **GraphQl**
7. [https://blog.usejournal.com/how-recon-helped-samsung-protect-their-production-repositories-of-samsungtv-ecommerce-estores-4c51d6ec4fdd](https://blog.usejournal.com/how-recon-helped-samsung-protect-their-production-repositories-of-samsungtv-ecommerce-estores-4c51d6ec4fdd) **IMPORTANT**
8. [https://web.archive.org/web/20191204223739/https://daleys.space/writeup/0day/2019/09/09/verizon-leak.html](https://web.archive.org/web/20191204223739/https://daleys.space/writeup/0day/2019/09/09/verizon-leak.html)
9. [https://blog.evanricafort.com/2019/07/business-logic-plex-tv.html](https://blog.evanricafort.com/2019/07/business-logic-plex-tv.html)
10. [https://flex0geek.blogspot.com/2019/10/leak-can-i-take-user-information-please.html](https://flex0geek.blogspot.com/2019/10/leak-can-i-take-user-information-please.html)
11. [https://hackernoon.com/how-i-could-have-hacked-all-uber-accounts-rtzl3z72](https://hackernoon.com/how-i-could-have-hacked-all-uber-accounts-rtzl3z72)
12. [https://medium.com/@D0rkerDevil/how-i-found-credential-enriched-redis-dump-2b9e808024c4](https://medium.com/@D0rkerDevil/how-i-found-credential-enriched-redis-dump-2b9e808024c4)
13. [https://medium.com/@Skylinearafat/how-to-look-for-js-files-vulnerability-for-fun-and-profit-78bfdfbd6731](https://medium.com/@Skylinearafat/how-to-look-for-js-files-vulnerability-for-fun-and-profit-78bfdfbd6731)
14. [https://medium.com/@cc1h2e1/unauthorized-access-to-all-user-information-leaks-5db95746aecf](https://medium.com/@cc1h2e1/unauthorized-access-to-all-user-information-leaks-5db95746aecf)
15. [https://medium.com/@harrmahar/how-i-get-my-first-p1-sensitive-information-disclosure-using-wpscan-c2fba00ac361](https://medium.com/@harrmahar/how-i-get-my-first-p1-sensitive-information-disclosure-using-wpscan-c2fba00ac361)
16. [https://hbothra22.medium.com/recon-to-sensitive-information-disclosure-in-minutes-503fc7ccdf0b](https://hbothra22.medium.com/recon-to-sensitive-information-disclosure-in-minutes-503fc7ccdf0b)

## CORS

1. [CORS bug on google's 404 page (rewarded)](https://medium.com/@jayateerthag/cors-bug-on-googles-404-page-rewarded-2163d58d3c8b) ✅
2. [CORS misconfiguration leading to private information disclosure](https://medium.com/@sasaxxx777/cors-misconfiguration-leading-to-private-information-disclosure-3034cfcb4b93) ✅
3. [CORS misconfiguration account takeover out of scope to grab items in scope](https://medium.com/@mashoud1122/cors-misconfiguration-account-takeover-out-of-scope-to-grab-items-in-scope-66d9d18c7a46) ✅
4. [Chrome CORS](https://blog.bi.tk/chrome-cors/) ✅
5. [Bypassing CORS](https://medium.com/@saadahmedx/bypassing-cors-13e46987a45b) ✅
6. [An unexploited CORS misconfiguration reflects further issues](https://smaranchand.com.np/2019/05/an-unexploited-cors-misconfiguration-reflecting-further-issues/) ✅
7. [Think outside the scope of advanced cors exploitation techniques](https://medium.com/@sandh0t/think-outside-the-scope-advanced-cors-exploitation-techniques-dad019c68397) ✅ **ADVANCED**
8. [A simple CORS misconfiguration leaked private post of Twitter Facebook Instagram](https://medium.com/@nahoragg/a-simple-cors-misconfig-leaked-private-post-of-twitter-facebook-instagram-5f1a634feb9d) ✅
9. [Exploiting CORS misconfiguration](https://bugbaba.blogspot.com/2018/02/exploiting-cors-miss-configuration.html) ✅
10. [http://www.geekboy.ninja/blog/exploiting-misconfigured-cors-via-wildcard-subdomains/](http://www.geekboy.ninja/blog/exploiting-misconfigured-cors-via-wildcard-subdomains/) ✅
11. [Exploiting insecure CORS API api.artsy.net](https://blog.securitybreached.org/2017/10/10/exploiting-insecure-cross-origin-resource-sharing-cors-api-artsy-net) ✅
12. [Pre domain wildcard CORS exploitation](https://medium.com/bugbountywriteup/pre-domain-wildcard-cors-exploitation-2d6ac1d4bd30) ✅
13. [Exploiting misconfigured CORS on popular BTC site](https://medium.com/@arbazhussain/exploiting-misconfigured-cors-on-popular-btc-site-2aedfff906f6) ✅
14. [Cross-origin resource sharing misconfig | steal user information - bughunterboy (bughunterboy)](https://hackerone.com/reports/235200) ✅
15. [[██████] Cross-origin resource sharing misconfiguration (CORS) - Vadim (jarvis7)](https://hackerone.com/reports/470298) ✅
16. `[https://hackerone.com/reports/758785](https://hackerone.com/reports/758785)` ✅
17. `[https://hackerone.com/reports/426165](https://hackerone.com/reports/426165)` ✅
18. `[https://hackerone.com/reports/896093](https://hackerone.com/reports/896093)` ✅
19. `[https://hackerone.com/reports/733017](https://hackerone.com/reports/733017)` ✅
20. `[https://hackerone.com/reports/768151](https://hackerone.com/reports/768151)` ✅
21. `[https://hackerone.com/reports/688567](https://hackerone.com/reports/688567)` ✅

## SOP

1. [https://enumerated.wordpress.com/2019/12/24/sop-bypass-via-browser-cache/](https://enumerated.wordpress.com/2019/12/24/sop-bypass-via-browser-cache/) ✅
2. https://medium.com/@raushanraj_65039/google-sites-and-exploiting-same-origin-policy-d400bf569964 ✅
3. https://medium.com/bugbountywriteup/sop-bypass-ecae7f4a5c00 ✅
4. https://www.netsparker.com/blog/web-security/stealing-local-files-with-simple-html-file/ ✅
5. [https://medium.com/swlh/hacking-the-same-origin-policy-f9f49ad592fc](https://medium.com/swlh/hacking-the-same-origin-policy-f9f49ad592fc)
6. [https://hackerone.com/reports/244504](https://hackerone.com/reports/244504) ✅
7. [https://hackerone.com/reports/103787](https://hackerone.com/reports/103787)
8. [https://hackerone.com/reports/761726](https://hackerone.com/reports/761726) ✅

## XXE

1. [https://web.archive.org/web/20200724124912/https://blog.0xatul.me/posts/2020/02/external-xml-entity-via-file-upload-svg/](https://web.archive.org/web/20200724124912/https://blog.0xatul.me/posts/2020/02/external-xml-entity-via-file-upload-svg/)
2. [https://httpsonly.blogspot.com/2017/01/0day-writeup-xxe-in-ubercom.html](https://httpsonly.blogspot.com/2017/01/0day-writeup-xxe-in-ubercom.html)
3. [https://medium.com/@zain.sabahat/an-interesting-xxe-in-sap-8b35fec6ef33](https://medium.com/@zain.sabahat/an-interesting-xxe-in-sap-8b35fec6ef33)
4. [https://medium.com/bugbountywriteup/bug-bounty-fastmail-feeda67905f5](https://infosecwriteups.com/bug-bounty-fastmail-feeda67905f5)
5. [https://mohemiv.com/all/exploiting-xxe-with-local-dtd-files/](https://mohemiv.com/all/exploiting-xxe-with-local-dtd-files/)
6. [https://www.corben.io/XSS-to-XXE-in-Prince/](https://www.corben.io/XSS-to-XXE-in-Prince/)
7. [https://web.archive.org/web/20210122093352/https://www.guptashubham.com/multiple-vulnerabilities-in-oracle-ebs/](https://web.archive.org/web/20210122093352/https://www.guptashubham.com/multiple-vulnerabilities-in-oracle-ebs/)
8. [https://hackerone.com/reports/500515](https://hackerone.com/reports/500515)
9. [https://hackerone.com/reports/248668](https://hackerone.com/reports/248668)
10. https://honoki.net/2018/12/12/from-blind-xxe-to-root-level-file-read-access/
11. [http://lab.onsec.ru/2014/06/xxe-oob-exploitation-at-java-17.html](http://lab.onsec.ru/2014/06/xxe-oob-exploitation-at-java-17.html)
12. https://mahmoudsec.blogspot.com/2019/08/exploiting-out-of-band-xxe-using.html
13. [https://blog.niksthehacker.com/oob-xxe-in-prizmdoc-cve-2018-15805-dfb1e474345c](https://blog.niksthehacker.com/oob-xxe-in-prizmdoc-cve-2018-15805-dfb1e474345c)
14. [https://infosecwriteups.com/soap-based-unauthenticated-out-of-band-xml-external-entity-oob-xxe-in-a-help-desk-software-c27a6abf182a](https://infosecwriteups.com/soap-based-unauthenticated-out-of-band-xml-external-entity-oob-xxe-in-a-help-desk-software-c27a6abf182a)
15. [https://www.protector47.com/2020/03/08/how-i-loose-5005-in-a-day-dos-billion-laugh-attack-xxe/](https://www.protector47.com/2020/03/08/how-i-loose-5005-in-a-day-dos-billion-laugh-attack-xxe/)
16. [https://r00thunt.com/2018/10/05/blind-xml-external-entities-out-of-band-channel-vulnerability-paypal-case-study/](https://r00thunt.com/2018/10/05/blind-xml-external-entities-out-of-band-channel-vulnerability-paypal-case-study/)
17. [https://github.com/0xKourama/hackerone-reports/blob/master/tops_by_bug_type/TOPXXE.md](https://github.com/0xKourama/hackerone-reports/blob/master/tops_by_bug_type/TOPXXE.md)

BLIND - OOB ❌

1. [https://spaceraccoon.dev/a-tale-of-two-formats-exploiting-insecure-xml-and-zip-file-parsers-to-create-a](https://spaceraccoon.dev/a-tale-of-two-formats-exploiting-insecure-xml-and-zip-file-parsers-to-create-a)
2. https://www.coalfire.com/The-Coalfire-Blog/June-2018/How-I-Found-CVE-2018-8819-Out-of-Band-(OOB)-XXE?feed=blogs
3. [https://hackerone.com/reports/334488](https://hackerone.com/reports/334488)
4. [https://hackerone.com/reports/395296](https://hackerone.com/reports/395296)
5. [https://hackerone.com/reports/312543](https://hackerone.com/reports/312543)

## DOS

1. [Long String DOS](https://medium.com/@shahjerry33/long-string-dos-6ba8ceab3aa0)
2. [Banner grabbing to DOS and memory corruption](https://medium.com/bugbountywriteup/banner-grabbing-to-dos-and-memory-corruption-2442b1c25bbb)
3. [profile-picture name parameter with large value lead to DoS for other users and programs on the platform](https://hackerone.com/reports/764434) to HackerOne - 455 upvotes, $2500
4. [xmlrpc.php FILE IS enable it will used for Bruteforce attack and Denial of Service(DoS)](https://hackerone.com/reports/752073) to Nord Security - 146 upvotes, $200
5. [xmlrpc.php FILE IS enable it will be used for brute force attack and denial of service](https://hackerone.com/reports/325040) to LocalTapiola - 20 upvotes, $315
6. [DoS on the Issue page by exploiting Mermaid.](https://hackerone.com/reports/470067) to GitLab - 137 upvotes, $3000
7. [character limitation bypass can lead to DoS on Twitter App and 500 Internal Server Error](https://hackerone.com/reports/819088) to Twitter - 136 upvotes, $560
8. [Permanent DoS with one click.](https://hackerone.com/reports/975827) to Automattic - 123 upvotes, $250
9. [a very long name in hey.com can prevent anyone from accessing their contacts and probably can cause denial of service](https://hackerone.com/reports/1018037) to Basecamp - 116 upvotes, $1000
10. [ActiveStorage throws exception when using whitespace as filename, may lead to denial of service of multiple pages](https://hackerone.com/reports/713407) to HackerOne - 102 upvotes, $2500
11. [Denial of Service | twitter.com & mobile.twitter.com](https://hackerone.com/reports/903740) to Twitter - 85 upvotes, $1120
12. [DoS attack via comment on Issue](https://hackerone.com/reports/557154) to GitLab - 77 upvotes, $1000
13. [DoS of https://nordvpn.com/ via CVE-2018-6389 exploitation](https://hackerone.com/reports/752010) to Nord Security - 70 upvotes, $200
14. [Denial of Service [Chrome]](https://hackerone.com/reports/921286) to Twitter - 64 upvotes, $560
15. [DoS: type confusion in mrb_no_method_error](https://hackerone.com/reports/181871) to Shopify-scripts - 60 upvotes, $20000
16. [[api.tumblr.com] Denial of Service by cookies manipulation](https://hackerone.com/reports/1005421) to Automatic - 51 upvotes, $200
17. [Application DOS via specially crafted payload on 3d.cs.money](https://hackerone.com/reports/993582) to CS Money - 35 upvotes, $200
18. [Pixel Flood Attack leads to Application level DoS](https://hackerone.com/reports/970760) to CS Money - 20 upvotes, $200
19. [lack of input validation that can lead Denial of Service (DOS)](https://hackerone.com/reports/768677) to Twitter - 17 upvotes, $560

## Html Injection


1. https://evanricafort.blogspot.com/2019/07/html-injection-in-clause-email.html
2. https://evanricafort.blogspot.com/2019/12/html-injection-to-xss-bypass-in.html
3. [https://footstep.ninja/posts/html-injection-in-email/](https://footstep.ninja/posts/html-injection-in-email/)
4. https://medium.com/@armaanpathan/chain-the-vulnerabilities-and-take-your-report-impact-on-the-moon-csrf-to-html-injection-which-608fa6e74236
5. https://medium.com/@irounakdhadiwal999/stored-iframe-injection-csrf-account-takeover-42c93ad13f5d
6. [https://medium.com/@know.0nix/hunting-good-bugs-with-only-html-d8fd40d17b38](https://medium.com/@know.0nix/hunting-good-bugs-with-only-html-d8fd40d17b38)
7. [https://infosecwriteups.com/unauthenticated-account-takeover-through-http-leak-33386bb0ba0b](https://infosecwriteups.com/unauthenticated-account-takeover-through-http-leak-33386bb0ba0b)
8. [https://medium.com/@pratiky054/html-injection-unique-exploitation-a5c3d4e6fed8](https://medium.com/@pratiky054/html-injection-unique-exploitation-a5c3d4e6fed8)
9. [https://bugdisclose.medium.com/how-i-caught-multiple-vulnerabilities-in-udemy-com-14012a8a1421](https://bugdisclose.medium.com/how-i-caught-multiple-vulnerabilities-in-udemy-com-14012a8a1421)
10. [https://medium.com/cyberverse/got-easiest-bounty-with-html-injection-via-email-confirmation-b1b10575a105](https://medium.com/cyberverse/got-easiest-bounty-with-html-injection-via-email-confirmation-b1b10575a105)

## S3


[https://www.youtube.com/watch?v=_x5VKuFjvrk](https://www.youtube.com/watch?v=_x5VKuFjvrk)

[https://book.hacktricks.xyz/external-recon-methodology#assets-discoveries](https://book.hacktricks.xyz/external-recon-methodology#assets-discoveries)

`[https://hackerone.com/reports/507097](https://hackerone.com/reports/507097)` ✅

`[https://hackerone.com/reports/128088](https://hackerone.com/reports/128088)` ✅

`[https://hackerone.com/reports/819278](https://hackerone.com/reports/819278)` ✅

`[https://hackerone.com/reports/209223](https://hackerone.com/reports/209223)` ✅

`[https://hackerone.com/reports/764243](https://hackerone.com/reports/764243)` ✅

`[https://hackerone.com/reports/809212](https://hackerone.com/reports/809212)` ✅

`[https://hackerone.com/reports/229690](https://hackerone.com/reports/229690)` ✅

`[https://hackerone.com/reports/278191](https://hackerone.com/reports/278191)` ✅

[https://hackerone.com/reports/1276733](https://hackerone.com/reports/1276733)

[https://hackerone.com/reports/1316650](https://hackerone.com/reports/1316650)

[https://hackerone.com/reports/947725](https://hackerone.com/reports/947725)

[https://hackerone.com/reports/207053](https://hackerone.com/reports/207053)

[https://hackerone.com/reports/209251](https://hackerone.com/reports/209251)

[https://hackerone.com/reports/129381](https://hackerone.com/reports/129381)

[https://medium.com/@ddigvijay/how-i-dumped-millions-of-crypto-currencies-accounts-28d388053713](https://medium.com/@ddigvijay/how-i-dumped-millions-of-crypto-currencies-accounts-28d388053713)

[Subdomain Takeover on happymondays.starbucks.com due to non-used AWS S3 DNS record](https://hackerone.com/reports/186766)

[Subdomain takeover via unsecured s3 bucket](https://blog.securitybreached.org/2018/09/24/subdomain-takeover-via-unsecured-s3-bucket/)

## **Clickjacking (UI redressing)**

1. [**https://apapedulimu.click/clickjacking-on-google-myaccount-worth-7500/](https://apapedulimu.click/clickjacking-on-google-myaccount-worth-7500/) ✅**
2. [**https://medium.com/@adeshkolte/how-i-earned-750-bounty-reward-from-at-t-bug-bounty-adesh-kolte-ae62dea44083](https://medium.com/@adeshkolte/how-i-earned-750-bounty-reward-from-at-t-bug-bounty-adesh-kolte-ae62dea44083) ✅**
3. [**https://medium.com/@ameerassadi/binary-com-clickjacking-vulnerability-exploiting-html5-security-features-368c1ff2219d](https://medium.com/@ameerassadi/binary-com-clickjacking-vulnerability-exploiting-html5-security-features-368c1ff2219d) ✅ SandBox** 
4. [**https://medium.com/@osamaavvan/1800-worth-clickjacking-1f92e79d0414](https://medium.com/@osamaavvan/1800-worth-clickjacking-1f92e79d0414) ✅**
5. [**https://medium.com/@osamaavvan/account-taker-with-clickjacking-ace744842ec3](https://medium.com/@osamaavvan/account-taker-with-clickjacking-ace744842ec3) ✅**
6. [**https://medium.com/@raushanraj_65039/clickjacking-in-google-docs-and-voice-typing-feature-c481d00b020a](https://medium.com/@raushanraj_65039/clickjacking-in-google-docs-and-voice-typing-feature-c481d00b020a) ✅**
7. [**https://medium.com/@raushanraj_65039/google-clickjacking-6a04132b918a](https://medium.com/@raushanraj_65039/google-clickjacking-6a04132b918a) ✅**
8. [**https://medium.com/bugbountywriteup/chaining-self-xss-with-ui-redressing-is-leading-to-session-hijacking-pwn-users-like-a-boss-efb46249cd14 ✅**](https://medium.com/bugbountywriteup/chaining-self-xss-with-ui-redressing-is-leading-to-session-hijacking-pwn-users-like-a-boss-efb46249cd14)
9. [**https://seekurity.com/blog/2016/04/22/admin/poc-gallery/facebook-clickjacking-how-we-put-a-new-dress-on-facebook-ui ✅**](https://seekurity.com/blog/2016/04/22/admin/poc-gallery/facebook-clickjacking-how-we-put-a-new-dress-on-facebook-ui)
10. [**https://websecblog.com/vulns/clickjacking-xss-on-google-org/](https://websecblog.com/vulns/clickjacking-xss-on-google-org/) ✅**
11. [**Redressing Instagram leaking application tokens via Instagram clickjacking vulnerability](https://www.seekurity.com/blog/general/redressing-instagram-leaking-application-tokens-via-instagram-clickjacking-vulnerability/) ✅**
12. [**Microsoft Yammer clickjacking exploiting HTML5 security features](https://www.seekurity.com/blog/general/microsoft-yammer-clickjacking-exploiting-html5-security-features/) ✅**
13. [**Highly wormable clickjacking in player card](https://hackerone.com/reports/85624) to Twitter - 127 upvotes, $5040 ✅**
14. [**Twitter Periscope Clickjacking Vulnerability](https://hackerone.com/reports/591432) to Twitter - 125 upvotes, $1120 ✅**
15. [**Clickjacking on donation page](https://hackerone.com/reports/921709) to WordPress - 88 upvotes, $50 ✅**
16. [**Stealing User emails by clickjacking cards.twitter.com/xxx/xxx](https://hackerone.com/reports/154963) to Twitter - 49 upvotes, $1120  ✅**
17. [**Clickjacking at join.nordvpn.com](https://hackerone.com/reports/765955) to Nord Security - 17 upvotes, $100 ✅**
18. [**Clickjacking is the admin page](https://hackerone.com/reports/728004) to Rocket.Chat - 16 upvotes, $0 ✅**
19. [**Clickjacking on cas.acronis.com login page](https://hackerone.com/reports/971234) to Acronis - 16 upvotes, $0 ✅**
20. [**Clickjacking at ylands.com](https://hackerone.com/reports/405342) to BOHEMIA INTERACTIVE a.s. - 15 upvotes, $80 ✅**

## Host Header Injection

1. [https://chainlover.blogspot.com/2018/11/love-story-of-account-takeover-chaining.html](https://chainlover.blogspot.com/2018/11/love-story-of-account-takeover-chaining.html) ✅
2. [https://lightningsecurity.io/blog/host-header-injection/](https://lightningsecurity.io/blog/host-header-injection/) ✅
3. [https://medium.com/nassec-cybersecurity-writeups/how-i-was-able-to-take-over-any-users-account-with-host-header-injection-546fff6d0f2](https://medium.com/nassec-cybersecurity-writeups/how-i-was-able-to-take-over-any-users-account-with-host-header-injection-546fff6d0f2) ✅
4. [https://medium.com/@bilalmerokhel/pwn-them-all-bugbounty-4ee60e13c83](https://medium.com/@bilalmerokhel/pwn-them-all-bugbounty-4ee60e13c83) ✅
5. [https://pethuraj.com/blog/how-i-earned-800-for-host-header-injection-vulnerability/](https://pethuraj.com/blog/how-i-earned-800-for-host-header-injection-vulnerability/) ✅
6. [https://sites.google.com/site/testsitehacking/10k-host-header](https://sites.google.com/site/testsitehacking/10k-host-header) ✅
7. `[https://hackerone.com/reports/698416](https://hackerone.com/reports/698416)` ✅
8. `[https://hackerone.com/reports/758380](https://hackerone.com/reports/758380)` ✅
9. `[https://hackerone.com/reports/158019](https://hackerone.com/reports/158019)` ✅
10. `[https://hackerone.com/reports/182670](https://hackerone.com/reports/182670)` ✅
11. `[https://hackerone.com/reports/13286](https://hackerone.com/reports/13286)` ✅
12. `[https://hackerone.com/reports/229498](https://hackerone.com/reports/229498)` ✅
13. `[https://hackerone.com/reports/170333](https://hackerone.com/reports/170333)` ✅
14. `[https://hackerone.com/reports/221908](https://hackerone.com/reports/221908)` ✅
15. `[https://hackerone.com/reports/264405](https://hackerone.com/reports/264405)` ✅ **CloudFlare**
16. `[https://hackerone.com/reports/226659](https://hackerone.com/reports/226659)` ✅
17. `[https://hackerone.com/reports/94637](https://hackerone.com/reports/94637)` ✅
18. `[https://hackerone.com/reports/791293](https://hackerone.com/reports/791293)` ✅
19. `[https://hackerone.com/reports/123513](https://hackerone.com/reports/123513)` ✅
20. `[https://hackerone.com/reports/158482](https://hackerone.com/reports/158482)` ✅
21. `[https://hackerone.com/reports/7357](https://hackerone.com/reports/7357)` ✅
22. [https://sechunter.medium.com/ato-via-host-header-poisoning-dc5c29d2fd0d](https://sechunter.medium.com/ato-via-host-header-poisoning-dc5c29d2fd0d) ✅
23. [https://medium.com/@daoud_youssef/from-host-header-injection-to-sql-injection-e7c61a61b575](https://medium.com/@daoud_youssef/from-host-header-injection-to-sql-injection-e7c61a61b575) ✅
24. [https://medium.com/@imunissar786/awesome-host-header-injection-worth-2k-a7e5be1dbb1d](https://medium.com/@imunissar786/awesome-host-header-injection-worth-2k-a7e5be1dbb1d) ✅
25. [https://medium.com/@logicbomb_1/bugbounty-rewarded-by-securing-vulnerabilities-in-bookmyshow-indias-largest-online-movie-bb81dba9b82](https://medium.com/@logicbomb_1/bugbounty-rewarded-by-securing-vulnerabilities-in-bookmyshow-indias-largest-online-movie-bb81dba9b82)

## SSRF

1. [ssrf to sqli](https://caesarevan23.medium.com/ssrf-external-service-interaction-for-find-real-ip-cloudflare-and-leads-to-sql-injection-c22c02243299)  (medium)
2. *[https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/](https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/)*
3. [https://www.linkedin.com/pulse/escalating-blind-ssrf-get-rce-santosh-kumar-sha](https://www.linkedin.com/pulse/escalating-blind-ssrf-get-rce-santosh-kumar-sha)
4. *[http://web.archive.org/web/20190522083351/http://10degres.net/aws-takeover-ssrf-javascript/](http://web.archive.org/web/20190522083351/http://10degres.net/aws-takeover-ssrf-javascript/)*
5. *[https://www.noob.ninja/2017/11/local-file-read-via-xss-in-dynamically.html](https://www.noob.ninja/2017/11/local-file-read-via-xss-in-dynamically.html)*
6. http://10degres.net/aws-takeover-ssrf-javascript/
7. http://blog.haao.sh/notes/downnotifer-ssrf/
8. http://www.kernelpicnic.net/2017/05/29/Pivoting-from-blind-SSRF-to-RCE-with-Hashicorp-Consul.html
9. https://buer.haus/2016/04/18/esea-server-side-request-forgery-and-querying-aws-meta-data/
10. https://buer.haus/2017/03/09/airbnb-chaining-third-party-open-redirect-into-server-side-request-forgery-ssrf-via-liveperson-chat/
11. https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/
12. https://dos.sh/blog/2017/6/21/yahoo-small-business-luminate-and-the-not-so-secret-keys
13. https://evanricafort.blogspot.com/2019/08/ssrf-vulnerability-in.html
14. https://geleta.eu/2019/my-first-ssrf-using-dns-rebinfing/
15. https://hk.saowen.com/a/a8d21c0bdf39e733395aefc0e331998e3d618558f90cf06135aa4df411804e59
16. https://jinone.github.io/bugbounty-a-simple-ssrf/
17. https://medium.com/@0ktavandi/blind-ssrf-in-stripe-com-due-to-sentry-misconfiguration-60ebb6a40b5
18. https://medium.com/@D0rkerDevil/how-i-convert-ssrf-to-xss-in-a-ssrf-vulnerable-jira-e9f37ad5b158
19. https://medium.com/@GeneralEG/escalating-ssrf-to-rce-f28c482eb8b9
20. https://medium.com/@Skylinearafat/how-outdated-jira-instances-suffers-from-multiple-security-vulnerabilities-6a88c45e9ec6
21. https://medium.com/@adeshkolte/how-i-found-xss-via-ssrf-vulnerability-adesh-kolte-873b30a6b89f
22. https://medium.com/@androgaming1912/gain-adfly-smtp-access-with-ssrf-via-gopher-protocol-26a26d0ec2cb
23. https://medium.com/@armaanpathan/pdfreacter-ssrf-to-root-level-local-file-read-which-led-to-rce-eb460ffb3129
24. https://medium.com/@d0nut/piercing-the-veal-short-stories-to-read-with-friends-4aa86d606fc5
25. https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437
26. https://medium.com/@elberandre/1-000-ssrf-in-slack-7737935d3884
27. https://medium.com/@elberandre/ssrf-trick-ssrf-xspa-in-microsofts-bing-webmaster-central-8015b5d487fb
28. https://medium.com/@know.0nix/hunting-good-bugs-with-only-html-d8fd40d17b38
29. https://medium.com/@kurtikleiton/blind-ssrf-on-coda-io-c7063f304455
30. https://medium.com/@logicbomb_1/chain-of-hacks-leading-to-database-compromise-b2bc2b883915
31. https://medium.com/@logicbomb_1/the-journey-of-web-cache-firewall-bypass-to-ssrf-to-aws-credentials-compromise-b250fb40af82
32. https://medium.com/@logicbomb_1/the-unusual-case-of-open-redirection-to-aws-security-credentials-compromise-59acc312f02b
33. https://medium.com/@maxon3/pcextreme-nl-fake-bug-bounty-1a8bf01d518f
34. https://medium.com/@michan001/ssrf-on-pdf-generator-36b81e16d67b
35. https://medium.com/@neerajedwards/reading-internal-files-using-ssrf-vulnerability-703c5706eefb
36. https://medium.com/@ozguralp/using-vulnerability-analytics-feature-like-a-boss-655fc1f1543b
37. https://medium.com/@pflash0x0punk/ssrf-via-ffmpeg-hls-processing-a04e0288a8c5
38. https://medium.com/@pratiky054/ssrf-to-read-local-files-and-abusing-the-aws-metadata-8621a4bf382
39. https://medium.com/@putracraft.theworld/server-side-request-forgery-in-openid-support-defcc64d5e41
40. https://medium.com/@rooterkaustubh/the-story-of-blind-ssrf-leads-to-internal-host-discovery-ee65b9b91e23
41. https://medium.com/@rootxharsh_90844/vimeo-ssrf-with-code-execution-potential-68c774ba7c1e
42. https://medium.com/@sivakrishnasamireddi/just-another-tale-of-severe-bugs-on-a-private-program-405870b03532
43. https://medium.com/@th3g3nt3l/how-i-found-an-ssrf-in-yahoo-guesthouse-recon-wins-8722672e41d4
44. https://medium.com/@tungpun/from-ssrf-to-local-file-disclosure-58962cdc589f
45. https://medium.com/@w_hat_boy/server-side-request-forgery-ssrf-port-issue-hidden-approch-f4e67bd8cc86
46. https://medium.com/@zain.sabahat/exploiting-ssrf-like-a-boss-c090dc63d326
47. https://medium.com/a-bugz-life/exploiting-an-ssrf-trials-and-tribulations-14c5d8dbd69a
48. https://medium.com/a-bugz-life/the-bugs-are-out-there-hiding-in-plain-sight-12d056613ea3
49. https://medium.com/bugbountywriteup/bug-bounty-fastmail-feeda67905f5
50. https://medium.com/bugbountywriteup/piercing-the-veil-server-side-request-forgery-to-niprnet-access-c358fd5e249a
51. https://mike-n1.github.io/SSRF_P4toP2
52. https://ngailong.wordpress.com/2019/04/07/old-but-gold-dot-dot-slash-to-get-the-flag-uber-microservice/amp/
53. https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/
54. https://opnsec.com/2018/07/into-the-borg-ssrf-inside-google-production-network/
55. https://philippeharewood.com/cve-2018-16794-on-fs-thefacebook-com/
56. https://s1gnalcha0s.github.io/dspl/2018/03/07/Stored-XSS-and-SSRF-Google.html
57. https://www.ansariosama.com/2017/09/exploiting-single-request-for-multiple.html
58. https://www.coengoedegebure.com/how-i-got-access-to-local-aws-info-via-jira/
59. https://www.mohamedharon.com/2019/02/ssrf-server-side-request-forgery-in.html#.XGWpfioiVM4.twitter
60. https://www.openbugbounty.org/blog/leonmugen/ssrf-reading-local-files-from-downnotifier-server/
61. https://www.rcesecurity.com/2017/03/ok-google-give-me-all-your-internal-dns-information/
62. https://www.rtcsec.com/2020/04/01-slack-webrtc-turn-compromise/
63. https://www.shawarkhan.com/2018/05/getting-read-access-on-edmodo.html
64. https://ysx.me.uk/a-pair-of-plotly-bugs-stored-xss-and-aws-metadata-ssrf/
65. [Exploiting an SSRF trials and tribulations](https://medium.com/a-bugz-life/exploiting-an-ssrf-trials-and-tribulations-14c5d8dbd69a)
66. [SSRF on PDF generator](https://medium.com/@michan001/ssrf-on-pdf-generator-36b81e16d67b)
67. [Google VRP SSRF in Google cloud platform stackdriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/)
68. [Vimeo upload function SSRF](https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437)
69. [SSRF via ffmeg processing](https://medium.com/@pflash0x0punk/ssrf-via-ffmpeg-hls-processing-a04e0288a8c5)
70. [My first SSRF using DNS rebinding](https://geleta.eu/2019/my-first-ssrf-using-dns-rebinfing/)
71. [Bugbounty simple SSRF](https://jin0ne.blogspot.com/2019/11/bugbounty-simple-ssrf.html)
72. [SSRF reading local files from downnotifier server](https://www.openbugbounty.org/blog/leonmugen/ssrf-reading-local-files-from-downnotifier-server/)
73. [SSRF vulnerability](https://evanricafort.blogspot.com/2019/08/ssrf-vulnerability-in.html)
74. [Gain adfly SMTP access with SSRF via gopher protocol](https://medium.com/@androgaming1912/gain-adfly-smtp-access-with-ssrf-via-gopher-protocol-26a26d0ec2cb)
75. [Blind SSRF in stripe.com due to senntry misconfiguration](https://medium.com/@0ktavandi/blind-ssrf-in-stripe-com-due-to-sentry-misconfiguration-60ebb6a40b5)
76. [SSRF port issue hidden approch](https://medium.com/@w_hat_boy/server-side-request-forgery-ssrf-port-issue-hidden-approch-f4e67bd8cc86)
77. [The jorney of web cache firewall bypass to SSRF to AWS credentials compromise](https://medium.com/@logicbomb_1/the-journey-of-web-cache-firewall-bypass-to-ssrf-to-aws-credentials-compromise-b250fb40af82)
78. [SSRF to local file read and abusing aws metadata](https://medium.com/@pratiky054/ssrf-to-read-local-files-and-abusing-the-aws-metadata-8621a4bf382)
79. [pdfreactor SSRF to root level local files read which lead to RCE](https://medium.com/@armaanpathan/pdfreacter-ssrf-to-root-level-local-file-read-which-led-to-rce-eb460ffb3129)
80. [SSRF trick : SSRF XSPA in micosoft's bing webwaster](https://medium.com/@elberandre/ssrf-trick-ssrf-xspa-in-microsofts-bing-webmaster-central-8015b5d487fb)
81. [Downnotifeer SSRF](https://m-q-t.github.io/notes/downnotifer-ssrf/)
82. [Escalating SSRF to RCE](https://medium.com/cesppa/escalating-ssrf-to-rce-f28c482eb8b9)
83. [Vimeo SSRF with code execution potential](https://medium.com/@rootxharsh_90844/vimeo-ssrf-with-code-execution-potential-68c774ba7c1e)
84. [SSRF in slack](https://medium.com/@elberandre/1-000-ssrf-in-slack-7737935d3884)
85. [Exploiting SSRF like a boss](https://medium.com/@zain.sabahat/exploiting-ssrf-like-a-boss-c090dc63d326)
86. [AWS takeover SSRF javascript](http://10degres.net/aws-takeover-ssrf-javascript/)
87. [Into the borg of SSRF inside google production network](https://opnsec.com/2018/07/into-the-borg-ssrf-inside-google-production-network/)
88. [SSRF to local file disclosure](https://medium.com/@tungpun/from-ssrf-to-local-file-disclosure-58962cdc589f)
89. [How I found an SSRF in yahoo guesthouse (recon wins)](https://medium.com/@th3g3nt3l/how-i-found-an-ssrf-in-yahoo-guesthouse-recon-wins-8722672e41d4)
90. [Reading internal files using SSRF vulnerability](https://medium.com/@neerajedwards/reading-internal-files-using-ssrf-vulnerability-703c5706eefb)
91. [Airbnb chaining third party open redirect into SSRF via liveperson chat](https://buer.haus/2017/03/09/airbnb-chaining-third-party-open-redirect-into-server-side-request-forgery-ssrf-via-liveperson-chat/)
92. 
93. [SSRF in Exchange leads to ROOT access in all instances](https://hackerone.com/reports/341876)
94. [SSRF using Javascript allows to exfill data from Google Metadata](https://hackerone.com/reports/530974)
95. [SSRF in Google cloud platform stackdriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/)
96. [SSRF to ROOT Access](https://hackerone.com/reports/341876)
97. [SSRF reading local files from downnotifier server](https://www.openbugbounty.org/blog/leonmugen/ssrf-reading-local-files-from-downnotifier-server/)
98. [Facebook SSRF](https://medium.com/@amineaboud/10000-facebook-ssrf-bug-bounty-402bd21e58e5)
99. [31k$ SSRF in Google Cloud Monitoring led to metadata exposure](https://nechudav.blogspot.com/2020/11/31k-ssrf-in-google-cloud-monitoring.html)
100. [How I Chained 4 vulnerabilities on GitHub Enterprise, From SSRF Execution Chain to RCE!](http://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html)

## OS Command Injection

1. `[https://hackerone.com/reports/680480](https://hackerone.com/reports/680480)` ✅
2. `[https://hackerone.com/reports/303061](https://hackerone.com/reports/303061)` ✅
3. `[https://hackerone.com/reports/546753](https://hackerone.com/reports/546753)` ✅
4. `[https://hackerone.com/reports/688270](https://hackerone.com/reports/688270)` ✅
5. `[https://hackerone.com/reports/212696](https://hackerone.com/reports/212696)` ✅
6. `[https://hackerone.com/reports/508487](https://hackerone.com/reports/508487)`

## CSRF

1. [Paypal bug bounty: Updating the Paypal. me profile picture without consent (CSRF attack) - Florian Courtial](https://hethical.io/paypal-bug-bounty-updating-the-paypal-me-profile-picture-without-consent-csrf-attack/) ✅
2. [Hacking PayPal Accounts with one click (Patched) - Yasser Ali](http://yasserali.com/hacking-paypal-accounts-with-one-click/) ✅
3. [Add tweet to collection CSRF - Vijay Kumar](https://hackerone.com/reports/100820) ✅
4. [Facebookmarketingdevelopers.com: Proxies, CSRF Quandry, and API Fun - phwd](http://philippeharewood.com/facebookmarketingdevelopers-com-proxies-csrf-quandry-and-api-fun/)
5. [How I Hack your Beats account? Apple Bug Bounty - @aaditya_purani](https://aadityapurani.com/2016/07/20/how-i-hacked-your-beats-account-apple-bug-bounty/)
6. [FORM POST JSON: JSON CSRF on POST Heartbeats API - Dr.Jones](https://hackerone.com/reports/245346)
7. [Hacking Facebook accounts using CSRF in Oculus-Facebook integration](https://www.josipfranjkovic.com/blog/hacking-facebook-oculus-integration-csrf)
8. [Cross site request forgery (CSRF) - Sjoerd Langkemper - Jan 9, 2019](http://www.sjoerdlangkemper.nl/2019/01/09/csrf/)
9. [Cross-Site Request Forgery Attack - PwnFunction](https://www.youtube.com/watch?v=eWEgUcHPle0)
10. [Wiping Out CSRF - Joe Rozner - Oct 17, 2017](https://medium.com/@jrozner/wiping-out-csrf-ded97ae7e83f)
11. [Bypass referer check logic for CSRF](https://www.hahwul.com/2019/10/11/bypass-referer-check-logic-for-csrf/)
12. [https://www.hahwul.com/2019/10/bypass-referer-check-logic-for-csrf.html](https://www.hahwul.com/2019/10/bypass-referer-check-logic-for-csrf.html)
13. [https://whitton.io/articles/messenger-site-wide-csrf/](https://whitton.io/articles/messenger-site-wide-csrf/)
14. https://medium.com/@saadahmedx/bypass-csrf-with-clickjacking-worth-1250-6c70cc263f40
15. [Bypass CSRF with clickjacking on Google org](https://medium.com/@saadahmedx/bypass-csrf-with-clickjacking-worth-1250-6c70cc263f40)
16. [CSRF combined with IDOR within Document Converter exposes files](https://hackerone.com/reports/398316) to Open-Xchange - 51 upvotes, $500
17. [Clickjacking & CSRF attack can be done at https://app.mavenlink.com/login](https://hackerone.com/reports/14494) to Mavenlink - 1 upvotes, $0
18. http://infosecflash.com/2019/01/05/how-i-could-have-taken-over-any-pinterest-account/
19. https://ahussam.me/Leaking-WordPress-CSRF-Tokens/
20. https://blog.ayoubaitelmokhtar.com/2018/06/paypal-bbp-i-couldve-deleted-all-smc.html
21. https://blog.darabi.me/2019/12/instagram-delete-media-csrf.html
22. https://blog.ripstech.com/2019/wordpress-csrf-to-rce/
23. https://blog.scrt.ch/2018/08/24/remote-code-execution-on-a-facebook-server/
24. https://blog.securityevaluators.com/collecting-shells-by-the-sea-of-nas-vulnerabilities-155a0bd7c525
25. https://blog.usejournal.com/cors-to-csrf-attack-c33a595d441
26. https://blog.yappare.com/2018/01/1800-in-less-than-hour.html
27. https://bughunt1307.herokuapp.com/googlebugs.html
28. https://fellchase.blogspot.com/2020/02/site-wide-csrf-on-popular-program.html
29. https://flex0geek.blogspot.com/2020/02/using-csrf-i-got-weird-account-takeover.html
30. https://gauravnarwani.com/admin-hijacked-by-sea-surf-pirates/
31. https://hackademic.co.in/youtube-bug/
32. https://haiderm.com/how-i-was-able-to-delete-13k-microsoft-translator-projects/
33. https://kongwenbin.com/fastest-fix-on-open-bug-bounty-platform/
34. https://ladysecspeare.wordpress.com/2020/04/05/how-a-simple-csrf-attack-turned-into-a-p1-level-bug/
35. https://medium.com/@Hossam.Mesbah/cross-site-request-forgery-critical-exploitable-in-infected-site-a271aedeed2f
36. https://medium.com/@Jacksonkv22/oauth-misconfiguration-lead-to-complete-account-takeover-c8e4e89a96a
37. https://medium.com/@Skylinearafat/a-very-useful-technique-to-bypass-the-csrf-protection-for-fun-and-profit-471af64da276
38. https://medium.com/@abhishake100/how-i-turned-self-xss-to-stored-via-csrf-d12eaaf59f2e
39. https://medium.com/@adeshkolte/cross-site-request-forgery-vulnerability-leads-to-user-profile-change-in-microsoft-express-logic-dc3481ab47ba
40. https://medium.com/@adeshkolte/how-i-got-500-from-microsoft-for-csrf-vulnerability-700accaf48b9
41. https://medium.com/@adeshkolte/how-i-made-1000-at-t-bug-bounty-h1-14e68b284e2f
42. https://medium.com/@adeshkolte/lintern-ute-account-takeover-via-csrf-adesh-kolte-307f7065ee74
43. https://medium.com/@androgaming1912/how-i-found-password-bypass-vulnerability-on-private-document-at-scribd-com-c0905e8dcc9a
44. https://medium.com/@armaanpathan/brute-forcing-user-ids-via-csrf-to-delete-all-users-with-csrf-attack-216ccd4d832c
45. https://medium.com/@ch3ckm4te/self-xss-to-account-takeover-72c89775cf8f
46. https://medium.com/@daniel.thatcher/obtaining-xss-using-moodle-features-and-minor-bugs-2035665989cc
47. https://medium.com/@iSecMax/how-i-hacked-companies-related-to-the-crypto-currency-and-earned-60-000-93e9b3299f4e
48. https://medium.com/@irounakdhadiwal999/stored-iframe-injection-csrf-account-takeover-42c93ad13f5d
49. https://medium.com/@kishorehariram/account-taken-over-in-style-8a547342a5ad
50. https://medium.com/@kongwenbin/fastest-fix-on-open-bug-bounty-platform-4bb03ff846e8
51. https://medium.com/@lokeshdlk77/csrf-email-confirmation-vulnerability-for-gmail-g-suite-in-facebook-5ab551a0a526
52. https://medium.com/@mr_hacker/csrf-bypass-using-cross-frame-scripting-c349d6f33eb6
53. https://medium.com/@navne3t/csrf-csrf-csrf-f203e6452a9c
54. https://medium.com/@nishantrustlingup/my-first-csrf-to-account-takeover-worth-750-1332641d4304
55. https://medium.com/@nnez/always-escalate-from-self-xss-to-persistent-xss-on-login-portal-54265b0adfd0
56. https://medium.com/@osamaavvan/exploiting-websocket-application-wide-xss-csrf-66e9e2ac8dfa
57. https://medium.com/@pig.wig45/json-csrf-attack-on-a-social-networking-site-hackerone-platform-3d7aed3239b0
58. https://medium.com/@rajeshranjan457/how-i-csrfd-my-first-bounty-a62b593d3f4d
59. https://medium.com/@renwa/self-xss-csrf-to-stored-xss-54f9f423a7f1
60. https://medium.com/@saadahmedx/account-takeover-worth-900-cacbe10de58e
61. https://medium.com/@saadahmedx/bypass-csrf-with-clickjacking-worth-1250-6c70cc263f40
62. https://medium.com/@sainttobs/csrf-token-bypasss-a-tale-of-my-2k-bug-ff7f51166ea1
63. https://medium.com/@secureITmania/how-i-exploit-the-json-csrf-with-method-override-technique-71c0a9a7f3b0
64. https://medium.com/@sherazkhalid_60362/account-takeover-by-chaining-two-vulnerabilities-bb447753b089
65. https://medium.com/@shub66452/account-takeover-using-csrf-json-based-a0e6efd1bffc
66. https://medium.com/@valeriyshevchenko/how-i-hacked-one-cryptocurrency-service-db3cb0f81d6c
67. https://medium.com/@vbharad/2-fa-bypass-via-csrf-attack-8f2f6a6e3871
68. https://medium.com/@xhzeem/the-accounttakeover-killing-chain-6ba23f4c9d4
69. https://medium.com/a-bugz-life/4x-csrfs-chained-for-company-account-takeover-f9fada416986
70. https://medium.com/bugbountywriteup/a-simple-bypass-of-registration-activation-that-lead-to-many-bug-a-story-about-how-my-friend-5df0889f1062
71. https://medium.com/bugbountywriteup/critical-bypass-csrf-protection-on-ibm-313ffb68dd0c
72. https://medium.com/bugbountywriteup/csrf-account-takeover-explained-automated-manual-bug-bounty-447e4b96485b
73. https://medium.com/bugbountywriteup/csrf-account-takeover-in-a-company-worth-1b-6e966813c262
74. https://medium.com/bugbountywriteup/csrf-attack-can-lead-to-stored-xss-f40ba91f1e4f
75. https://medium.com/intigriti/how-i-hijacked-your-account-when-you-opened-my-cat-picture-9a0a0acca9e8
76. https://medium.com/tenable-techblog/stealing-downloads-from-slack-users-be6829a55f63
77. https://mike-n1.github.io/Chain_XSS
78. https://ninadmathpati.com/how-i-was-able-to-bypass-the-current-password/
79. https://nirmaldahal.com.np/r-xss-csrf-bypass-to-account-takeover/?__cf_chl_jschl_tk__=d2126b03db2a812a5531feaf545778312401bf1d-1589689403-0-AeUUwidHL9iXCyI5xkfK9YG0i5nb3qc8GtpcX97TylUt6sbNvr1DfRlTfV_2JXFOhtrfyyOYwMkMlB_oQxH8RqXIjvXrTUuipHiCQsPHcztJl1CxaJlslqhTQSLtRqnny7uqJxeV_KxTFaupU6v6klWfK-U8l_SHZTTEposq37_WtcvFiPYM95HGaE5M9I6UisfG5pavR1HZALc9RFVKKSiCrPHXllEJ2msyjXQc65GCSaR-eWHsN0EiNCgDPvAlyQSWT5ygg2bgn6QEM_ZIZDrvME3YcoWx4SGIdj26qT5K_J4RqGZdjUAJIZy-AUqEuh4mLzKqZd3F6bXPKqQylEI
80. https://noobe.io/articles/2019-10/xss-to-account-takeover
81. https://pentester.land/Hacking%20%E2%80%94%20Always%20Check%20the%20Cross-domain%20Policy
82. https://rafiem.github.io/bugbounty/tokopedia/site-wide-csrf-graphql/
83. https://santuysec.com/2020/01/21/google-bug-bounty-csrf-in-learndigital-withgoogle-com/
84. https://smaranchand.com.np/2019/10/an-inconsistent-csrf/
85. https://soroush.secproject.com/blog/2019/04/yet-other-examples-of-abusing-csrf-in-logout/
86. https://www.imperva.com/blog/facebook-privacy-bug/
87. https://www.sagarvd.me/
88. [https://www.sec-down.com/wordpress/?p=809](https://www.sec-down.com/wordpress/?p=809) 
89. [https://ysamm.com/?p=185](https://ysamm.com/?p=185) 
90. [https://ysamm.com/?p=379](https://ysamm.com/?p=379) 
91. `[https://hackerone.com/reports/339352](https://hackerone.com/reports/339352)` ✅
92. `[https://hackerone.com/reports/293016](https://hackerone.com/reports/293016)` ✅
93. `[https://hackerone.com/reports/577920](https://hackerone.com/reports/577920)` ✅
94. `[https://hackerone.com/reports/127703](https://hackerone.com/reports/127703)` ✅
95. `[https://hackerone.com/reports/334253](https://hackerone.com/reports/334253)`
96. `[https://hackerone.com/reports/856518](https://hackerone.com/reports/856518)` ✅
97. `[https://hackerone.com/reports/177472](https://hackerone.com/reports/177472)` ✅
98. `[https://hackerone.com/reports/419891](https://hackerone.com/reports/419891)` ✅
99. `[https://hackerone.com/reports/766533](https://hackerone.com/reports/766533)`
100. `[https://hackerone.com/reports/152569](https://hackerone.com/reports/152569)` ✅
101. `[https://hackerone.com/reports/802930](https://hackerone.com/reports/802930)` ✅
102. `[https://hackerone.com/reports/856981](https://hackerone.com/reports/856981)`
103. `[https://hackerone.com/reports/148156](https://hackerone.com/reports/148156)` ✅

## LFI/LFD - Path Traversal - RFI

### **Remote File Inclusion**

- `[https://hackerone.com/reports/14092](https://hackerone.com/reports/14092)` ✅

### **Path Traversal**

1. `[https://hackerone.com/reports/579517](https://hackerone.com/reports/579517)` ✅
2. `[https://hackerone.com/reports/229622](https://hackerone.com/reports/229622)` ✅
3. `[https://hackerone.com/reports/765291](https://hackerone.com/reports/765291)` ✅
4. `[https://hackerone.com/reports/217344](https://hackerone.com/reports/217344)` ✅
5. `[https://hackerone.com/reports/497771](https://hackerone.com/reports/497771)` ✅
6. `[https://hackerone.com/reports/301862](https://hackerone.com/reports/301862)` ✅

### Local File Inclusion

1. `[https://hackerone.com/reports/492767](https://hackerone.com/reports/492767)` ✅
2. `[https://hackerone.com/reports/1007799](https://hackerone.com/reports/1007799)` ✅
3. `[https://hackerone.com/reports/7779](https://hackerone.com/reports/7779)` ✅
4. `[https://hackerone.com/reports/390013](https://hackerone.com/reports/390013)`
5. [RFI LFI Writeup](http://hassankhanyusufzai.com/RFI_LFI_writeup/) ✅
6. [How we got LFI in apache drill recom like a boss](https://medium.com/bugbountywriteup/how-we-got-lfi-in-apache-drill-recon-like-a-boss-6f739a79d87d) ✅
7. [Bugbounty journey from LFI to RCE](https://medium.com/@logicbomb_1/bugbounty-journey-from-lfi-to-rce-how-a69afe5a0899) ✅
8. [From LFI to RCE via PHP sessions](https://www.rcesecurity.com/2017/08/from-lfi-to-rce-via-php-sessions/) ✅
9. [magix bugbounty magix.com XSS RCE SQLI and LFI](https://www.rcesecurity.com/2014/04/magix-bug-bounty-magix-com-rce-sqli-and-xara-com-lfi-xss/) ✅
10. [https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/](https://buer.haus/2017/06/29/escalating-xss-in-phantomjs-image-rendering-to-ssrflocal-file-read/) ✅
11. [https://medium.com/@armaanpathan/chain-the-bugs-to-pwn-an-organisation-lfi-unrestricted-file-upload-remote-code-execution-93dfa78ecce](https://medium.com/@armaanpathan/chain-the-bugs-to-pwn-an-organisation-lfi-unrestricted-file-upload-remote-code-execution-93dfa78ecce)  ✅
12. [https://medium.com/@logicbomb_1/chain-of-hacks-leading-to-database-compromise-b2bc2b883915](https://medium.com/@logicbomb_1/chain-of-hacks-leading-to-database-compromise-b2bc2b883915)  ✅
13. [https://medium.com/@logicbomb_1/the-journey-of-web-cache-firewall-bypass-to-ssrf-to-aws-credentials-compromise-b250fb40af82](https://medium.com/@logicbomb_1/the-journey-of-web-cache-firewall-bypass-to-ssrf-to-aws-credentials-compromise-b250fb40af82)  ✅
14. [https://medium.com/@maxon3/lfi-to-command-execution-deutche-telekom-bug-bounty-6fe0de7df7a6](https://medium.com/@maxon3/lfi-to-command-execution-deutche-telekom-bug-bounty-6fe0de7df7a6)  ✅
15. [https://medium.com/@tungpun/client-not-client-aa448cfdedd2](https://medium.com/@tungpun/client-not-client-aa448cfdedd2)  ✅
16. [https://medium.com/@zain.sabahat/exploiting-ssrf-like-a-boss-c090dc63d326](https://medium.com/@zain.sabahat/exploiting-ssrf-like-a-boss-c090dc63d326)   ✅
17. [https://medium.com/bugbountywriteup/bugbounty-journey-from-lfi-to-rce-how-a69afe5a0899](https://medium.com/bugbountywriteup/bugbounty-journey-from-lfi-to-rce-how-a69afe5a0899)   ✅

## File Upload

1. [https://anotherhackerblog.com/exploiting-file-uploads-pt-2/](https://anotherhackerblog.com/exploiting-file-uploads-pt-2/) ✅
2. [https://blog.0xatul.me/posts/2020/02/external-xml-entity-via-file-upload-svg/](https://blog.0xatul.me/posts/2020/02/external-xml-entity-via-file-upload-svg/) ✅
3. [https://m0chan.github.io/2020/02/04/Arbitary-File-Upload-Too-Stored-XSS.html](https://m0chan.github.io/2020/02/04/Arbitary-File-Upload-Too-Stored-XSS.html) ✅
4. [https://medium.com/@abhishake100/my-first-rce-stressed-employee-gets-me-2x-bounty-c4879c277e37](https://medium.com/@abhishake100/my-first-rce-stressed-employee-gets-me-2x-bounty-c4879c277e37) ✅
5. [https://medium.com/@asdqwedev/remote-image-upload-leads-to-rce-inject-malicious-code-to-php-gd-image-90e1e8b2aada](https://medium.com/@asdqwedev/remote-image-upload-leads-to-rce-inject-malicious-code-to-php-gd-image-90e1e8b2aada) ✅
6. [https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437](https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437) 
7. [https://medium.com/@ducanhbui/manageengine-servicedesk-plus-arbitrary-file-upload-4bab0bd00425](https://medium.com/@ducanhbui/manageengine-servicedesk-plus-arbitrary-file-upload-4bab0bd00425) ✅
8. [https://medium.com/@frostnull/from-file-upload-to-email-pass-dc7141aa1ff6](https://medium.com/@frostnull/from-file-upload-to-email-pass-dc7141aa1ff6) ✅
9. [https://medium.com/@mohdaltaf163/uploading-backdoor-for-fun-and-profit-rce-db-cred-p1-2cdaa00e2125](https://medium.com/@mohdaltaf163/uploading-backdoor-for-fun-and-profit-rce-db-cred-p1-2cdaa00e2125) ✅
10. [https://ozguralp.medium.com/simple-remote-code-execution-vulnerability-examples-for-beginners-985867878311](https://ozguralp.medium.com/simple-remote-code-execution-vulnerability-examples-for-beginners-985867878311) ✅
11. [https://blog.securitybreached.org/2017/12/19/unrestricted-file-upload-to-rce-bug-bounty-poc/](https://blog.securitybreached.org/2017/12/19/unrestricted-file-upload-to-rce-bug-bounty-poc/) ✅
12. [https://medium.com/@shayboy123/how-i-gain-unrestricted-file-upload-remote-code-execution-bug-bounty-381d0aab0dad](https://medium.com/@shayboy123/how-i-gain-unrestricted-file-upload-remote-code-execution-bug-bounty-381d0aab0dad) ✅
13. [https://medium.com/@smilehackerofficial/how-i-found-rce-but-got-duplicated-ea7b8b010990](https://medium.com/@smilehackerofficial/how-i-found-rce-but-got-duplicated-ea7b8b010990) ✅
14. [https://medium.com/bugbountywriteup/race-condition-that-could-result-to-rce-a-story-with-an-app-that-temporary-stored-an-uploaded-9a4065368ba3](https://medium.com/bugbountywriteup/race-condition-that-could-result-to-rce-a-story-with-an-app-that-temporary-stored-an-uploaded-9a4065368ba3) 
15. [https://mustafakemalcan.com/asus-rce-vulnerability-on-rma-asus-europe-eu/](https://mustafakemalcan.com/asus-rce-vulnerability-on-rma-asus-europe-eu/) ✅
16. [https://supras.io/exploitation-of-the-cve-2018-15961-unrestricted-file-upload-in-adobe-coldfusion/](https://supras.io/exploitation-of-the-cve-2018-15961-unrestricted-file-upload-in-adobe-coldfusion/) ✅
17. [https://vict0ni.me/unrestricted-file-upload-on-pdf/](https://vict0ni.me/unrestricted-file-upload-on-pdf/) ✅
18. [https://ysamm.com/?p=12](https://ysamm.com/?p=12) ✅
19. [How I got stored XSS using a file upload](https://medium.com/@vis_hacker/how-i-got-stored-xss-using-file-upload-5c33e19df51e) ✅
20. [Chain the bugs to pwn an organization LFI unrestricted file upload to RCE](https://medium.com/@armaanpathan/chain-the-bugs-to-pwn-an-organisation-lfi-unrestricted-file-upload-remote-code-execution-93dfa78ecce) ✅
21. [File Upload blind SQLI](https://jspin.re/fileupload-blind-sqli/) ✅
22. [Path traversal while uploading results in RCE](https://blog.harshjaiswal.com/path-traversal-while-uploading-results-in-rce)
23. [RCE by uploading a web config](https://poc-server.com/blog/2018/05/22/rce-by-uploading-a-web-config/)
24. [https://hackerone.com/reports/298](https://hackerone.com/reports/298) ✅
25. [https://blog.detectify.com/2012/12/30/how-i-hacked-facebook-and-received-a-3500-usd-facebook-bug-bounty/](https://blog.detectify.com/2012/12/30/how-i-hacked-facebook-and-received-a-3500-usd-facebook-bug-bounty/) ✅
26. [https://medium.com/@nahoragg/chaining-tricky-oauth-exploitation-to-stored-xss-b67eaea4aabd](https://medium.com/@nahoragg/chaining-tricky-oauth-exploitation-to-stored-xss-b67eaea4aabd)
27. [https://hackerone.com/reports/93807](https://hackerone.com/reports/93807) ✅
28. [https://hackerone.com/reports/865354](https://hackerone.com/reports/865354) ✅
29. [https://hackerone.com/reports/949295](https://hackerone.com/reports/949295) ✅
30. [https://hackerone.com/reports/880099](https://hackerone.com/reports/880099) ✅
31. [https://hackerone.com/reports/808287](https://hackerone.com/reports/808287) ✅
32. [https://hackerone.com/reports/97672](https://hackerone.com/reports/97672) ✅
33. [http://h1.nobbd.de/](http://h1.nobbd.de/)
