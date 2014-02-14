# Morse Code 2.0

By now you all have become experts at translating English to morse code, it's time to do the reverse. **But there's a catch!** Unlike the previous challenge, we aren't giving you a PHP array for doing your lookup; in fact you are **not allowed** to use any kind of lookup array. Instead, you must parse the string using nested `if` and/or `switch` statements. Just like before spaces will be replaced with `/` characters, but to make things simpler we will also separate each letter with a space. So for example, the following:

~~~
.... . .-.. .-.. --- / .-- --- .-. .-.. -..
~~~

would translate to:

~~~
hello world
~~~