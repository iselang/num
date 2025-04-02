<link rel="preload" as="style" href="https://actwu.github.io/md.css">
<link rel="stylesheet" href="https://actwu.github.io/md.css">

UX
```html
<slides bol2>
<slide>Slide 1</slide>
<slide>Slide 2</slide>
<slide>Slide 3</slide>
</slides>
```

UI
```html
<style>
slides {
display: flex;
overflow-x: auto;
width: auto;
scroll-snap-type: x mandatory; 
padding: 2px;   
scroll-padding: 2px;
}

slide {
flex-shrink: 0;
width: 100%;
height: 80svh;
display: flex;
align-items: center;
justify-content: center;
text-align: center;
scroll-snap-align: start; 
}
</style>
```
