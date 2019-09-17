# A rating Web component

This is an example project showing how to build a rating Web component by using vanilla JavaScript.

The project defines a star rating component like the following:

![](https://raw.githubusercontent.com/andychiare/rating-stencil-component/master/img/starRating.png)

It allows you to set your rating value and to programmatically handle the component properties.

# Using the component

Copy `myRating.js` file into a local folder named `my-rating`.

Create an HTML page in a local folder and put a script tag in its head section pointing to `myRating.js` file, like in the following example:

```html
<script src="my-rating/myRating.js"></script>
```

Now you can use the component in your HTML by inserting the tag `<my-rating></my-rating>`

The following are the attributes of `my-rating` element:

| Attribute | Description                                   | Default value |
| --------- | --------------------------------------------- | ------------- |
| max-value | The maximum number of stars for the component | 5             |
| value     | The rating value currently shown              | 0             |

See the [index.html](https://github.com/andychiare/rating-stencil-component/blob/master/src/index.html) file for an example of use of the component.

