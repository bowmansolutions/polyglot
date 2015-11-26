+++
date = "2015-11-25T21:48:05-05:00"
draft = false
title = "Visual Basic"

+++

I am just not sure that [Visual Basic](https://msdn.microsoft.com/en-us/library/2x7h1hfk.aspx) is for me. I am probably judging too quickly, though; at one time, it was an extremely popular language.

["Jon Hopkins"](http://programmers.stackexchange.com/users/5095/jon-hopkins) articulates well some positives and negatives regarding Visual Basic in an [answer on StackExchange](http://programmers.stackexchange.com/questions/18282/why-do-people-say-that-vb-gives-you-bad-programming-habits#18319):

> 1. VB was always designed as a tool to allow people to get results quickly - both in terms of learning curve and development time. While this is great in some ways the options it gave you to cut corners (which were in many cases the things which increased productivity) were too tempting for a lot of people even when they weren't appropriate.
> 
> 2. It was massively popular, at it's peak the most popular language on the planet. Given that a reasonable proportion of all programmers are bad (and especially as VB did many things which increased the chance that it would have a higher proportion than average), the largest language stands a pretty good chance of having the largest number of bad programmers.
> 
> 3. Some of the default settings encouraged bad practice. For instance by default variable declaration wasn't required (it would automatically come into existence the minute you used it, no need for any `Dim iThingy` as integer, or even just `Dim iThingy` as you didn't need to say what variable type it was if you didn't want to). Anyone decent turned it on (or just typed `Option Explicit` at the top of each module) but be default you didn't have to.
> 
> 4. In the same way VB just had some unpleasant bits in the language and tools. `On Error Resume Next` (basically ignore errors) was over used, the fact that you had to use Goto for error handling and that even done well it was still a bit of a mess, the fact that there were a few too many controls that made simple things even simpler when people might have been better served actually thinking about things a bit more and coding from scratch, the fact that it was very forgiving (so to set the text value of a text box you could just use `Text1 = "blah"` instead of `Text1.Text = "blah"`) which could lead to laziness and code that wasn't as readable as it could be.
> 
> 5. Many people came to VB through VBA in Office. The chances are that if you learned to program throwing together macros in Word, then you never had to learn great programming practice and you might never have seen the need when you scaled up.
> 
> 6. And as part of this when VB4 came along and added object orientation (not really proper object orientation but a bit of it) it did so in a fairly bad way (no polymorphism, no inheritance, all the old non-OO stuff remained which meant it was very take it or leave it and mix and match). This meant that if you were the sort of developer who did bad things, you could now also have bad OO habits.
> 
> But none of these things made you write bad code. I worked with VB for a decade and wrote, and saw other people write, plenty of good workable code that did well in production and was supportable and maintainable.
> 
> The bottom line is that bad programmers write bad code, good programmers write good code. The tools may make it a little easier or a little harder but it's the individual who writes the code and the individual who should take responsibility.

(Thanks to [Jon Hopkins](http://programmers.stackexchange.com/users/5095/jon-hopkins) for this. His and other StackExchange contributions can be shared and adapted according to the [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](http://creativecommons.org/licenses/by-sa/3.0/) license.

