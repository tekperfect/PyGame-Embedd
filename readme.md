# Embedding Repl.it
All public repl.it's can be embedded via the link in a html iframe and a `?lite=true` parameter

### Additional parameters
`?lite=true&outputonly=1` disables the editor

`height`: int | adjust the height

`width`: int | adjust width

`scrolling`: "no" / "yes" | can scroll

`frameborder"` : "no" / "yes" | border around editor

`allowtransparency` : bool | transparent

`allowfullscreen`: bool | fullscreen 

`sandbox`: sub-set | 


### Current example

```html
<iframe 
height="400px" 
width="100%" 
src="link?lite=true" 
scrolling="no" 
frameborder="no" 
allowtransparency="true" 
allowfullscreen="true" 
sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals">
</iframe>
```