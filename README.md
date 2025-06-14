# Exercise-7-Create-a-function-which-will-accept-a-string-.solved

Download Here: [Exercise 7 Create a function which will accept a string….solved](https://jarviscodinghub.com/assignment/exercise-7-create-a-function-which-will-accept-a-string-solved/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Create a function which will accept a string and return
(if it exists) an IPv4 address in the string. This means
it should catch any IP addresses of the form W.X.Y.Z
where each letter is replaced with a 1 to 3 digit number up to 255. This means you should find ”0.0.0.0”
and ”255.255.255.255” and anything in between, such as
”192.168.1.64”. You should not catch IP addresses up
to ”999.999.999.999”. It should only get up to a max of
”255” for each byte of the address.
Hint: For each byte of the of the address (each of the
four parts) the easiest solution will be to use multiple
or (|) operators while restricting the first couple digits
of the number. Also, you can mix in any amount of
Python you want (you don’t need to use regex at all if
it’s giving you problems, though regex should make this
relatively easy).
Update: You may assume that if the string contains
an IP address it contains only the IP address. This
means you can use the start (ˆ) and end ($) characters to restrict what your regular expression searches for.
This is useful because if you consider ’400’, the regular
expression r’^1?[0-9]?[0-9]$’ will not match it, but
the regular expression r’1?[0-9]?[0-9]’ will match it.

