# Object Orientated Programming Review

As you build larger and large projects using vanilla JavaScript, you'll notice procedural JavaScript has some limitations and annoyances. For example, consider how long your `index.js` files have been. As you build larger projects, there has to be a better way to scale.

Now, think back to your ruby days. You spent the entire PREWORK coding in procedural Ruby, then we introduced Object Orientated Ruby in Mod 1 in order to better break down and organize our code. 

We will be doing the same thing going into Mod 4. We are going to be coding in Object Orientated JavaScript in order to better manage and organize our code (among many other benefits Object Orientated Programming has to offer).

We will not be re-teaching OO, but instead take some time to review it. 

Before you scroll down any further, do this next exercise in Ruby (it may have been a while since you _really_ coded in Ruby, so don't rush and take this time to review). Perhaps create a [repl.it](https://repl.it/languages/ruby) and code your solution there.

## Exercise 

Create a `Cat` class in ruby. 

All cats should have some data: a name and an age. 

> ella = Cat.new("Ella", 8)
> => #<Cat:0x00007fa386a63390 @name="Ella", @age=8> 

All cats should have some **behavior**. Define a method called `name` that returns the name of the cat 
> ella.name
> => "Ella" 

Next, define a method called `meow` that returns the string `"meeoowwww"`.
> ella.meow
> => "meeoowwww" 

Finally, define a method called `greet` that returns a string of `Hello, my name is`, cat's name in it, and the return of the `meow` method.
> ella.greet
> => "Hi, my name is Ella! meeoowwww" 
