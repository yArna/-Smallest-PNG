# -Smallest-PNG





I read an interesting post: [The world's smallest PNG - by Evan Hahn ](https://evanhahn.com/worlds-smallest-png/)


This is very interesting, the author built a minimal "legal" PNG file,which is only 67 bytes

I realized that actually non-standard files can be used in many situations, so I tried to remove some data and constructed a minimal "illegal" but usable PNG file, which is only 41 bytes

It can be used in browsers (Chome, Safari, Firefox), can also be previewed and opened in macOS, and can also be used in Figma, but Photoshop cannot open it


Interestingly, on Chrome, if you use it as the background image of Style, it will appear black, but if you use it directly with the <img> tag, it will appear transparent like other browsers.


View in browser ：https://yarna.github.io/-Smallest-PNG/



<hr/>

## 41bytes.png 👇👇👇👇

<img width="200" heigth="200" src="./41bytes.png">
<hr/>
