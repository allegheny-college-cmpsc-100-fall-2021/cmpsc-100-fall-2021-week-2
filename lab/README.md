# Lab: No pane, no gain

![We built this city, but not on rock and roll -- that song is terrible](https://raw.githubusercontent.com/allegheny-college-cmpsc-100-fall-2021/cmpsc-100-fall-2021-week-2-functions-solution/media/media/cmpsc-100-brick-facade.jpg?token=AAL3C7CJW3NANQUWCQHSFADBIJYWQ)

## Overview

Question for you: how long (in person-hours) would it take to wash every window in `NAME OF CITY` and how many people would you need to complete it in a year?

Got your answer? Good.

First, you'd probably like to know what city we're talking about -- that would at least help in terms of figuring out some sense of scale. In essence, that's what this problem is about: it's _not about_ being right or wrong, but being confident in saying

> I think the answer is closer to 1000 hours than 100 and 100 staff instead of 10.

But, to the end of starting our new window washing service, we're going to write the program that we can use to estimate which end of the 100 - 1000 spectrum we're on for sure. 

In this lab, you'll practice using:

* `input()`
* various _operators_ (including `=` and the various arithmetic operators)
* Flow of Control (or, Control of Flow)
* Programming in Python
* problem-solving skills
* creating and using functions

### More facts and parameters for the problem

The above isn't really that helpful, admittedly. But what _would be_? Take some time to think about this with your group. We'll reconvene to put together a list -- what would you want to know in order to successfully estimate this problem?

(We will complete the following table together after you confer with your group.)

Use the following Markdown table below to record some of the helpful factors and values we come up with:

|Factor |Value |
|:------|:-----|
|`TODO` |`TODO`|
|`TODO` |`TODO`|

To add to the table above, paste the following Markdown at the end of the above table to add a new row (replacing the `TODO`s with actual values):

```
|`TODO` |`TODO` |
```

### Test scenarios

The following table lists test scenarios for which your program should feature correct outcomes:

|City size |Estimated "person hours" |Estimated crew |
|:---------|:--------------|:------------------------|
|`300000` |`369285.71`       |`185` |
|`37000000`|`45545238.0`   |`22773` |
|`3000`   |`3692.86`      |`2` |

You are, of course, encouraged to work with your table groups to help derive the way to solve this problem. Of course, TLs and your instructor are also available to assist!

## Requirements

### Program

* A completed program in the [week-2-lab.py](week-2-lab.py) file
* No remaining `TODO`s
* At least `7` single-line comments
  * Recall, these are the lines with the `#` at the start
* Enough uses of the `input()` function to get required information
* Enough uses of the `int()` function to properly convert the data
  * All window count estimates should be returned as `int`
  * Staff counts should be returned as `int`
* Enough suses of the `round()` function to properly round data up or down
  * All hour amounts should be rounded up, to `2` decimal places
  * All staff estimates should be rounded up to `0` decimal places
* Calculations which involve the `+`, `-`, `*`, or `/` (and their various `+=`) counterparts
  * There are multiple ways to solve this problem, though there is likely one optimal solution, given what we know
* At least `2` functions beyond the `main()` function to represent things like:
  * the number of possible windows to be cleaned
  * the overall hours calculation of all of the windows to be cleaned
  * any other functions you find helpful
* Working code when submitted

## Writing

* A [completed reflection](writing/reflection.md) which:
  * Is at least `250` words
  * Features _no_ `TODO`s
