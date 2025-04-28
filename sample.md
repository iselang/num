<link rel="preload" as="style" href="https://actwu.github.io/md.css">
<link rel="stylesheet" href="https://actwu.github.io/md.css">

[` Back `](./)

# Sample Apps

1. File editor with num

```html
<cont spacet="10">
<row bol4 bend="0">
<tap bol4 bend="0" upload="data" file="txt">
<i class="fa-solid fa-upload"></i>
</tap>
<tap bol4 bend="0" do="
make.file(pick('#name').get,'text', pick('#data').get);"
padl="25" padr="25" >
<i class="fa-solid fa-save"></i>
</tap>
<ask id="name" m big bend="0" style="height: 0.3in">aa</ask>
</row>
<ask bol4 id="data" m big bend="0" style="min-height: 90svh; height: max-width">aa</ask>
</cont> 

<cont></cont>
```
