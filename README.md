# Static Page View Counter

A simple way to implement view counter in your website.

## test page

[https://abdheshnayak.github.io/static-website-views-counter/](https://abdheshnayak.github.io/static-website-views-counter/)

#### ScreenShots

![Image of the Main Screen](screenshots/1.png)


## Built With

* [PHP]
* [mysql]

## Implementation

### Decide a page id which will be unique.

your page id must not contains any space and please use a unique keyword.

### implement int your html code.

you just need to add a iframe tag in your html code where you want to show your views. which contains the following attributes with value.
In source attribute replase your id.

```
<iframe  
	src="https://kamla.com.np/viewcount/?ID=[your_id_of_page]" 
	
	scrolling="no" style="display:inline-block;border:none;
	width:5em;height:2em;">
</iframe>


```

## LICENSE

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details

## Authors

* **Abdhesh Nayak**

	[![Icon](https://img.shields.io/badge/Github-lightgrey)](https://github.com/abdheshnayak) [![Icon](https://img.shields.io/badge/LinkedIn-blue)](https://www.linkedin.com/in/abdhesh-nayak/)

See also the list of [Contributors](https://github.com/abdheshnayak/OffChat/contributors) who participated in this project.
