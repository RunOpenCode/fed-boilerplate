FED Boilerplate
===============

This is collection of commonly used CSS/JS snippets in RunOpenCode projects
that are missing in widely used libraries (e.g. Bootstrap).

## CSS

All css classes using same naming as Bootstrap 3 classes

* **-xs** for extra small devices (less than 768px), this is default and no media query is used 
* **-sm** for small devices (768px and up)
* **-md** for medium devices (992px and up)
* **-lg** for large devices (1200px and up)

there are also classes with _'only'_ suffix - currently can be applied only to clearfix classes

* **-xs-only** only for extra small devices (up to 768px) 
* **-sm-only** only for small devices (from 768px up to 992px)
* **-md-only** only for medium devices (from 992px up to 1200px)
* **-lg-only** only for large devices (1200px and up)

### Display

``` .display-block ``` 

``` .display-inline-block ```

``` .display-inline ```   

### Floating

``` .pull-left ``` 

``` .pull-right ```

``` .pull-none ```

### Margins and padding

##### Margins

Margins can be set to positive and negative values, default classes for margins and padding 
are from 0 to 20px 

eg. ```.ml-xs-10``` is ```margin-left: 10;``` and ```.ml-xs--10``` is ```margin-left: -10px;```

``` .m ```

``` .ml ```

``` .mr ```

``` .mt ```

``` .mb ```

##### Padding

Default classes for padding are from 0 to 20px

``` .p ```

``` .pl ```

``` .pr ```

``` .pt ```

``` .pb ```

### Text

``` .text-center ```

``` .text-left ```

``` .text-right ```

``` .text-justify ```

### Clearfix

``` .clearfix ```
