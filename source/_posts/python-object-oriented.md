---
title: python 面向对象
date: 2021-01-28 20:16:30
tags: 随笔

---
###面向对象静态语言VS动态语言
python是面向对象动态语言，与之相对的，Java是静态语言
例子如下：
```
class Animal(object):
    def run(self):
        print("animal is running...")
    def shout(self):
        print("animal is shouting...")

class Dog(Animal):
    def run(self):
        print("a dog is running...")
    def shout(self):
        print("a dog is barking...")

class Chick(Animal):
    def run(self):
        print("a chick is running...")
    def shout(self):
        print("a chick is crowing...")

class Timer(object):
    def run(self):
        print("time is running...")

def run_twice(animal):
    animal.run()
    #print("run over.")
dog = Dog()
chick = Chick()
animal = Animal()
timer = Timer()
run_twice(animal)
run_twice(dog)
run_twice(chick)
run_twice(timer)
```
*运行结果*
![运行结果](/images/results/result01.png)


