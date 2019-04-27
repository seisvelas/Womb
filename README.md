This is a high level language with the flavor of an x86 assembly. Sample code:

```
#lang reader "rosario.rkt"


// countFive.rose
// loop through numbers 1..5


// initialize incrementor
<-  var 0

// loop
label @begin
  ++  var
  hi  var
  !=  var 5
goto @begin

// this program displays the numbers 1 through five successfully using Rosario!
```
