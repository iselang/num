# Hey!
Start your num with base to have a ui base.

```html
<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

body[full] { margin: 0 auto;
max-width: 90vw; 

box-sizing: border-box;
text-align: center;  background-color: var(--b); }

[hide],[hide] *, app,js,hide { display:none; visibility:hidden; width:0;height:0; size:0;opacity:0%; font-size:0; color:transparent; background:transparent;position:fixed; top:0;z-index:-2;}

::-webkit-scrollbar {min-width: 5px; width: 5px; margin:2px; min-height: 10px; height: 10px; border: 1.5px solid var(--b2); }
::-webkit-scrollbar-thumb {background:var(--b3);border-radius: var(--bdr);}
::-webkit-scrollbar-thumb:hover {background:var(--b2);} 
* { text-decoration: none; text-rendering: optimizeLegibility; text-transform: none; user-zoom: none; 
--bdr:0px;
--sh:2.5px 2.5px 0px 2px;
--r: #dd4162;  --l: #4561ca;  --y: #dbb94c;  --g: #369162;  --p:#de90a0 ;  --v: #8f41dd;  --m: #fafafa;  --b: #101010;
--r2: #a5243f;  --l2: #6247ce;  --y2: #ab8f2a;  --g2: #276846;  --p2: #b36f76; --v2: #6c24a5;  --m2:#eae7f1 !important; --b2: #302e32;
--r3: #df848d;  --l3: #747cc7;  --y3: #e9d086;  --g3: #7db88f;  --p3: #ee9fa7; --v3: #a675d6;  --m3: #cacfe1;  --b3: #60667f;
--r4: #f8bcc9;  --l4: #becaf7;  --y4: #fdf4ce;  --g4: #bafcd8;  --p4: #ffe5e7; --v4: #ebd0ff;  --m4: #dddada;  --b4: #7b7da6;

transition:none!important;
color: var(--m);
border-radius: var(--bdr);font-weight:400; 
font-size: 19px;  letter-spacing:-1.24px;  font-family: "Poppins", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu,
Cantarell, "Helvetica Neue", sans-serif; background-color: var(--b);border: 0;} 
:root, html, body {  background-color: transparent; border-radius:0px; margin: 0px;}
body:not(body[full]) { margin: 0 auto;
max-width: 1280px !important; 
box-sizing: border-box;
text-align: center;  background-color: var(--b); }

[m] {color: var(--m);} svg[m] {fill: var(--m);} [mbg], h1 a {background-color: var(--m);} [mol] {outline: var(--m) solid 1.5px;} [msh] {box-shadow: var(--sh) var(--m);}

[b],h1 a {color:var(--b);} svg[b] {fill: var(--b);} [bbg], p a {background-color:var(--b);} [bol] {outline: var(--b) solid 1.5px;} [bsh] {box-shadow: var(--sh) var(--b );}

[r] {color:var(--r);} svg[r] {fill: var(--r);} [rbg],h2 a{background-color:var(--r);}[rol] {outline: var(--r) solid 1.5px;} [rsh] {box-shadow: var(--sh) var(--r);}

[y] {color:var(--y);} svg[y] {fill: var(--y);} [ybg], h3 a {background-color:var(--y);} [yol] {outline:var(--y) solid 1.5px;} [ysh] {box-shadow: var(--sh) var(--y );}

[l] {color:var(--l);} svg[l] {fill: var(--l);} [lbg], h4 a {background-color:var(--l); } [lol] {outline:var(--l) solid 1.5px;} [lsh] {box-shadow: var(--sh) var(--l );}

[g] {color:var(--g);} svg[g] {fill: var(--g);} [gbg], h5 a {background-color:var(--g);} [gol] {outline:var(--g) solid 1.5px;} [gsh] {box-shadow: var(--sh) var(--g );}

[p] {color:var(--p);} svg[p] {fill: var(--p);} [pbg], h6 a {background-color:var(--p);} [pol] {outline:var(--p) solid 1.5px;} [psh] {box-shadow: var(--sh) var(--p );}

[v] {color:var(--v);} svg[v] {fill: var(--v);} [vbg] {background-color:var(--v);} [vol] {outline:var(--v) solid 1.5px;} [vsh] {box-shadow: var(--sh) var(--v);}


[m2] {color: var(--m2);} svg[m2] {fill: var(--m2);} [mbg2] {background-color: var(--m2);} [mol2] {outline: var(--m2) solid 1px;} [msh2] {box-shadow: var(--sh) var(--m2);}

[b2] {color:var(--b2);} svg[b2] {fill: var(--b2);} [bbg2] {background-color:var(--b2);} [bol2] {outline: var(--b2) solid 1px;} [bsh2] {box-shadow: var(--sh) var(--b2);}

[r2] {color:var(--r2);} svg[r2] {fill: var(--r2);} [rbg2] {background-color:var(--r2);}[rol2] {outline: var(--r2) solid 1px;} [rsh2] {box-shadow: var(--sh) var(--r2);}

[y2] {color:var(--y2);} svg[y2] {fill: var(--y2);} [ybg2] {background-color:var(--y2);} [yol2] {outline:var(--y2) solid 1px;} [ysh2] {box-shadow: var(--sh) var(--y2);}

[l2] {color:var(--l2);} svg[l2] {fill: var(--l2);} [lbg2] {background-color:var(--l2); } [lol2] {outline:var(--l2) solid 1px;} [lsh2] {box-shadow: var(--sh) var(--l2);}

[g2] {color:var(--g2);} svg[g2] {fill: var(--g2);} [gbg2] {background-color:var(--g2);} [gol2] {outline:var(--g2) solid 1px;} [gsh2] {box-shadow: var(--sh) var(--g2);}

[p2] {color:var(--p2);} svg[p2] {fill: var(--p2);} [pbg2] {background-color:var(--p2);} [pol2] {outline:var(--p2) solid 1px;} [psh2] {box-shadow: var(--sh) var(--p2);}

[v2] {color:var(--v2);} svg[v2] {fill: var(--v2);} [vbg2] {background-color:var(--v2);} [vol2] {outline:var(--v2) solid 1px;} [vsh2] {box-shadow: var(--sh) var(--v2);}


[m3] {color: var(--m3);} svg[m3] {fill: var(--m3);} [mbg3] {background-color: var(--m3);} [mol3] {outline: var(--m3) solid 1px;} [msh3] {box-shadow: var(--sh) var(--m3);}

[b3] {color:var(--b3);} svg[b3] {fill: var(--b3);} [bbg3] {background-color:var(--b3);} [bol3] {outline: var(--b3) solid 1px;} [bsh3] {box-shadow: var(--sh) var(--b3);}

[r3] {color:var(--r3);} svg[r3] {fill: var(--r3);} [rbg3] {background-color:var(--r3);}[rol3] {outline: var(--r3) solid 1px;} [rsh3] {box-shadow: var(--sh) var(--r3);}

[y3] {color:var(--y3);} svg[y3] {fill: var(--y3);} [ybg3] {background-color:var(--y3);} [yol3] {outline:var(--y3) solid 1px;} [ysh3] {box-shadow: var(--sh) var(--y3);}

[l3] {color:var(--l3);} svg[l3] {fill: var(--l3);} [lbg3] {background-color:var(--l3); } [lol3] {outline:var(--l3) solid 1px;} [lsh3] {box-shadow: var(--sh) var(--l3);}

[g3] {color:var(--g3);} svg[g3] {fill: var(--g3);} [gbg3] {background-color:var(--g3);} [gol3] {outline:var(--g3) solid 1px;} [gsh3] {box-shadow: var(--sh) var(--g3);}

[p3] {color:var(--p3);} svg[p3] {fill: var(--p3);} [pbg3] {background-color:var(--p3);} [pol3] {outline:var(--p3) solid 1px;} [psh3] {box-shadow: var(--sh) var(--p3);}

[v3] {color:var(--v3);} svg[v3] {fill: var(--v3);} [vbg3] {background-color:var(--v3);} [vol3] {outline:var(--v3) solid 1px;} [vsh3] {box-shadow: var(--sh) var(--v3);}


[m4] {color: var(--m4);} svg[m4] {fill: var(--m4);} [mbg4] {background-color: var(--m4);} [mol4] {outline: var(--m4) solid 1px;} [msh4] {box-shadow: var(--sh) var(--m4);}

[b4] {color:var(--b4);} svg[b4] {fill: var(--b4);} [bbg4] {background-color:var(--b4);} [bol4] {outline: var(--b4) solid 1px;} [bsh4] {box-shadow: var(--sh) var(--b4);}

[r4] {color:var(--r4);} svg[r4] {fill: var(--r4);} [rbg4] {background-color:var(--r4);}[rol4] {outline: var(--r4) solid 1px;} [rsh4] {box-shadow: var(--sh) var(--r4);}

[y4] {color:var(--y4);} svg[y4] {fill: var(--y4);} [ybg4] {background-color:var(--y4);} [yol4] {outline:var(--y4) solid 1px;} [ysh4] {box-shadow: var(--sh) var(--y4);}

[l4] {color:var(--l4);} svg[l4] {fill: var(--l4);} [lbg4] {background-color:var(--l4); } [lol4] {outline:var(--l4) solid 1px;} [lsh4] {box-shadow: var(--sh) var(--l4);}

[g4] {color:var(--g4);} svg[g4] {fill: var(--g4);} [gbg4] {background-color:var(--g4);} [gol4] {outline:var(--g4) solid 1px;} [gsh4] {box-shadow: var(--sh) var(--g4);}

[p4] {color:var(--p4);} svg[p4] {fill: var(--p4);} [pbg4] {background-color:var(--p4);} [pol4] {outline:var(--p4) solid 1px;} [psh4] {box-shadow: var(--sh) var(--p4);}

[v4] {color:var(--v4);} svg[v4] {fill: var(--v4);} [vbg4] {background-color:var(--v4);} [vol4] {outline:var(--v4) solid 1px;} [vsh4] {box-shadow: var(--sh) var(--v4);}

img, embed, iframe, video{outline:solid 2px var(--b) ; width:80%; max-width: 28em;  height: auto;} 
textarea, input{outline:solid 2px var(--b) ; width: 100%; max-width:28em; height: auto; } 
feed,cam {
max-width: 20em;
}
</style>
```
