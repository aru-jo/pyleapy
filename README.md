# pyleap
pyleap is a python package to determine whether a year is a leap year.
  - It works just as you would expect it to. 
  - Handles iterators (list, tuple, str) , floats, and of course - int 
  - Less memory overhead than calendar's isleap function 

> You may ask me, why do we need a package 
> for such a trivial task ? 
> I ask you this - Why not? 
> Me, Circa 2020 AD (MMXX)

### Installation

pyleap requires [Python](https://www.python.org/) 2 or 3 to run.

Install pyleap via pip.

```sh
$ pip install pyleap 
```


### Development

Want to contribute? Great! - pyleap does need more functionality. 
Raise an issue!

### Usage
Use it to find whether a number(int) is a leap year..or a float - if you're weird enough.  
```sh
import pyleap
print(pyleap.isleap(2000)
```

You can use it on iterables too! We don't like dicts though. 

```sh
print(pyleap.isleap([1900, 1950, 2000])
```

License
----
MIT

**Which means do whatever you want!**

