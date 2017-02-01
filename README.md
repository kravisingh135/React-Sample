# React-Sample

### DOM

```html
div id="content"></div>
```
### JS code

```js
var DemoContent = React.createClass({
			render:function(){
				return(
						<h2>React Heading.</h2>
				);

			}
		});
		React.render(
			<div>
				<DemoContent />				
			</div>, 
			document.getElementById('content'));
```
