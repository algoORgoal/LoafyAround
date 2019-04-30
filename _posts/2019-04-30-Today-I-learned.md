---
layout: post1
title: TIL April, 30
---

4/25
reverse(): takes no argument. doesn’t return any value.
reversed(): takes as input sequence. return  reversed argument.
range(a, b): from a to b but doesn’t count b.
python3 and python2 supports almost the same string format. str() returns human-readable string but repr() returns interpreter-readable string. If you want to print quotes itself, you might need to use repr() with string addition.

String formatting in python:
{0} {1} {2} {3} . format(sequence)
{n} is replaced by nth item of sequence

string = ‘{0} {1} {2} {3}’

Using python format string with lists
print(string.format(

Unpacking and packing:
* for lists
** for dictionaries
function(object): doesn’t consider object as several arguments.
function(*object): 

Question: what does packing and unpacking do?
Unpacking: Splitting sequence into several independent items
Packing: opposite for unpacking?
Question: why do I need to put unpacked variable into .format() function?


some python 2 version doesn’t support object unpacking with star(*) marks.

Long floating numbers made by division is automatically shortened when printing out in python3
ex) when a = 1.6888888898989898
print(“{0}”.format(a)) : print out 1.7

Doubling can print out {{ }} brackets.

Measurement of Network
Bandwidth: an amount of data transmitted from the starting point to the end point in certain time
Latency: an amount of time required to transmit data from starting point to the ending point.

Add new key and value pair to dictionary
Dictionary[newkey] = value

Division in python3:
/ -> returns float number if needed
// -> returns integer output

개행문자 출력 안시키는 방법
print(“서울”:end:” ”)

Input function returns output as string.
