<link rel="preload" as="style" href="https://actwu.github.io/md2.css">
<link rel="stylesheet" href="https://actwu.github.io/md2.css">

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

2. A Password generator using num
```html
<!DOCTYPE html>
<meta ref="convert:num">
<head>
<link rel='preload' as="script" href='https://cdn.jsdelivr.net/gh/iselang/iselang.github.io@main/num.min.js'>
</head>
<body>

<layout pad="5">
<span> 
  <box></box>
<layout>
<box></box>
<box hei="20" space="5" bbg2 bol3 >
<say id="ps">××××××××××××</say>
</box>
<box hei="20" lbg space="5">
  <tap do="pick('#ps').set=genps(len)">
<say> Gen</say>
</tap>
</box>
    
<span hei="70" gap="3">
<box gbg space="5">
<tap do="len++; pick('#ot').innerText=len">
<i class="fa-solid fa-plus"></i>
</tap>
</box>
  <box bbg2 bol3 space="5">
    <say id="ot">12</say>
  </box>
<box lbg space="5">
<tap do="len=Math.max(1,len-1); pick('#ot').innerText=len">
<i class="fa-solid fa-minus pad="5"></i>
</tap>
</box>

</span>
  <box></box>
</layout>
  <box></box>
</span>
  
</layout>
</body>
<script src="https://cdn.jsdelivr.net/gh/iselang/iselang.github.io@main/num.min.js"></script>
<script>
load("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css")
load('https://iselang.github.io/ux.js');load('num/ui.css')
app('Name of my NUM')
let len=12
const genps=l=>{const c="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()_+[]{}<>?",a=new Uint32Array(l);crypto.getRandomValues(a);return Array.from(a,x=>c[x%c.length]).join("")}
</script>
```
