
# Console Animation 

This is a simple canvas animation written in pure javascript that writes text as if it's being typed into a computer console. 

## Running the animation

You can run the animation with the code below. Pass a config object to the animation constructor to customize it. 

```html
<canvas id="animation" style="width:100%; height:500px"></canvas>
<script src="consoleAnimation.js"></script>
<script type="text/javascript">
	var textAnimation = new animation({
		canvas: 'animation',
		text: "This program animates text\nlike it's being typed\ninto a console",
		background: "blue",
		fontSize: 50,
		textColor: '#DDE3E8'
	})
	textAnimation.run();
</script>
```

The config object supports the following properties: 

```javascript
var animationConfig = {	
	canvas: "Canvas-Element-ID",
	text: "The text you want to animate",
	background: "black", //background color
	fontSize: 50, 
	textColor: '#DDE3E8'
}
```