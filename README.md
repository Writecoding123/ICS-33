# ICS-33

有需要请联系学长学姐489388793@qq.com

ICS 33 Fall 2022

The Grin language

The precise requirements for your interpreter are discussed later in this write-up, but we'll first need to agree on the definition of the Grin language that your interpret will implement. Grin is a programming language, though its design is quite different from Python's, so we'll first need to acquaint ourselves with how it works. Given a Grin program, you'll need to know, first and foremost, what its output is meant to be.

A Grin program is a sequence of statements, one per line. Here's an example of a Grin program:

LET MESSAGE "Hello Boo!"
PRINT MESSAGE
.
