UI
```html
<style>
cards {
display: grid;
grid-template-columns: repeat(2, 1fr);
width: auto;
overflow-x: hidden;
padding:2.5px;
}

card {
width: 100%;
height: 190px;
display: flex;
align-items: center;
justify-content: center;
text-align: center;
}

@media (min-width: 600px) and (max-width: 1024px) {
cards {
grid-template-columns: repeat(3, 1fr); 
}
}

@media (min-width: 1024px) {
cards {
grid-template-columns: repeat(4, 1fr); 
}
}
</style>
```

UX
```html
<cards>
<card bol2>Card 1</card>
<card bol2>Card 2</card>
<card bol2>Card 3</card>
<card bol2>Card 4</card>
<card bol2>Card 5</card>
<card bol2>Card 6</card>
</cards>
```
