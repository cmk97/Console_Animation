
# Console Animation 

This is a simple canvas animation written in pure javascript that writes text as if it's being typed into a computer console. 

## Running the animation

To run the animation, create a canvas element and pass its id to the animation constructor. Include the text you want to write (it supports newlines!). 

```html
<canvas id="animation" style="width:100%; height:500px"></canvas>
<script src="consoleAnimation.js"></script>
<script type="text/javascript">
	var textAnimation = new animation({
		canvas: 'animation',
		text: "Hello.\nI animate text\nsort of like a console\n"
	})
	textAnimation.run();
</script>
```