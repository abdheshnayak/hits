# Static Page Views Counter

A simple way to implement views/visits counter on your website.

get api key here [https://rapidapi.com/abdheshnayak/api/counter10](https://rapidapi.com/abdheshnayak/api/counter10)

**Example**

![viewsCount](https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&ID=testpage)

## Implementation

#### Decide a page id which will be unique.

Your **page id** must not contain any **space** and please use a **unique** keyword.

And your every individual **page** needs a new **unique id**.

So, I suggest to use your id like this:
if your domain is **api.anayak.com.np** and page is home

```
kamla_com_np_home
or
kamla-com-np-home
or
kamlacomnphome
```

> or you can use a nike name like,

```
ak-kamla_com_np_home
```

# Implementation

### In HTML

You just need to implement an IMG tag in your HTML source code. and put the value of src attribute as given below

```
<img

src="https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&ID=testpage"

alt="test page">
```

where you have to just change your ID
like

```
ID=kamla-com-np
```

so the link will be

```
https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=api-key&&ID=kamla-com-np
```

### Example

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Views Counter Test Page</title>
  </head>
  <body>
    <h1>Views Counter Test Page</h1>
    <img src="https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=api-key&&ID=testpage" alt="testpage">
  </body>
</html>
```

### In README.md

```
![viewsCount](https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&ID=testpage)
```

### Showing without updating Count

You can use IDV for see only views without updating views count.
**example:**

```
https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&IDV=testpage
```

## Use Different Color

You can select the badge of your with different color, also for doing that you have to add do only one attribute i.e. color in the link.

> <p><span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="brightgreen" src="https://img.shields.io/badge/-brightgreen-brightgreen"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="green" src="https://img.shields.io/badge/-green-green"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="yellowgreen" src="https://img.shields.io/badge/-yellowgreen-yellowgreen"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="yellow" src="https://img.shields.io/badge/-yellow-yellow"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="orange" src="https://img.shields.io/badge/-orange-orange"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="red" src="https://img.shields.io/badge/-red-red"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="blue" src="https://img.shields.io/badge/-blue-blue"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="lightgrey" src="https://img.shields.io/badge/-lightgrey-lightgrey"></span></span><br><span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="success" src="https://img.shields.io/badge/-success-success"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="important" src="https://img.shields.io/badge/-important-important"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="critical" src="https://img.shields.io/badge/-critical-critical"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="informational" src="https://img.shields.io/badge/-informational-informational"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="inactive" src="https://img.shields.io/badge/-inactive-inactive"></span></span><br><span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="blueviolet" src="https://img.shields.io/badge/-blueviolet-blueviolet"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="ff69b4" src="https://img.shields.io/badge/-ff69b4-ff69b4"></span><span display="inline" height="20px" class="common__BadgeWrapper-v13icv-3 gEmBHT"><img alt="9cf" src="https://img.shields.io/badge/-9cf-9cf"></span></span></p>

Select a color from above and then use it like this.

```
above_link%26%26COLOR=colorname
```

like,

```
https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=api-key&&IDV=testpage%26%26COLOR=blueviolet
```

**Result**

![viewsCount](https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&IDV=testpage%26%26COLOR=blueviolet)

## Lable Color

You can also change lable color by adding %26%26CLABEL=colorname

```
above_link%26%26CLABEL=colorname
```

like,

```
https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=api-key&&IDV=testpage%26%26COLOR=blueviolet%26%26CLABEL=green
```

**Result**

![viewsCount](https://img.shields.io/endpoint?url=https://counter10.p.rapidapi.com/?rapidapi-key=44fcc7f8f7mshacfcb91fc4190bfp189dddjsnaa696e83052d&&IDV=testpage%26%26COLOR=blueviolet%26%26CLABEL=green)

## Built With

- **PHP**
- **MySql**

## LICENSE

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/abdheshnayak/static-website-views-counter/blob/master/LICENSE) file for details

## Authors

> **Abdhesh Nayak**

[![Icon](https://img.shields.io/badge/Github-lightgrey)](https://github.com/abdheshnayak) [![Icon](https://img.shields.io/badge/LinkedIn-blue)](https://www.linkedin.com/in/abdhesh-nayak/)

**See also the list of [Contributors](https://github.com/abdheshnayak/static-website-views-counter/contributors) who participated in this project.**
