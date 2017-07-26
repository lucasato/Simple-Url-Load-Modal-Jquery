# Responsive Jquery Modal Plugin

Load data from an specific url in a modal window.

## Prerequisites

jQuery 1.3+
## Demo

[Demo Gallery](http://www.tiendasdigitales.net/github/simpleurlmodaljs/)

## Quick start

Include CSS And JS Files

1. Include Files:
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<link rel="stylesheet" href="css/simpleurlmodaljs.min.css">
<script src="js/simpleurlmodaljquery.min.js"></script>
```

2. Scope

```js
$('#my-btn').simpleUrlModalJquery(
    {
      width:600,
      height:550,
      title:'Contact Form',
      url:'load-in-modal.html'
      data:{field:value} (optional)
     }
);
```
**HTML**

```html
<input type="button" value="Open Form" id="my-btn"/>
```

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Lucas G. Martinez** - *Initial work* - [Lucasato](https://github.com/lucasato)

See also the list of [contributors](https://github.com/lucasato/simpleurlmodaljs/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
