# Snapaper PAI
Past Paper Resources From GCE Guide | Made with ![Love](https://static.ouorz.com/heart_16px_501363_easyicon.net.png) by TonyHe

<br/>

### Usage

#### Cookies
+ Key :  snapaper_server
+ Value : 1  for gceguide.com
+ Value : 0  for gecguide.xyz

<br/>

#### Cates
Request
``` php
COOKIES 'snapaper_server' => '1/0'
GET https://www.snapaper.com/vue/cates?cate=:cate
```
Response
``` json
{
    "0": {
        "name": "Accounting (9706)"
    },
    "1": {
        "name": "Afrikaans - Language (AS Level only) (8679)"
    }
}
```

<br/>

#### Papers
Request
``` php
COOKIES 'snapaper_server' => '1/0'
GET https://www.snapaper.com/vue/papers?cate=:cate&sub=:subject
```
Response
``` json
{
    "0": {
        "name": "9609_m16_gt.pdf",
        "url": "/A Levels/Business (for first examination in 2016) (9609)/9609_m16_gt.pdf"
    },
    "1": {
        "name": "9609_m16_ms_12.pdf",
        "url": "/A Levels/Business (for first examination in 2016) (9609)/9609_m16_ms_12.pdf"
    }
}
```

<br/>

### Notice
+ We've set Access-Control-Allow-Origin: *
+ Free of charge
+ No guarantee for stability
+ The server is located in Beijing, China
