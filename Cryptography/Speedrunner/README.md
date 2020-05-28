# Speedrunner

## Description
I want to make it into the hall of fame -- a top runner in "The History of American Dad Speedrunning". But to do that, I'll need to be faster. I found some [weird parts](https://static.tjctf.org/6e61ec43e56cff1441f4cef46594bf75869a2c66cb47e86699e36577fbc746ff_encoded.txt) in the American Dad source code. I think it might help me become the best. <br>

__Hint__: ```SHI ZAAAAA (cipher)```

## Solution

Pencarian ```flag``` akan kita cari melalui _link_ [weird parts](https://static.tjctf.org/6e61ec43e56cff1441f4cef46594bf75869a2c66cb47e86699e36577fbc746ff_encoded.txt) 

![01](https://user-images.githubusercontent.com/49342639/83008117-dfb7c280-a03e-11ea-94ce-8cbc713effda.PNG)

Darisini, kita dapat melihat dengan sangat jelas terdapat 1 (satu) kalimat dengan ```flag format```

![02](https://user-images.githubusercontent.com/49342639/83008336-36250100-a03f-11ea-8d53-bbf033ecb9d8.PNG)

Karena ```flag``` tersebut masih belum sesuai dengan ```flag format sebenarnya``` dan terdapat __Hint__ yang menunjukkan bahwa ```flag``` di dalam _link_ berbentuk __cipher__, maka kita perlu melakukan pendeskripsian melalui _online tools for decrypt_ yakni ```Cryptii```. Jangan lupa untuk mengatur __shift__ dari __cipher__ tersebut hingga kita berhasil menemukan ```flag``` dengan ```flag format sebenarnya```
	![runner](./runner.png)
	
## Flag
```html
TJCTF{NEW_TECH_NEW_TECH_GO_FAST_GO_FAST}
```
