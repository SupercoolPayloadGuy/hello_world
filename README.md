# 🌍 Hello, World! — Every Language Edition

A collection of **Hello, World!** programs across **84 programming languages**, sorted from most to least popular — mainstream languages first, then the glorious chaos of esoteric languages.

---

## Table of Contents

### Mainstream Languages
1. [Python](#1-python)
2. [JavaScript](#2-javascript)
3. [Java](#3-java)
4. [C#](#4-c)
5. [C++](#5-c-1)
6. [C](#6-c-2)
7. [TypeScript](#7-typescript)
8. [PHP](#8-php)
9. [Swift](#9-swift)
10. [Kotlin](#10-kotlin)
11. [Rust](#11-rust)
12. [Go](#12-go)
13. [Ruby](#13-ruby)
14. [R](#14-r)
15. [MATLAB](#15-matlab)
16. [Scala](#16-scala)
17. [Dart](#17-dart)
18. [Lua](#18-lua)
19. [Perl](#19-perl)
20. [Haskell](#20-haskell)
21. [Shell / Bash](#21-shell--bash)
22. [PowerShell](#22-powershell)
23. [Visual Basic .NET](#23-visual-basic-net)
24. [Assembly (x86)](#24-assembly-x86)
25. [Objective-C](#25-objective-c)
26. [Groovy](#26-groovy)
27. [Elixir](#27-elixir)
28. [Clojure](#28-clojure)
29. [F#](#29-f)
30. [Erlang](#30-erlang)
31. [Julia](#31-julia)
32. [OCaml](#32-ocaml)
33. [Fortran](#33-fortran)
34. [COBOL](#34-cobol)
35. [Pascal](#35-pascal)
36. [Ada](#36-ada)
37. [Prolog](#37-prolog)
38. [Lisp / Common Lisp](#38-lisp--common-lisp)
39. [Scheme](#39-scheme)
40. [Racket](#40-racket)
41. [Nim](#41-nim)
42. [Crystal](#42-crystal)
43. [Zig](#43-zig)
44. [D](#44-d)
45. [Haxe](#45-haxe)
46. [Tcl](#46-tcl)
47. [AWK](#47-awk)
48. [Sed](#48-sed)
49. [BASIC](#49-basic)
50. [Delphi](#50-delphi)
51. [CoffeeScript](#51-coffeescript)
52. [Elm](#52-elm)
53. [PureScript](#53-purescript)
54. [ReasonML](#54-reasonml)
55. [V (Vlang)](#55-v-vlang)
56. [Odin](#56-odin)
57. [Gleam](#57-gleam)
58. [ABAP](#58-abap)
59. [SQL](#59-sql)
60. [HTML](#60-html)
61. [Markdown](#61-markdown)

### 🤪 Esoteric Languages
62. [Brainfuck](#62-brainfuck)
63. [Befunge-93](#63-befunge-93)
64. [INTERCAL](#64-intercal)
65. [LOLCODE](#65-lolcode)
66. [ArnoldC](#66-arnoldc)
67. [Shakespeare](#67-shakespeare)
68. [Chef](#68-chef)
69. [Ook!](#69-ook)
70. [Malbolge](#70-malbolge)
71. [Whitespace](#71-whitespace)
72. [COW](#72-cow)
73. [Chicken](#73-chicken)
74. [JSFuck](#74-jsfuck)
75. [Rockstar](#75-rockstar)
76. [Fish (><>)](#76-fish-)
77. [Deadfish](#77-deadfish)
78. [Unlambda](#78-unlambda)
79. [FALSE](#79-false)
80. [/// (Slashes)](#80--slashes)
81. [Piet](#81-piet)
82. [Emojicode](#82-emojicode)
83. [Hexagony](#83-hexagony)
84. [Velato](#84-velato)

---

## 1. Python

**File:** `hello.py`

```python
print("Hello, World!")
```

**Run:**
```bash
python hello.py
```

---

## 2. JavaScript

**File:** `hello.js`

```javascript
console.log("Hello, World!");
```

**Run (Node.js):**
```bash
node hello.js
```

---

## 3. Java

**File:** `Hello.java`

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

**Run:**
```bash
javac Hello.java
java Hello
```

---

## 4. C#

**File:** `Hello.cs`

```csharp
using System;

class Hello {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```

**Run:**
```bash
dotnet run
```

---

## 5. C++

**File:** `hello.cpp`

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

**Run:**
```bash
g++ -o hello hello.cpp
./hello
```

---

## 6. C

**File:** `hello.c`

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

**Run:**
```bash
gcc -o hello hello.c
./hello
```

---

## 7. TypeScript

**File:** `hello.ts`

```typescript
const message: string = "Hello, World!";
console.log(message);
```

**Run:**
```bash
npx ts-node hello.ts
```

---

## 8. PHP

**File:** `hello.php`

```php
<?php
echo "Hello, World!\n";
?>
```

**Run:**
```bash
php hello.php
```

---

## 9. Swift

**File:** `hello.swift`

```swift
print("Hello, World!")
```

**Run:**
```bash
swift hello.swift
```

---

## 10. Kotlin

**File:** `Hello.kt`

```kotlin
fun main() {
    println("Hello, World!")
}
```

**Run:**
```bash
kotlinc Hello.kt -include-runtime -d hello.jar
java -jar hello.jar
```

---

## 11. Rust

**File:** `main.rs`

```rust
fn main() {
    println!("Hello, World!");
}
```

**Run:**
```bash
rustc main.rs
./main
```

---

## 12. Go

**File:** `hello.go`

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

**Run:**
```bash
go run hello.go
```

---

## 13. Ruby

**File:** `hello.rb`

```ruby
puts "Hello, World!"
```

**Run:**
```bash
ruby hello.rb
```

---

## 14. R

**File:** `hello.R`

```r
cat("Hello, World!\n")
```

**Run:**
```bash
Rscript hello.R
```

---

## 15. MATLAB

**File:** `hello.m`

```matlab
disp('Hello, World!')
```

**Run:**
```bash
matlab -batch "run('hello.m')"
```

---

## 16. Scala

**File:** `Hello.scala`

```scala
@main def hello(): Unit =
  println("Hello, World!")
```

**Run:**
```bash
scala Hello.scala
```

---

## 17. Dart

**File:** `hello.dart`

```dart
void main() {
  print('Hello, World!');
}
```

**Run:**
```bash
dart hello.dart
```

---

## 18. Lua

**File:** `hello.lua`

```lua
print("Hello, World!")
```

**Run:**
```bash
lua hello.lua
```

---

## 19. Perl

**File:** `hello.pl`

```perl
#!/usr/bin/perl
print "Hello, World!\n";
```

**Run:**
```bash
perl hello.pl
```

---

## 20. Haskell

**File:** `hello.hs`

```haskell
main :: IO ()
main = putStrLn "Hello, World!"
```

**Run:**
```bash
runhaskell hello.hs
```

---

## 21. Shell / Bash

**File:** `hello.sh`

```bash
#!/bin/bash
echo "Hello, World!"
```

**Run:**
```bash
bash hello.sh
```

---

## 22. PowerShell

**File:** `hello.ps1`

```powershell
Write-Host "Hello, World!"
```

**Run:**
```powershell
pwsh hello.ps1
```

---

## 23. Visual Basic .NET

**File:** `Hello.vb`

```vb
Module Hello
    Sub Main()
        Console.WriteLine("Hello, World!")
    End Sub
End Module
```

**Run:**
```bash
dotnet run
```

---

## 24. Assembly (x86, Linux)

**File:** `hello.asm`

```nasm
section .data
    msg db "Hello, World!", 0x0a
    len equ $ - msg

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, len
    int 0x80

    mov eax, 1
    xor ebx, ebx
    int 0x80
```

**Run:**
```bash
nasm -f elf hello.asm
ld -m elf_i386 -o hello hello.o
./hello
```

---

## 25. Objective-C

**File:** `hello.m`

```objc
#import <Foundation/Foundation.h>

int main() {
    @autoreleasepool {
        NSLog(@"Hello, World!");
    }
    return 0;
}
```

**Run:**
```bash
clang -framework Foundation hello.m -o hello
./hello
```

---

## 26. Groovy

**File:** `hello.groovy`

```groovy
println "Hello, World!"
```

**Run:**
```bash
groovy hello.groovy
```

---

## 27. Elixir

**File:** `hello.exs`

```elixir
IO.puts("Hello, World!")
```

**Run:**
```bash
elixir hello.exs
```

---

## 28. Clojure

**File:** `hello.clj`

```clojure
(println "Hello, World!")
```

**Run:**
```bash
clojure hello.clj
```

---

## 29. F#

**File:** `Hello.fsx`

```fsharp
printfn "Hello, World!"
```

**Run:**
```bash
dotnet fsi Hello.fsx
```

---

## 30. Erlang

**File:** `hello.erl`

```erlang
-module(hello).
-export([start/0]).

start() ->
    io:fwrite("Hello, World!\n").
```

**Run:**
```bash
erl -noshell -s hello start -s init stop
```

---

## 31. Julia

**File:** `hello.jl`

```julia
println("Hello, World!")
```

**Run:**
```bash
julia hello.jl
```

---

## 32. OCaml

**File:** `hello.ml`

```ocaml
let () = print_endline "Hello, World!"
```

**Run:**
```bash
ocaml hello.ml
```

---

## 33. Fortran

**File:** `hello.f90`

```fortran
program hello
    print *, "Hello, World!"
end program hello
```

**Run:**
```bash
gfortran -o hello hello.f90
./hello
```

---

## 34. COBOL

**File:** `hello.cob`

```cobol
       IDENTIFICATION DIVISION.
       PROGRAM-ID. HELLO.
       PROCEDURE DIVISION.
           DISPLAY "Hello, World!".
           STOP RUN.
```

**Run:**
```bash
cobc -x -o hello hello.cob
./hello
```

---

## 35. Pascal

**File:** `hello.pas`

```pascal
program Hello;
begin
  writeln('Hello, World!');
end.
```

**Run:**
```bash
fpc hello.pas
./hello
```

---

## 36. Ada

**File:** `hello.adb`

```ada
with Ada.Text_IO;

procedure Hello is
begin
   Ada.Text_IO.Put_Line("Hello, World!");
end Hello;
```

**Run:**
```bash
gnatmake hello.adb
./hello
```

---

## 37. Prolog

**File:** `hello.pl`

```prolog
:- initialization(main, main).

main(_) :-
    write('Hello, World!'), nl.
```

**Run:**
```bash
swipl hello.pl
```

---

## 38. Lisp / Common Lisp

**File:** `hello.lisp`

```lisp
(format t "Hello, World!~%")
```

**Run:**
```bash
sbcl --script hello.lisp
```

---

## 39. Scheme

**File:** `hello.scm`

```scheme
(display "Hello, World!")
(newline)
```

**Run:**
```bash
guile hello.scm
```

---

## 40. Racket

**File:** `hello.rkt`

```racket
#lang racket
(displayln "Hello, World!")
```

**Run:**
```bash
racket hello.rkt
```

---

## 41. Nim

**File:** `hello.nim`

```nim
echo "Hello, World!"
```

**Run:**
```bash
nim compile --run hello.nim
```

---

## 42. Crystal

**File:** `hello.cr`

```crystal
puts "Hello, World!"
```

**Run:**
```bash
crystal hello.cr
```

---

## 43. Zig

**File:** `hello.zig`

```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```

**Run:**
```bash
zig run hello.zig
```

---

## 44. D

**File:** `hello.d`

```d
import std.stdio;

void main() {
    writeln("Hello, World!");
}
```

**Run:**
```bash
dmd -run hello.d
```

---

## 45. Haxe

**File:** `Hello.hx`

```haxe
class Hello {
    static function main() {
        trace("Hello, World!");
    }
}
```

**Run:**
```bash
haxe --main Hello --interp
```

---

## 46. Tcl

**File:** `hello.tcl`

```tcl
puts "Hello, World!"
```

**Run:**
```bash
tclsh hello.tcl
```

---

## 47. AWK

**File:** `hello.awk`

```awk
BEGIN {
    print "Hello, World!"
}
```

**Run:**
```bash
awk -f hello.awk
```

---

## 48. Sed

```bash
echo "" | sed 's/.*/Hello, World!/'
```

---

## 49. BASIC

**File:** `hello.bas`

```basic
10 PRINT "Hello, World!"
20 END
```

**Run:**
```bash
qbasic hello.bas
```

---

## 50. Delphi

**File:** `Hello.dpr`

```pascal
program Hello;
{$APPTYPE CONSOLE}
begin
  Writeln('Hello, World!');
end.
```

**Run:** `dcc32 Hello.dpr`

---

## 51. CoffeeScript

**File:** `hello.coffee`

```coffeescript
console.log "Hello, World!"
```

**Run:**
```bash
coffee hello.coffee
```

---

## 52. Elm

**File:** `Hello.elm`

```elm
module Hello exposing (main)

import Html exposing (text)

main =
    text "Hello, World!"
```

**Run:**
```bash
elm reactor
```

---

## 53. PureScript

**File:** `Hello.purs`

```purescript
module Main where

import Effect.Console (log)
import Effect (Effect)

main :: Effect Unit
main = log "Hello, World!"
```

**Run:**
```bash
spago run
```

---

## 54. ReasonML

**File:** `Hello.re`

```reason
let () = print_endline("Hello, World!");
```

**Run:**
```bash
ocamlfind ocamlopt -package reason -linkpkg Hello.re -o hello && ./hello
```

---

## 55. V (Vlang)

**File:** `hello.v`

```v
fn main() {
    println('Hello, World!')
}
```

**Run:**
```bash
v run hello.v
```

---

## 56. Odin

**File:** `hello.odin`

```odin
package main

import "core:fmt"

main :: proc() {
    fmt.println("Hello, World!")
}
```

**Run:**
```bash
odin run hello.odin -file
```

---

## 57. Gleam

**File:** `hello.gleam`

```gleam
import gleam/io

pub fn main() {
  io.println("Hello, World!")
}
```

**Run:**
```bash
gleam run
```

---

## 58. ABAP

```abap
REPORT zhello.
WRITE: / 'Hello, World!'.
```

**Run:** Execute within SAP GUI using transaction `SE38`.

---

## 59. SQL

```sql
SELECT 'Hello, World!' AS message;
```

**Run:**
```bash
sqlite3 :memory: "SELECT 'Hello, World!' AS message;"
```

---

## 60. HTML

**File:** `hello.html`

```html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Hello</title></head>
<body><h1>Hello, World!</h1></body>
</html>
```

---

## 61. Markdown

**File:** `hello.md`

```markdown
# Hello, World!
```

---

---

# 🤪 Esoteric Languages

> _"Why write readable code when you could write poetry, recipes, or cow sounds?"_
>
> Sorted roughly by notoriety within the esolang community. There are 6,600+ on the [Esolangs Wiki](https://esolangs.org) — this is just the greatest hits.

---

## 62. Brainfuck

> The godfather of esolangs. Only **8 commands**. Turing-complete. Utterly unreadable. Inspired dozens of derivatives.

**File:** `hello.bf`

```brainfuck
++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.
```

| Command | Meaning |
|---|---|
| `>` | Move pointer right |
| `<` | Move pointer left |
| `+` | Increment cell |
| `-` | Decrement cell |
| `.` | Output cell as ASCII |
| `,` | Input a byte to cell |
| `[` | Jump past `]` if cell is 0 |
| `]` | Jump back to `[` if cell is nonzero |

**Run:**
```bash
brainfuck hello.bf
```

---

## 63. Befunge-93

> Code is a **2D grid**. The instruction pointer can move up, down, left, or right. It wraps around. It can loop back over its own code.

**File:** `hello.b93`

```befunge
"!dlroW ,olleH">:#,_@
```

> `"` enters string mode and pushes characters onto the stack in reverse. `>` moves right, `#` jumps over next instruction, `,` outputs a char, `_` goes right if stack top is 0, `@` ends program.

**Run:**
```bash
befunge hello.b93
```

**Try online:** [https://tio.run/#befunge93](https://tio.run/#befunge93)

---

## 64. INTERCAL

> Created in 1972 as a parody. It **requires the word `PLEASE`** a certain number of times — too few and it says your program is "insufficiently polite"; too many and it complains you're a sycophant.

**File:** `hello.i`

```intercal
DO ,1 <- #13
DO ,1 SUB #1 <- #238
DO ,1 SUB #2 <- #108
DO ,1 SUB #3 <- #112
DO ,1 SUB #4 <- #0
DO ,1 SUB #5 <- #64
DO ,1 SUB #6 <- #194
DO ,1 SUB #7 <- #48
DO ,1 SUB #8 <- #22
DO ,1 SUB #9 <- #248
DO ,1 SUB #10 <- #168
DO ,1 SUB #11 <- #24
DO ,1 SUB #12 <- #16
DO ,1 SUB #13 <- #162
PLEASE READ OUT ,1
PLEASE GIVE UP
```

> Values are encoded in a bizarre interleaved bit format. `PLEASE` can replace `DO` — and must appear for the program to be considered polite.

**Run:**
```bash
ick hello.i && ./hello
```

---

## 65. LOLCODE

> Based on **LOLcat internet memes**. `HAI` starts the program, `KTHXBYE` ends it. `VISIBLE` prints. It's fully functional despite reading like a cat wrote it.

**File:** `hello.lol`

```lolcode
HAI 1.4
  VISIBLE "Hello, World!"
KTHXBYE
```

**Run:**
```bash
lci hello.lol
```

---

## 66. ArnoldC

> Every keyword is an **Arnold Schwarzenegger one-liner**. `IT'S SHOWTIME` starts the program. `YOU HAVE BEEN TERMINATED` ends it.

**File:** `hello.arnoldc`

```arnoldc
IT'S SHOWTIME
TALK TO THE HAND "Hello, World!"
YOU HAVE BEEN TERMINATED
```

| ArnoldC Keyword | Meaning |
|---|---|
| `IT'S SHOWTIME` | Begin main |
| `YOU HAVE BEEN TERMINATED` | End main |
| `TALK TO THE HAND` | Print to stdout |
| `GET TO THE CHOPPER` | Declare variable |
| `HASTA LA VISTA, BABY` | End if block |
| `GET UP` | Increment |
| `GET DOWN` | Decrement |

**Run:**
```bash
arnoldc hello.arnoldc
```

---

## 67. Shakespeare

> Programs look like **Shakespearean plays**. Characters are variables. Their dialogue contains arithmetic. `Speak your mind!` prints the current character's value as ASCII.

**File:** `hello.spl`

```shakespeare
The Tragedy of Hello World.

Romeo, a young man with remarkable patience.
Juliet, a likewise young woman of remarkable grace.

Act I: The only act.
Scene I: The beginning.

[Enter Romeo and Juliet]

Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Romeo: Speak your mind!

[Exeunt]
```

> Nouns have positive (pretty, big, kingdom → +1) or negative (pig, rotten → -1) values. Adjectives double. So "big mighty proud kingdom" = 2×2×2×1 = 8. Romeo accumulates values until he equals an ASCII code, then speaks.

**Run:**
```bash
spl2c < hello.spl > hello.c && gcc hello.c -o hello && ./hello
```

---

## 68. Chef

> Programs look like **cooking recipes**. Variables are ingredients measured in grams/cups/etc. Stacks are mixing bowls. `Serves N` outputs the result.

**File:** `hello.chef`

```chef
Hello World Cake with Chocolate sauce.

Ingredients.
72 g chocolate chips
101 g butter
108 g flour
111 g sugar
44 g baking soda
32 g cocoa
87 g milk
111 g eggs
114 g cream
100 g vanilla extract
33 g salt
10 g baking powder

Method.
Put salt into the mixing bowl.
Put baking powder into the mixing bowl.
Put vanilla extract into the mixing bowl.
Put cream into the mixing bowl.
Put eggs into the mixing bowl.
Put milk into the mixing bowl.
Put cocoa into the mixing bowl.
Put sugar into the mixing bowl.
Put flour into the mixing bowl.
Put butter into the mixing bowl.
Put chocolate chips into the mixing bowl.
Liquify contents of the mixing bowl.
Pour contents of the mixing bowl into the baking dish.

Serves 1.
```

> Each ingredient quantity is an ASCII code. `Liquify` converts numbers to characters. The baking dish is the output buffer.

**Run:**
```bash
chef hello.chef
```

---

## 69. Ook!

> A parody of Brainfuck where all 8 commands are replaced by combinations of **orangutan sounds**: `Ook.`, `Ook?`, and `Ook!`

**File:** `hello.ook`

```ook
Ook. Ook? Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook.
Ook. Ook. Ook. Ook. Ook! Ook? Ook? Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook.
Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook? Ook! Ook! Ook? Ook! Ook? Ook.
Ook! Ook. Ook. Ook? Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook.
Ook. Ook. Ook! Ook? Ook? Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook?
Ook! Ook! Ook? Ook! Ook? Ook. Ook. Ook. Ook! Ook. Ook. Ook. Ook. Ook. Ook. Ook.
Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook. Ook! Ook. Ook! Ook. Ook. Ook. Ook. Ook.
Ook. Ook. Ook! Ook. Ook. Ook? Ook. Ook? Ook. Ook? Ook. Ook. Ook. Ook. Ook. Ook.
Ook! Ook.
```

| Ook pair | Brainfuck equivalent |
|---|---|
| `Ook. Ook?` | `>` |
| `Ook? Ook.` | `<` |
| `Ook. Ook.` | `+` |
| `Ook! Ook!` | `-` |
| `Ook! Ook.` | `.` |
| `Ook. Ook!` | `,` |
| `Ook! Ook?` | `[` |
| `Ook? Ook!` | `]` |

**Run:**
```bash
ook hello.ook
```

---

## 70. Malbolge

> Named after the **8th circle of Hell**. Designed in 1998 to be literally impossible to program in. It took **two years** for the first Hello World to appear — found by a constraint solver, not a human.

> Code is self-modifying by design. Every instruction encrypts itself after execution. Data is ternary. There are only 8 real commands out of 94 possible characters.

**File:** `hello.mal`

```
('&%:9]!~}|z2Vxwv-,POqponl$Hjig%eB@@>}=<M:9wv6WsU2T|nm-,jcL(I&%$#"
`CB]V?Tx<uVtT`Rpo3NlF.Jh++FdbCBA@?]!~|4XzyTT43Qsqq(Lnmkj"Fhg${z@>
```

> This is actual, real, valid Malbolge that prints "Hello World". No human wrote it by hand.

**Run:**
```bash
malbolge hello.mal
```

> **Trivia:** The author, Ben Olmstead, stated he believed it was impossible to write a Malbolge program. He was wrong — but only barely.

---

## 71. Whitespace

> Only **spaces**, **tabs**, and **newlines** are significant. Every other character is a comment. This README cannot display the actual file — download it separately.

> In Whitespace notation (S=Space, T=Tab, N=Newline), pushing the ASCII value of 'H' (72) and printing it looks like:
>
> `S S S T S S S T S S N` (push 72) followed by `T N S` (print as char)
>
> Repeat for each character of "Hello, World!" and end with an exit.

**Run:**
```bash
whitespace hello.ws
```

**Try online:** [https://tio.run/#whitespace](https://tio.run/#whitespace)

---

## 72. COW

> A Brainfuck variant where all 12 commands are **variations of the word "moo"**. For bovine programmers.

**File:** `hello.cow`

```cow
MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO
MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO
MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO
MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO
OOO MOO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO
MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO MoO moo MOo
MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo MOo Moo
```

| Command | Effect |
|---|---|
| `moo` | Loop start (like `[`) |
| `MOO` | Loop end (like `]`) |
| `MoO` | Increment cell |
| `MOo` | Decrement cell |
| `moO` | Move pointer right |
| `mOo` | Move pointer left |
| `OOO` | Set cell to zero |
| `oOO` | Print cell as char |

**Run:**
```bash
cow hello.cow
```

---

## 73. Chicken

> The **only valid token is `chicken`**. The number of repetitions on each line determines the opcode. That's it. That's the whole language.

**File:** `hello.chicken`

```
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
```

> Opcode 0 (no chickens on a line) = halt. Opcode 1 = push string "chicken". Opcode 2 = add. Opcode 3 = subtract. Opcode 4 = multiply. Opcode 5 = compare. Higher opcodes load/store from the chicken "BBQ" data store.

**Run:**
```bash
chicken hello.chicken
```

---

## 74. JSFuck

> JavaScript written using **only 6 characters**: `(` `)` `[` `]` `!` `+`. Completely valid JS. Runs in any browser console.

**File:** `hello.js`

```javascript
[][(![]+[])[+[]]+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]+(!![]+[])[+[]]]
[([][(![]+[])[+[]]+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]+(!![]+[])[+[]]]+[])
[!+[]+!+[]+!+[]]+(!![]+[][(![]+[])[+[]]+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]
+(!![]+[])[+[]]])[+!+[]+[+[]]]+([][[]]+[])[+!+[]]+(![]+[])[!+[]+!+[]+!+[]]
+(!![]+[])[+[]]+(!![]+[])[+!+[]]+([][[]]+[])[+[]]+([][(![]+[])[+[]]+(![]+[])
[!+[]+!+[]]+(![]+[])[+!+[]]+(!![]+[])[+[]]]+[])[!+[]+!+[]+!+[]]+(!![]+[])[+[]]
+(!![]+[][(![]+[])[+[]]+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]+(!![]+[])[+[]]])[+!+[]+[+[]]]
+(!![]+[])[+!+[]]]((![]+[])[+!+[]]+(![]+[])[!+[]+!+[]]+(!![]+[])[!+[]+!+[]+!+[]]
+(!![]+[])[+!+[]]+(!![]+[])[+[]]+([][(![]+[])[+[]]+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]
+(!![]+[])[+[]]]+[])[+!+[]+[!+[]+!+[]+!+[]]]+[+!+[]]+([+[]]+![]+[][(![]+[])[+[]]
+(![]+[])[!+[]+!+[]]+(![]+[])[+!+[]]+(!![]+[])[+[]]])[!+[]+!+[]+[+[]]])()
```

**Run:**
```bash
node hello.js
# Or paste directly into any browser console
```

---

## 75. Rockstar

> A language designed so that programs are also **valid rock ballads**. Variable names are song-lyric-style phrases. Arithmetic is expressed poetically.

**File:** `hello.rock`

Simple version:
```rockstar
Shout "Hello, World!"
```

Full rock-star lyrical version:
```rockstar
Tommy was a dancer
The world is a stage
While Tommy ain't nothing
Shout "Hello, World!"
Tommy said Tommy
```

> **Variable naming:** `"My world is a fire"` → variable `my world` = 4 (letter count of `fire`). Every word in a string literal encodes a digit by its length. Poetry is math.

**Run:**
```bash
rockstar hello.rock
```

**Try online:** [https://codewithrockstar.com/online](https://codewithrockstar.com/online)

---

## 76. Fish (`><>`)

> Another 2D stack-based language. The instruction pointer wraps like a **fish swimming in a bowl**. Named appropriately.

**File:** `hello.fish`

```
"Hello, World!"r!|o<
```

Or multi-line:
```
"Hello, World!"
v             <
>l?!;o        ^
```

> `>` `<` `^` `v` set direction. `"` toggles string mode. `o` outputs a char. `l` pushes stack length. `r` reverses the stack. `;` ends the program. `!` skips next instruction.

**Run:**
```bash
python fish.py hello.fish
```

**Try online:** [https://tio.run/#fish](https://tio.run/#fish)

---

## 77. Deadfish

> Minimal to the extreme: **only 4 commands**. No loops. No conditionals. To print "H" (ASCII 72), you carefully square and increment your way there.

**File:** `hello.df`

```deadfish
iisiiiisiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiioddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiodddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddo
```

| Command | Effect |
|---|---|
| `i` | Increment accumulator |
| `d` | Decrement accumulator |
| `s` | Square accumulator |
| `o` | Output accumulator as ASCII char |

> If accumulator hits 256 or -1, it silently resets to 0. There is no way to loop except by writing out every single increment/decrement by hand.

**Run:**
```bash
deadfish hello.df
```

---

## 78. Unlambda

> A **functional language based on combinatory logic**. No variables. No data types. Just functions applied to functions. Even "Hello, World!" is deeply painful.

**File:** `hello.unl`

```unlambda
`r```````````.H.e.l.l.o.,. .W.o.r.l.d.!i
```

> `` ` `` applies a function to an argument. `.X` prints the character X. `i` is the identity function (`i x = x`). `r` prints a newline. `k` is the K combinator (`k x y = x`). `s` is the S combinator (`s x y z = x z (y z)`).

**Run:**
```bash
unlambda hello.unl
```

---

## 79. FALSE

> The language that **directly inspired Brainfuck**. Stack-based, cryptic by design. Created in 1993. The entire compiler fit in 1024 bytes.

**File:** `hello.false`

```false
"Hello, World!"
```

> In FALSE, `"..."` pushes each character's ASCII value onto the stack one by one. `,` pops and prints a character. The above prints the string directly using the string output form.

**Run:**
```bash
false hello.false
```

---

## 80. `///` (Slashes)

> A language with exactly **one operation: string substitution**. Patterns look like `/find/replace/text`. Turing-completeness comes entirely from recursive self-referential substitutions.

**File:** `hello.sl`

```
Hello, World!
```

> If there are no `/` patterns, text is printed directly. The power of `///` is in looping: `/loop//loop/` would create an infinite substitution cycle. A real loop in `///` looks like `/[/\//[/]/loop/[loop]`.

**Run:**
```bash
slashes hello.sl
```

---

## 81. Piet

> Programs are **bitmap images** that look like abstract pixel art. The "instruction pointer" moves through colored blocks. Named after Piet Mondrian.

**File:** `hello.png` _(an actual image file)_

> A Piet Hello World looks like a small colorful pixel grid. Each colored region's size encodes a number; transitions between adjacent hue/brightness levels encode operations (push, add, duplicate, output char, etc.).

```
[Cannot be represented as text — it's a PNG image]
```

> The 20 valid colors are arranged in a 6-hue × 3-brightness cycle. Black blocks walls. White blocks are no-ops. The pointer bounces off walls and navigates through the image as the program runs.

**Run:**
```bash
npiet hello.png
```

**Try online:** [https://www.bertnase.de/npiet/npiet-execute.php](https://www.bertnase.de/npiet/npiet-execute.php)

---

## 82. Emojicode

> A **fully statically typed, object-oriented language** where all syntax is emojis. Not a joke — it has classes, generics, closures, and a real compiler.

**File:** `hello.emojic`

```emojicode
🏁 🍇
  😀 🔤Hello, World!🔤❗️
🍉
```

> `🏁` is the entry point. `🍇` opens a block, `🍉` closes it. `😀` is the print function. `🔤` delimiters mark a string literal. `❗️` calls a method.

**Run:**
```bash
emojicodec hello.emojic
./hello
```

---

## 83. Hexagony

> Code is arranged in a **hexagonal grid**. Six instruction pointers travel in six directions simultaneously. Only one is active at any time — but they all exist.

**File:** `hello.hxg`

```hexagony
H;e;l;l;o;,; ;W;o;r;l;d;!<@
```

Laid out in its natural hexagonal form:
```
      H ; e ; l
     ; l ; o ; ,
    ;   ; W ; o ;
     r ; l ; d ;
      ! < @ . .
```

> `@` terminates the program. `;` outputs the current memory edge as a character. The memory model is an infinite hexagonal grid of integers (separate from the code grid). Each of the six instruction pointers starts at a corner of the hexagon.

**Run:**
```bash
hexagony hello.hxg
```

**Try online:** [https://hexagony.net](https://hexagony.net)

---

## 84. Velato

> Programs are **MIDI files**. The pitch intervals between consecutive notes encode instructions. You can literally **play your code as music** on a piano.

**File:** `hello.mid` _(a MIDI file)_

> Velato maps intervals between consecutive notes to operations. A major third (4 semitones) might push a value; a perfect fifth (7 semitones) might output a character. A Hello World program played on piano produces real program output when passed to the interpreter.

**Run:**
```bash
java -jar velato.jar hello.mid
```

---

## Summary Table — Mainstream Languages

| # | Language | Paradigm | Typed | Year |
|---|----------|----------|-------|------|
| 1 | Python | Multi | Dynamic | 1991 |
| 2 | JavaScript | Multi | Dynamic | 1995 |
| 3 | Java | OOP | Static | 1995 |
| 4 | C# | Multi | Static | 2000 |
| 5 | C++ | Multi | Static | 1985 |
| 6 | C | Procedural | Static | 1972 |
| 7 | TypeScript | Multi | Static | 2012 |
| 8 | PHP | Multi | Dynamic | 1994 |
| 9 | Swift | Multi | Static | 2014 |
| 10 | Kotlin | Multi | Static | 2011 |
| 11 | Rust | Multi | Static | 2010 |
| 12 | Go | Multi | Static | 2009 |
| 13 | Ruby | OOP | Dynamic | 1995 |
| 14 | R | Statistical | Dynamic | 1993 |
| 15 | MATLAB | Numerical | Dynamic | 1984 |
| 16 | Scala | Multi | Static | 2004 |
| 17 | Dart | OOP | Static | 2011 |
| 18 | Lua | Multi | Dynamic | 1993 |
| 19 | Perl | Multi | Dynamic | 1987 |
| 20 | Haskell | Functional | Static | 1990 |
| 21 | Bash | Scripting | Dynamic | 1989 |
| 22 | PowerShell | Scripting | Dynamic | 2006 |
| 23 | VB.NET | OOP | Static | 2001 |
| 24 | Assembly | Low-level | N/A | 1940s |
| 25 | Objective-C | OOP | Static | 1984 |
| 26 | Groovy | Multi | Dynamic | 2003 |
| 27 | Elixir | Functional | Dynamic | 2011 |
| 28 | Clojure | Functional | Dynamic | 2007 |
| 29 | F# | Multi | Static | 2005 |
| 30 | Erlang | Functional | Dynamic | 1986 |
| 31 | Julia | Multi | Dynamic | 2012 |
| 32 | OCaml | Multi | Static | 1996 |
| 33 | Fortran | Procedural | Static | 1957 |
| 34 | COBOL | Procedural | Static | 1959 |
| 35 | Pascal | Procedural | Static | 1970 |
| 36 | Ada | Multi | Static | 1980 |
| 37 | Prolog | Logic | Dynamic | 1972 |
| 38 | Common Lisp | Multi | Dynamic | 1984 |
| 39 | Scheme | Functional | Dynamic | 1975 |
| 40 | Racket | Multi | Dynamic | 1994 |
| 41 | Nim | Multi | Static | 2008 |
| 42 | Crystal | OOP | Static | 2014 |
| 43 | Zig | Procedural | Static | 2016 |
| 44 | D | Multi | Static | 2001 |
| 45 | Haxe | Multi | Static | 2005 |
| 46 | Tcl | Scripting | Dynamic | 1988 |
| 47 | AWK | Scripting | Dynamic | 1977 |
| 48 | Sed | Scripting | N/A | 1974 |
| 49 | BASIC | Procedural | Dynamic | 1964 |
| 50 | Delphi | OOP | Static | 1995 |
| 51 | CoffeeScript | Multi | Dynamic | 2009 |
| 52 | Elm | Functional | Static | 2012 |
| 53 | PureScript | Functional | Static | 2013 |
| 54 | ReasonML | Functional | Static | 2016 |
| 55 | V (Vlang) | Multi | Static | 2019 |
| 56 | Odin | Procedural | Static | 2016 |
| 57 | Gleam | Functional | Static | 2019 |
| 58 | ABAP | Procedural | Static | 1983 |
| 59 | SQL | Query | Static | 1974 |
| 60 | HTML | Markup | N/A | 1993 |
| 61 | Markdown | Markup | N/A | 2004 |

---

## Summary Table — Esoteric Languages

| # | Language | The Gimmick | Year | Difficulty |
|---|----------|-------------|------|-----------|
| 62 | Brainfuck | 8 commands only | 1993 | ⭐⭐⭐ |
| 63 | Befunge-93 | 2D code grid | 1993 | ⭐⭐⭐ |
| 64 | INTERCAL | Must say PLEASE | 1972 | ⭐⭐⭐⭐ |
| 65 | LOLCODE | LOLcat memes | 2007 | ⭐ |
| 66 | ArnoldC | Schwarzenegger quotes | 2013 | ⭐ |
| 67 | Shakespeare | Shakespearean plays | 2001 | ⭐⭐⭐⭐ |
| 68 | Chef | Cooking recipes | 2002 | ⭐⭐⭐ |
| 69 | Ook! | Orangutan sounds | 2001 | ⭐⭐⭐ |
| 70 | Malbolge | 8th circle of Hell | 1998 | ⭐⭐⭐⭐⭐ |
| 71 | Whitespace | Invisible characters only | 2003 | ⭐⭐⭐⭐ |
| 72 | COW | Moo variations | 2003 | ⭐⭐⭐ |
| 73 | Chicken | One word: chicken | 2008 | ⭐⭐ |
| 74 | JSFuck | 6 JS characters | 2012 | ⭐⭐⭐⭐⭐ |
| 75 | Rockstar | Rock song lyrics | 2018 | ⭐⭐ |
| 76 | Fish (><>) | 2D fish bowl | 2008 | ⭐⭐⭐ |
| 77 | Deadfish | 4 commands, no loops | 2004 | ⭐⭐ |
| 78 | Unlambda | Combinatory logic only | 1999 | ⭐⭐⭐⭐⭐ |
| 79 | FALSE | Stack-based obfuscation | 1993 | ⭐⭐⭐ |
| 80 | /// (Slashes) | String substitution only | 2006 | ⭐⭐⭐ |
| 81 | Piet | Abstract pixel art bitmaps | 2002 | ⭐⭐⭐⭐ |
| 82 | Emojicode | All emojis, actually typed | 2016 | ⭐⭐ |
| 83 | Hexagony | Hexagonal grid, 6 pointers | 2015 | ⭐⭐⭐⭐⭐ |
| 84 | Velato | MIDI music files | 2009 | ⭐⭐⭐⭐⭐ |

---

## Resources

- [Esolangs Wiki](https://esolangs.org) — 6,600+ languages catalogued
- [Rosetta Code](https://rosettacode.org) — Hello World in hundreds of languages
- [Try It Online (TIO)](https://tio.run) — run esolang code in your browser
- [TIOBE Index](https://www.tiobe.com/tiobe-index/) — mainstream language popularity rankings
- [Stack Overflow Developer Survey](https://survey.stackoverflow.co) — real-world language usage data

## Contributing

Found a language missing? Open a PR! There are over 6,600 languages on the Esolangs wiki alone.

## License

Released into the public domain. Use freely, learn joyfully. 🌍
