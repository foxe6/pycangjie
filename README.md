# pyCangJie

<badges>[![version](https://img.shields.io/pypi/v/pycangjie.svg)](https://pypi.org/project/pycangjie/)
[![license](https://img.shields.io/pypi/l/pycangjie.svg)](https://pypi.org/project/pycangjie/)
[![pyversions](https://img.shields.io/pypi/pyversions/pycangjie.svg)](https://pypi.org/project/pycangjie/)  
[![donate](https://img.shields.io/badge/Donate-Paypal-0070ba.svg)](https://paypal.me/foxe6)
[![powered](https://img.shields.io/badge/Powered%20by-UTF8-red.svg)](https://paypal.me/foxe6)
[![made](https://img.shields.io/badge/Made%20with-PyCharm-red.svg)](https://paypal.me/foxe6)
</badges>

<i>CangJie 倉頡 dictionary API.</i>

# Hierarchy

```
pycangjie
|---- convert()
'---- gen_table()
```

# Example

## python
```python
import pycangjie
text = "倉頡API"
print(pycangjie.convert(text))
print(pycangjie.gen_table(pycangjie.convert(text)))
```

## Web
Try it out [here](http://cangjie.xxxx.kozow.com/).
