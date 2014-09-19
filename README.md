#Animate.css
*Add motion to your pages!*

`Animotion.css` is a is a cross-browsers CSS library for animate HTML contents.

##Getting started
After you download Animotion.css, move animotion.css to your root's CSS directory. Next, just include Animotion's CSS file inside of your tags:

```html
<head>
	<link rel="stylesheet" type="text/css" href="css/animotion.min.css"/>
</head>
```

Then just use given classes to add specific animotion to your HTML elements.
You can easily combine it with jQuery using the addClass method.

To add an Animotion programmatically:
```javascript
$('#element').addClass('bounce infinite');
```

**Duration** 

- `short`: animotion is repeated just once
- `medium`: animotion is repeated 5 times
- `long`: animotion is repeated 10 times
- `infinite`: animotion is repeated forever

You can customize the animation count overwriting those classes:

```css
.short {
	-webkit-animation-iteration-count: number; 
	-ms-animation-iteration-count: number; 
	animation-iteration-count: number; 
}
```

##Demo
To check avaiable animotions and view a simple demo click [here](http://lorecioni.github.io/animotion.css)

## License
Animation.css is licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Contributing
Pull requests and feedbacks are welcome here!