# NeSleep - Won't let your Mac sleep 😴
 
NeSleep is a really simple command/library which you can use to disable the sleep mode on your Mac. By disabling the sleep mode on your Mac, you can let all the tasks ongoing even when your iMac screen is off or MacBook's lid is closed. It also comes in handy when you connect your MacBook to an external display, by letting you close the lid and still be able to use the external display.

## Demo

![Farmers Market Finder Demo](https://github.com/vishalroygeek/NeSleep/blob/master/assets/nesleep-demo.gif)
 
## Installation

You can either fork this github repository, or can simply use PyPi via pip. Also, you can watch the video tutorial [here](https://www.youtube.com/watch?v=C_H_zE6X43g).

```
$ pip install nesleep
```
 
## Usage

Already mentioned above, NeSleep can be used directly from terminal, and can also be imported in your project. Once the installation is successful, follow the methods given below.

##### 1. Terminal
You can simply call the command `nesleep 1` anywhere using a terminal to disable the sleep mode. And to re-enable it, call `nesleep 0`. Yes, its that simple 😉

##### 2. Project
To use nesleep in project, first import sleep from nesleep.
```python
from nesleep import sleep
```

Now, you can call `sleep()` anywhere in the script to enable/disable sleep mode
```python
#This will enable the sleep mode
sleep(True)

#This will disable the sleep mode
sleep(False)
```

# LICENSE
___
```
Copyright (c) 2019 Vishal Roy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
