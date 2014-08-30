---
layout: page
title: Coffeescript == Leibniz's notation
permalink: /coffeescript-is-leibniz-notation/
---


###Calculus and Leibniz's notation

In the 17th century Calculus was conceived separately from the works of two different mathematicians, Isaac Newton and Gottfried Leibniz. At the time there was much controversy on who should get credit for conceiving calculus first. For me the answer is immaterial, calculus is an awesome tool. 

The power of the tool lies in the efficiency in which you can solve problems or make logical arguments. As I think about efficiency as the point of any tool I sometimes wonder if Leibniz's contribution to mathematics was much greater than Newton's. It is the Leibniz notation today that allows children to be taught calculus as early as high school.

###Symbol manipulation and Shortcuts

In calculus as we get familiar with the basic symbol manipulation we start to make shortcuts. These shortcuts do not obfuscate the problem we are working on, in fact in many cases the solution is much easier to understand after these shortcuts are taken. 

Suppose that you were asked to solve a problem in which you needed to take the integral of the tangent function. If you have never taken the integral of the tangent function, you might be in a bind. The simple solution to your dilemma is to use the definition of the tangent function which is sine over cosine. As the sine and cosine integrals are trivial you have probably memorized them and thus will see the obvious substitution solution.

 However, eventually you will stop deriving the integral of the tangent and simply skip to the `ln |sec x| + C` solution. In fact as problems become larger and more complex the shortcut is preferred as anyone reading your work will know the same shortcut.

###Javascript Jungle

When i write client code for the browser I prefer to use Coffeescript. I want to write code fast, efficiently and easy to maintain for other people on the project. I have developed the strong conviction that Coffeescript is Leibniz's notation for Javascript. Unfortunately many front end developers find Coffeescript disagreeable, a position I cannot fathom.
  
I find the Coffeescript -> Javascript translation/compilation to be so simple that in most cases it can be done manually in your head. In the same sense as knowing the integral of the tangent function is built on the sin/cos definitions it should be trivial to interpret :


{% highlight coffeescript %}
(x) ->
  doSomething(x)
{% endhighlight %}

as equivalant to:

{% highlight coffeescript %}
function(x){
  y = doSomething(x);
  return y;
}
{% endhighlight %}










