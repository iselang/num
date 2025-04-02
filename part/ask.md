UI
```html
<style>
ask {
display:flex;
place-content: left;
display: block;
min-width: 10px;
max-width: 100%;
padding: 0.08in 0.15in;
border-radius: var(--bdr);
height: auto;
min-height: auto;
max-height: none;
overflow: auto;
resize: vertical;
justify-content: left;
text-align: left;
}
ask:empty::before {
content: attr(say);
color: var(--b2);
}
</style>

```

UX
```html
<ask bol2 say="hey"></ask>
```
