# Bootstrap - Line Up Those Images

### Bootstrap Website Details
* http://getbootstrap.com/
* Get started with CDN links: http://getbootstrap.com/getting-started/
* Checkout examples: http://getbootstrap.com/getting-started/#examples
* Starter Template: http://getbootstrap.com/getting-started/#template

Bootstrap requires a containing element to wrap site contents and house the grid system.

**Fixed Width**
```
<div class="container">
  ...
</div>
```

**or Full Width: spanning the entire width of the viewport**
```
<div class="container-fluid">
  ...
</div>
```


### Mobile First
Disables zooming on mobile devices
```
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```


### The Grid
* http://getbootstrap.com/css/
* Media Queries - based on different size viewports.
* Rows are made up of 12 columns. 
* Divide 12 by the number of visible columns (any combination adding up to 12).
```
<div class="row">
    <div class="col-lg-4">Column 1</div>
    <div class="col-lg-4">Column 2</div>
    <div class="col-lg-4">Column 3</div>
</div>
```

* Columns have additional class related to re-size: lg, md, sm, xs.
    - **lg** Resizes as soon as the browser window reduces below 1200px
    - **md** Resizes as soon as the browser window reduces below 992px
    - **sm** Resizes as soon as the browser window reduces below 768px
    - **xs** No resize


### Images
* `.img-responsive` class applies:
    - max-width: 100%;
    - height: auto; 
    - display: block; 
    - to the image so that it scales nicely to the parent element
* Center images that use the `.img-responsive class`, with `.center-block`
* Add shapes
    - `<img src="..." alt="..." class="img-rounded">`
    - `<img src="..." alt="..." class="img-circle">`
    - `<img src="..." alt="..." class="img-thumbnail">`

### Grid Detail Example
* https://github.com/brendalong/responsive-starter

### Read Bootstrap docs for more options

