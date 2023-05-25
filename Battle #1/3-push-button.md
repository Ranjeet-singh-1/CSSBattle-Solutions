# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

![result](./images/3-push-button.png)

```html
<p class="circle"><p>
<div></div>
<style>
  body{
    background:#6592CF;
    margin:0;
  }
.circle{
  position:absolute;
  top:125;
  left:175;
  width:50;
  height:50;
  background:#EEB850;
  box-shadow:0 0 0 50px #243D83, 0 0 0 100px #6592CF; 
  /* box-shadow: horizontal vertical blur spread color  */
  border-radius:50%;
}
  div{
    position:absolute;
    top:75;
    left:50;
    width:300;
    height:150;
    background:#243D83;
    z-index:-1; 
/*     Z-index for to order elements one on an above using values */
  }
</style>
```
## Learning
- Syntax to crate box shadow: box-shadow: **_horizontal vertical blur spread color_**
- Z-index for to stacking elements one on an above using z-index values