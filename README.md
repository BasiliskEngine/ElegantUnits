# ElegantUnits
"Lightweight" Java Unit Testing Framework

# Documentation
I wanted really badly to make some videos that could summarize most of what I thought
I wanted to share about ElegantUnits, but today I decided that it might be a little
better to write some documentation for those of you who don't want to watch videos, and
those of you that are just ready to learn the library. I've tried my best to add 
features that work around each other in ElegantUnits, and so far it seems as if I have
done a good job of creating this toolkit so that you can by far strengthen the structure
and the flow of your application architecture in more than one way. If you use ElegantUnits
correctly, there is absolutely no way that your Units shouldn't be working after completing
the unit testing phase, with ElegantUnits. Enjoy!

# Assertions

Just like in real life, assertions in application development can be very dangerous to make.
In Java, if you weren't already familiar, an assertion is a statement in your application that
assumes a condition, and causes your application depend on upon it. For example, if you poll
the user for some input in the first phase of your application, directly after that, you could assert
that this input field is not null, and if it is, your application will crash. Now, that is a clear 
example of intentional termination, which is why we don't really use assertions in production. However,
this is a unit testing framework, and therefore it is a very good idea to use these in order to make sure
that you aren't going to have any null values in places that you shouldn't. Java comes standard with an assert
keyword, but it's pretty stale. First of all, it can only assert a Java boolean value, and it can only throw
exceptions. In ElegantUnits, we can assert values 
