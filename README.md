# Static Page View Counter

A simple way to implement view/visits counter on your website.

#### Example

![viewsCount](https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?ID=testpage)


## Implementation

#### Decide a page id which will be unique.

your page id must not contain any space and please use a unique keyword.

and your every individual page needs a new unique id.

so I suggest to use your id like this:
if your domain is kamla.com.np and page is home

```
kamla_com_np_home
or
kamla-com-np-home
or
kamlacomnphome
```
or you can use a nike name like
```
ak-kamla_com_np_home
```

# Implementation
### In HTML

you just need to implement an IMG tag in your HTML source code. and put the value of src attribute as given below

```
<img

src="https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?ID=testpage"

alt="testpage">
```
where you have to just change your ID
like
```
ID=kamla-com-np
```
so the link will be
```
https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?ID=kamla-com-np
```


#### Example

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Views Counter Test Page</title>
  </head>
  <body>
    <h1>Views Counter Test Page</h1>
    <img src="https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?ID=testpage" alt="testpage">
  </body>
</html>
```


### In README.md
```
![viewsCount](https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?ID=testpage)
```


### Note
You can use IDV for see only views without updating the badge.
example:
```
![viewsCount](https://img.shields.io/endpoint?url=https://pageviewcounter.000webhostapp.com/?IDV=testpage)
```



## Built With

* **PHP**
* **MySql**

## LICENSE

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details

## Authors

* **Abdhesh Nayak**

	[![Icon](https://img.shields.io/badge/Github-lightgrey)](https://github.com/abdheshnayak) [![Icon](https://img.shields.io/badge/LinkedIn-blue)](https://www.linkedin.com/in/abdhesh-nayak/)

See also the list of [Contributors](https://github.com/abdheshnayak/OffChat/contributors) who participated in this project.
