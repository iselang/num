<link rel="preload" as="style" href="https://actwu.github.io/md.css">
<link rel="stylesheet" href="https://actwu.github.io/md.css">

UX
```html
<previews>
<preview bol2>preview 1</preview>
<preview bol2>preview 2</preview>
<preview bol2>preview 3</preview>
</previews>
```
UI
```html
<style>
previews {
display: flex;
overflow-x: auto;
width: auto ;
scroll-snap-type: x mandatory;
padding:2.5px;
}

preview {
flex-shrink: 0;
width: 150px;
height: 190px;
display: flex;
align-items: center;
justify-content: center;
text-align: center;
color: white;
scroll-snap-align: center; 
}

</style>
```
