# 🌍 Hello, World! — Every Language Edition

> A collection of Hello, World! programs sourced from **[Try It Online (tio.run)](https://tio.run)** and beyond — covering practical, golfing, and esoteric languages.  
> Sorted: mainstream by popularity → golfing languages → esoteric/recreational.  
> **680+ languages** are hosted on TIO. This README covers the most notable ones with annotated examples.

**Quick links:** [Practical](#-practical-languages) · [Golfing](#-code-golfing-languages) · [Esoteric](#-esoteric--recreational-languages) · [Shell/Scripting](#-shellscripting) · [Markup/Query](#-markupquery) · [Run them all](https://tio.run)

---

## 🖥️ Practical Languages

### Python 3
```python
print("Hello, World!")
```
`python hello.py`

---

### Python 2
```python
print "Hello, World!"
```
`python2 hello.py`

---

### JavaScript (Node.js)
```javascript
console.log("Hello, World!");
```
`node hello.js`

---

### TypeScript
```typescript
console.log("Hello, World!");
```
`npx ts-node hello.ts`

---

### Java
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
`javac Main.java && java Main`

---

### C (gcc)
```c
#include <stdio.h>
int main() {
    puts("Hello, World!");
}
```
`gcc -o hello hello.c && ./hello`

---

### C (clang)
```c
#include <stdio.h>
int main() {
    puts("Hello, World!");
}
```
`clang -o hello hello.c && ./hello`

---

### C (tcc — Tiny C Compiler)
```c
#include <stdio.h>
int main() {
    puts("Hello, World!");
    return 0;
}
```
`tcc -run hello.c`

---

### C++ (gcc)
```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
}
```
`g++ -o hello hello.cpp && ./hello`

---

### C++ (clang)
```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!" << std::endl;
}
```
`clang++ -o hello hello.cpp && ./hello`

---

### C# (.NET Core)
```csharp
using System;
class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```
`dotnet run`

---

### C# (Mono)
```csharp
using System;
class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```
`mcs hello.cs && mono hello.exe`

---

### C# (Visual C# Interactive)
```csharp
WriteLine("Hello, World!");
```
`csi hello.csx`

---

### Visual Basic .NET
```vb
Module Hello
    Sub Main()
        Console.WriteLine("Hello, World!")
    End Sub
End Module
```
`dotnet run`

---

### F#
```fsharp
printfn "Hello, World!"
```
`dotnet fsi hello.fsx`

---

### PHP
```php
<?php
echo "Hello, World!\n";
```
`php hello.php`

---

### Ruby
```ruby
puts "Hello, World!"
```
`ruby hello.rb`

---

### Swift
```swift
print("Hello, World!")
```
`swift hello.swift`

---

### Kotlin
```kotlin
fun main() {
    println("Hello, World!")
}
```
`kotlinc hello.kt -include-runtime -d hello.jar && java -jar hello.jar`

---

### Rust
```rust
fn main() {
    println!("Hello, World!");
}
```
`rustc main.rs && ./main`

---

### Go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
`go run hello.go`

---

### Scala
```scala
@main def hello() = println("Hello, World!")
```
`scala hello.scala`

---

### Groovy
```groovy
println "Hello, World!"
```
`groovy hello.groovy`

---

### Dart
```dart
void main() {
  print('Hello, World!');
}
```
`dart hello.dart`

---

### Lua
```lua
print("Hello, World!")
```
`lua hello.lua`

---

### Perl 5
```perl
print "Hello, World!\n";
```
`perl hello.pl`

---

### Perl 6 / Raku
```perl
say "Hello, World!";
```
`raku hello.raku`

---

### Haskell
```haskell
main = putStrLn "Hello, World!"
```
`runhaskell hello.hs`

---

### Elixir
```elixir
IO.puts("Hello, World!")
```
`elixir hello.exs`

---

### Erlang
```erlang
-module(hello).
-export([start/0]).
start() -> io:fwrite("Hello, World!\n").
```
`erl -noshell -s hello start -s init stop`

---

### Clojure
```clojure
(println "Hello, World!")
```
`clojure hello.clj`

---

### Common Lisp
```lisp
(format t "Hello, World!~%")
```
`sbcl --script hello.lisp`

---

### Scheme (Guile)
```scheme
(display "Hello, World!")
(newline)
```
`guile hello.scm`

---

### Racket
```racket
#lang racket
(displayln "Hello, World!")
```
`racket hello.rkt`

---

### OCaml
```ocaml
let () = print_endline "Hello, World!"
```
`ocaml hello.ml`

---

### Standard ML
```sml
print "Hello, World!\n";
```
`sml hello.sml`

---

### CakeML
```sml
print "Hello, World!";
```
`cake hello.cml`

---

### Julia
```julia
println("Hello, World!")
```
`julia hello.jl`

---

### R
```r
cat("Hello, World!\n")
```
`Rscript hello.R`

---

### MATLAB
```matlab
disp('Hello, World!')
```
`matlab -batch "run('hello.m')"`

---

### Nim
```nim
echo "Hello, World!"
```
`nim compile --run hello.nim`

---

### Crystal
```crystal
puts "Hello, World!"
```
`crystal hello.cr`

---

### Zig
```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```
`zig run hello.zig`

---

### D
```d
import std.stdio;
void main() { writeln("Hello, World!"); }
```
`dmd -run hello.d`

---

### Haxe
```haxe
class Hello {
    static function main() {
        trace("Hello, World!");
    }
}
```
`haxe --main Hello --interp`

---

### Tcl
```tcl
puts "Hello, World!"
```
`tclsh hello.tcl`

---

### Ada (GNAT)
```ada
with Ada.Text_IO;
use Ada.Text_IO;

procedure Main is
begin
  Put_Line ("Hello, World!");
end Main;
```
`gnatmake hello.adb && ./hello`

---

### Fortran
```fortran
program hello
    print *, "Hello, World!"
end program hello
```
`gfortran -o hello hello.f90 && ./hello`

---

### COBOL (GNU)
```cobol
PROGRAM-ID.H.PROCEDURE
DIVISION.DISPLAY "Hello, World!".
```
`cobc -free -x -o hello hello.cob && ./hello`

---

### Pascal (FPC)
```pascal
program Hello;
begin
  writeln('Hello, World!');
end.
```
`fpc hello.pas && ./hello`

---

### Delphi / Object Pascal
```pascal
program Hello;
{$APPTYPE CONSOLE}
begin
  Writeln('Hello, World!');
end.
```
Compile with `dcc32 Hello.dpr`.

---

### Prolog (SWI-Prolog)
```prolog
:- initialization(main, main).
main(_) :- write('Hello, World!'), nl.
```
`swipl hello.pl`

---

### Objective-C
```objc
#import <Foundation/Foundation.h>
int main() {
    @autoreleasepool {
        NSLog(@"Hello, World!");
    }
    return 0;
}
```
`clang -framework Foundation hello.m -o hello && ./hello`

---

### Assembly (nasm, x64, Linux)
```nasm
section .text
global _start
_start:
mov edx,13
mov ecx,msg
mov ebx,1
mov eax,4
int 0x80
mov eax,1
xor ebx,ebx
int 0x80
section .data
msg db "Hello, World!",0xa
```
`nasm -f elf64 hello.asm && ld -o hello hello.o && ./hello`

---

### Assembly (fasm, x64, Linux)
```nasm
format ELF executable 3

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, 13
    int 0x80
    mov eax, 1
    mov ebx, 0
    int 0x80

msg db "Hello, World!"
```
`fasm hello.asm && ./hello`

---

### Assembly (as, x64, Linux)
```asm
.print "Hello, World!"
```
`as -o hello.o hello.s && ld -o hello hello.o && ./hello`

---

### CIL (Mono IL Assembler)
```cil
.assembly Program {}
.assembly extern mscorlib {}
.method static void Main()
{
     .entrypoint
     .maxstack 1
     ldstr "Hello, World!"
     call void [mscorlib]System.Console::WriteLine(string)
     ret
}
```
`ilasm hello.il && mono hello.exe`

---

### APL (Dyalog Unicode)
```apl
⎕←'Hello, World!'
```
`dyalog -script hello.apl`

---

### APL (Dyalog Classic)
```apl
⎕←'Hello, World!'
```

---

### APL (dzaima/APL)
```apl
⎕←'Hello, World!'
```

---

### APL (ngn/apl)
```apl
⎕←'Hello, World!'
```

---

### J
```j
'Hello, World!'
```
`jconsole hello.ijs`

---

### K (ngn/k)
```k
"Hello, World!"
```

---

### ALGOL 68 (Genie)
```algol68
print("Hello, World!")
```
`a68g hello.a68`

---

### ABC
```abc
WRITE "Hello, World!"
```
`abc hello.abc`

---

### Agda
```agda
open import IO
main = run (putStr "Hello, World!")
```
`agda --compile hello.agda && ./hello`

---

### ATS2
```ats
implement
main0 () = print("Hello, World!")
```
`patscc -o hello hello.dats && ./hello`

---

### Attache
```attache
Print["Hello, World!"]
```
`attache hello.@`

---

### BeanShell
```java
print("Hello, World!");
```
`bsh hello.bsh`

---

### Boo
```boo
print "Hello, World!"
```
`booc hello.boo && mono hello.exe`

---

### Brat
```brat
p "Hello, World!"
```
`brat hello.brat`

---

### Ceylon
```ceylon
shared void run() {
    print("Hello, World!");
}
```
`ceylon run hello`

---

### Chapel
```chapel
write("Hello, World!");
```
`chpl hello.chpl -o hello && ./hello`

---

### Clean
```clean
module main
Start:: String
Start = "Hello, World!"
```
`clm -b -o hello hello && ./hello`

---

### CLIPS
```clips
(printout t "Hello, World!")
(exit)
```
`clips -f hello.clp`

---

### Cobra
```cobra
class Program
    def main
        print 'Hello, World!'
```
`cobra hello.cobra`

---

### Coconut
```coconut
"Hello, World!" |> print
```
`coconut hello.coco && python hello.py`

---

### Cryptol
```cryptol
:set ascii=on
"Hello, World!"
```

---

### Curry (PAKCS)
```curry
main = putStr "Hello, World!"
```
`pakcs :l hello :main`

---

### D2
```d2
"r8$.s$o;Hello, World!
```

---

### Dafny
```dafny
method Main() {
    print "Hello, World!";
}
```
`dafny hello.dfy`

---

### Dyvil
```dyvil
class Main {
    static func main(args: [String]) = print 'Hello, World!'
}
```

---

### eC
```ec
class HelloApp : Application
{
    void Main()
    {
        PrintLn("Hello, World!");
    }
}
```
`ecp hello.ec && ecc hello && ./hello`

---

### Egel
```egel
import "io.ego"
using IO
def main = print "Hello, World!"
```

---

### bc
```bc
print "Hello, World!";

```
`bc hello.bc`

---

### dc
```dc
[Hello, World!]P
```
`dc hello.dc`

---

### Io
```io
write("Hello, World!\n")
```
`io hello.io`

---

### Janet
```janet
(print "Hello, World!")
```
`janet hello.janet`

---

### Logtalk
```logtalk
:- initialization(
    write('Hello, World!'), nl
).
```
`logtalk_run hello.lgt`

---

### Pony
```pony
actor Main
  new create(env: Env) =>
    env.out.print("Hello, World!")
```
`ponyc hello && ./hello`

---

### Red
```red
print "Hello, World!"
```
`red hello.red`

---

### Rexx
```rexx
say 'Hello, World!'
```
`rexx hello.rexx`

---

### Seed7
```seed7
$ include "seed7_05.s7i";
const proc: main is func
begin
  writeln("Hello, World!");
end func;
```
`s7 hello.sd7`

---

### Self
```smalltalk
('Hello, World!' printNl)
```

---

### Simula 67
```simula
BEGIN
   OutText("Hello, World!");
   Outimage;
END
```
`cim hello.sim && ./hello`

---

### Smalltalk (GNU)
```smalltalk
Transcript show: 'Hello, World!'.
```
`gst hello.st`

---

### SNOBOL4
```snobol4
        OUTPUT = "Hello, World!"
END
```
`snobol4 hello.sno`

---

### Squirrel
```squirrel
print("Hello, World!\n");
```
`sq hello.nut`

---

### Terra
```terra
local C = terralib.includec("stdio.h")
terra main()
  C.puts("Hello, World!")
end
main()
```
`terra hello.t`

---

### Typed Racket
```racket
#lang typed/racket
(displayln "Hello, World!")
```
`racket hello.rkt`

---

### Wren
```wren
System.print("Hello, World!")
```
`wren hello.wren`

---

### XQuery
```xquery
"Hello, World!"
```

---

### Yabasic
```basic
print "Hello, World!"
```
`yabasic hello.yab`

---

### Zimbu
```zimbu
FUNC Main() $
  IO.Print("Hello, World!~n")
$
```

---

## 🐚 Shell/Scripting

### Bash
```bash
echo Hello, World!
```
`bash hello.sh`

---

### Dash
```sh
echo Hello, World!
```
`dash hello.sh`

---

### Zsh
```zsh
echo Hello, World!
```
`zsh hello.zsh`

---

### Fish (shell)
```fish
echo Hello, World!
```
`fish hello.fish`

---

### Ksh
```ksh
echo Hello, World!
```
`ksh hello.ksh`

---

### Tcsh
```tcsh
echo Hello, World!
```
`tcsh hello.tcsh`

---

### Bosh
```sh
echo Hello, World!
```

---

### AWK (GNU)
```awk
BEGIN { print "Hello, World!" }
```
`awk -f hello.awk`

---

### Sed (GNU)
```bash
echo "" | sed 's/.*/Hello, World!/'
```

---

### ed
```ed
a
Hello, World!
.
wq
```
`ed hello.txt < hello.ed && cat hello.txt`

---

### PowerShell
```powershell
Write-Host "Hello, World!"
```
`pwsh hello.ps1`

---

## 🏷️ Markup/Query

### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Hello</title></head>
<body><h1>Hello, World!</h1></body>
</html>
```

---

### SQL (SQLite)
```sql
SELECT 'Hello, World!' AS message;
```
`sqlite3 :memory: "SELECT 'Hello, World!' AS message;"`

---

### XQuery
```xquery
"Hello, World!"
```

---

### XSLT
```xml
<?xml version="1.0"?>
<xsl:stylesheet xmlns:xsl="http://www.w3.org/1999/XSL/Transform" version="1.0">
<xsl:template match="/">
Hello, World!
</xsl:template>
</xsl:stylesheet>
```

---

### ABAP
```abap
REPORT zhello.
WRITE: / 'Hello, World!'.
```
Run in SAP GUI → transaction `SE38`.

---

### Markdown
```markdown
# Hello, World!
```

---

## ⛳ Code Golfing Languages

> These languages are designed for writing the shortest possible programs. Most have implicit Hello World or compressed string support.

---

### 05AB1E
```
"Hello, World!"
```
[Try it](https://tio.run/#05ab1e)

---

### 05AB1E (legacy)
```
"Hello, World!"
```

---

### 2sable
```
"Hello, World!"
```

---

### Jelly
```
"3ḷXṂṄ⁸⁾⁾Ẇ»
```
Jelly's compressed string literal for "Hello, World!" — [Try it](https://tio.run/#jelly)

---

### GolfScript
```
"Hello, World!"
```
[Try it](https://tio.run/#golfscript)

---

### CJam
```
"Hello, World!"
```
[Try it](https://tio.run/#cjam)

---

### Pyth
```
"Hello, World!"
```
[Try it](https://tio.run/#pyth)

---

### Husk
```
"Hello, World!"
```
[Try it](https://tio.run/#husk)

---

### Pip
```
"Hello, World!"
```
[Try it](https://tio.run/#pip)

---

### Stax
```
"Hello, World!"
```
[Try it](https://tio.run/#stax)

---

### Vyxal
```
`Hello, World!`
```
[Try it](https://tio.run/#vyxal)

---

### Add++
```
D,f,^,"Hello, World!"
$f
O
```

---

### Actually
```
H
```
`H` is the built-in "Hello, World!" literal in Actually. One byte.

---

### Canvas
```
Hello, World!
```

---

### Carrot
```
Hello, World!
```

---

### Charcoal
```
Hello, World!
```

---

### Brachylog v2
```
"Hello, World!"w
```

---

### Burlesque
```
,"Hello, World!"Q
```

---

### Convex
```
"Hello, World!
```

---

### Crayon
```
"Hello, World!"q
```

---

### Deorst
```
'Hello, World!'O
```

---

### Gol><> (Golfish)
```
"!dlroW ,olleH"r!|lolo
```

---

### Ly
```
"Hello, World!"op
```

---

### Commata (,,,)
```
"Hello, World!
```

---

### Cy
```
"Hello, World!" :<
```

---

### ARBLE
```
"Hello, World!"
```

---

### Arcyóu
```
"Hello, World!"
```

---

### Anyfix
```
"Hello, World!"
```

---

### Chain
```
Hello, World!
```

---

### Check
```
"Hello, World!"o
```

---

### Deorst
```
'Hello, World!'O
```

---

### Cubically
```
+53@6+1F2L2+0@6L2F2U3R3F1L1+2@66L3F3R1U1B3+0@6:4U1R1+00@6-000@6+50000@6+000000@6+2-000000@6-5+4000@6-00@6/0+00@6:0+0/0+00@6
```

---

### Cubix
```
./v.o;@?/"!dlroW"S',u/"Hello"
```

---

### Ceres
```
389960998265612367812323333 115dÆP
```

---

### Cardinal
```
%"Hello, World!";x
```

---

### Braingolf
```
"Hello, World!"&@
```

---

### BuzzFizz
```
print "Hello, World!"
```

---

### Keg
```
"Hello, World!"
```

---

## 🤪 Esoteric / Recreational Languages

> Listed roughly by notoriety. There are 6,600+ on the [Esolangs Wiki](https://esolangs.org). All of the below run on [Try It Online](https://tio.run).

---

### brainfuck
> 8 commands. Turing complete. Inspired hundreds of derivatives.
```brainfuck
--<-<<+[+[<+>--->->->-<<<]>]<<--.<++++++.<<-..<<.<+.>>.>>.<<<.+++.>>.>>-.<<<+.
```
[Try it](https://tio.run/#brainfuck)

---

### Befunge-93
> 2D code grid. Instruction pointer can travel in any direction.
```befunge
"!dlroW ,olleH">:#,_@
```
[Try it](https://tio.run/#befunge)

---

### Befunge-96 (MTFI)
```befunge
"Hello, World!"i>:#,_@
```

---

### Befunge-97 (MTFI)
```befunge
q"Hello, World!"i#]:#,_@
```

---

### Befunge-98 (FBBI)
```befunge
"9!dlroW ,olleH"ck,@
```
[Try it](https://tio.run/#befunge-98)

---

### INTERCAL
> Requires the word `PLEASE` — too few and the compiler refuses to run (insufficiently polite).
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
[Try it](https://tio.run/#intercal)

---

### LOLCODE
> Based on LOLcat internet memes.
```lolcode
HAI 1.4
  VISIBLE "Hello, World!"
KTHXBYE
```
[Try it](https://tio.run/#lolcode)

---

### ArnoldC
> Every keyword is an Arnold Schwarzenegger quote.
```arnoldc
IT'S SHOWTIME
TALK TO THE HAND "Hello, World!"
YOU HAVE BEEN TERMINATED
```
[Try it](https://tio.run/#arnoldc)

---

### Shakespeare (SPL)
> Programs look like Shakespearean plays. Characters are variables.
```shakespeare
The Tragedy of Hello World.
Romeo, a young man with remarkable patience.
Juliet, a likewise young woman of remarkable grace.
Act I: The only act.
Scene I: The beginning.
[Enter Romeo and Juliet]
Juliet: You are as pretty as the sum of yourself and a big mighty proud kingdom.
Romeo: Speak your mind!
[Exeunt]
```
[Try it](https://tio.run/#spl)

---

### Chef
> Programs are cooking recipes. Variables are ingredients.
```chef
Hello World.

Ingredients.
 72 l H
101 l e
108 l l
111 l o
 44 l _comma
 32 l _space
 87 l w
114 l r
100 l d
 33 l _bang

Method.
Put _bang into the mixing bowl.
Put d into the mixing bowl.
Put l into the mixing bowl.
Put r into the mixing bowl.
Put o into the mixing bowl.
Put w into the mixing bowl.
Put _space into the mixing bowl.
Put _comma into the mixing bowl.
Put o into the mixing bowl.
Put l into the mixing bowl.
Put l into the mixing bowl.
Put e into the mixing bowl.
Put H into the mixing bowl.
Pour contents of the mixing bowl into the baking dish.

Serves 1.
```
[Try it](https://tio.run/#chef)

---

### Ook!
> Brainfuck but in orangutan sounds: `Ook.` `Ook?` `Ook!`
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
[Try it](https://tio.run/#ook)

---

### Malbolge
> Named after the 8th circle of Hell. So hard the first Hello World took 2 years to find.
```malbolge
('&%:9]!~}|z2Vxwv-,POqponl$Hjig%eB@@>}=<M:9wv6WsU2T|nm-,jcL(I&%$#"
`CB]V?Tx<uVtT`Rpo3NlF.Jh++FdbCBA@?]!~|4XzyTT43Qsqq(Lnmkj"Fhg${z@>
```
[Try it](https://tio.run/#malbolge)

---

### Whitespace
> Only spaces, tabs, and newlines matter. All other characters are comments.
```
(File is invisible — download from TIO or any Whitespace repository)
```
[Try it](https://tio.run/#whitespace)

---

### COW
> Brainfuck variant where commands are variations of "moo".
```cow
MoO MOo MOo moO MoO moO MoO moO moO MoO moO MoO moO moO MoO MOO MoO MoO MoO
MoO MOO moO MoO MoO MoO MOO moO MoO MoO MoO MoO moO MOo MOo moO MoO MoO MoO
mOo mOo mOo MOo moo mOo MOo moo mOo MoO MoO MoO moo moO moO moO Moo moO MOo
MOo moO MOo Moo moO Moo Moo MoO moO MoO MoO MoO MoO moO MoO MoO MoO Moo MoO
moO MOo MOo moO MOO moO MOo Moo mOo mOo moo
```
[Try it](https://tio.run/#cow)

---

### Chicken
> The only valid token is the word `chicken`. Line length = opcode.
```chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken chicken
chicken chicken
chicken chicken chicken chicken chicken chicken chicken chicken chicken
```
[Try it](https://tio.run/#chicken)

---

### JSFuck
> JavaScript using only `(` `)` `[` `]` `!` `+`. Runs in any browser console.
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
`node hello.js` or paste in browser console. [Try it](https://tio.run/#jsfuck)

---

### Rockstar
> Programs are also valid rock ballads.
```rockstar
Shout "Hello, World!"
```
[Try it online](https://codewithrockstar.com/online) · [TIO](https://tio.run/#rockstar)

---

### Fish (`><>`)
> 2D language where the pointer wraps like a fish in a bowl.
```fish
"!dlroW ,olleH">:#,_@
```
[Try it](https://tio.run/#fish)

---

### Deadfish~
> `w` is the built-in "Hello, World!" command. The tilde variant added it.
```deadfish
w
```
[Try it](https://tio.run/#deadfish-)

---

### Deadfish (original)
> Only 4 commands: `i` (increment), `d` (decrement), `s` (square), `o` (output). No loops.
```deadfish
iisiiiisiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiioddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiiiiiiiiiiiio
```

---

### Unlambda
> Functional language using only combinatory logic. No variables, no data types.
```unlambda
`r```````````.H.e.l.l.o.,. .W.o.r.l.d.!i
```
[Try it](https://tio.run/#unlambda)

---

### FALSE
> The language that directly inspired Brainfuck. Stack-based, 1024-byte compiler.
```false
"Hello, World!"
```
[Try it](https://tio.run/#false)

---

### `///` (Slashes)
> One operation: string substitution. `/find/replace/text`.
```
Hello, World!
```
[Try it](https://tio.run/#slashes)

---

### Piet
> Programs are bitmap images (PNG files). Named after Piet Mondrian.
```
[PNG image file — see https://www.bertnase.de/npiet/npiet-execute.php]
```
[Try it online](https://www.bertnase.de/npiet/npiet-execute.php) · [TIO](https://tio.run/#piet)

---

### Emojicode
> Statically typed, object-oriented language using only emojis.
```emojicode
🏁 🍇
  😀 🔤Hello, World!🔤❗️
🍉
```
[Try it](https://tio.run/#emojicode)

---

### Hexagony
> Code arranged in a hexagonal grid. Six instruction pointers.
```hexagony
H;e;l;l;o;,; ;W;o;r;l;d;!<@
```
[Try it](https://tio.run/#hexagony)

---

### Velato
> Programs are MIDI files. Intervals between notes encode instructions.
```
(MIDI file — see Java Velato interpreter)
```

---

### Aceto
> 2D language based on a Hilbert curve.
```aceto
o,or
l Wl
le!d
"H"p
```
[Try it](https://tio.run/#aceto)

---

### Aheui (esotope)
> A Korean esolang where commands are Korean syllable blocks.
```aheui
발따밤따빠받나파빠밣다빠밦다빠받타밢밢따밦다밤밣따밦밦따빠밣다파받따빠받다파빠빠밠타밣밢따아멓희 
```
[Try it](https://tio.run/#aheui)

---

### Alchemist
> Based on chemical reactions.
```alchemist
_->Out_"Hello, World!"
```
[Try it](https://tio.run/#alchemist)

---

### Alice
> Dual-mode 2D language switching between cardinal and ordinal movement.
```alice
/OH!lloo /
@""edlr,W\ 
```
[Try it](https://tio.run/#alice)

---

### Ante
> Programs are poker hands. Cards are operations.
```ante
9♦8♥J♦A♦2♣3♥7♠J♦A♦7♦J♦J♦A♦3♦J♦5♥6♦4♥J♥A♥6♠6♠J♥A♦8♦J♦A♦8♠J♦A♦3♦J♦A♦6♠J♦A♦8♠J♦A♥3♦2♠J♥A♥2♣6♠J♥
```
[Try it](https://tio.run/#ante)

---

### AsciiDots
> Programs look like ASCII art circuits with traveling dots.
```asciidots
.-$"Hello, World!"
```
[Try it](https://tio.run/#asciidots)

---

### Backhand
> Instruction pointer skips every other cell.
```backhand
"ol!,ld elWHro"
```
[Try it](https://tio.run/#backhand)

---

### Beatnik
> Instructions are determined by the Scrabble score of words.
```beatnik
K QQQQQQQG ZD XO K QQJA KD ZD XO K KG KD ZD ZD ZD XO XO K B KD ZD XO K QQQQF ZD ZD XO K QQQD XO K A Z KD XO ZD XO K B KD XO ZD XO K J Z XO K QQQB XO
```
[Try it](https://tio.run/#beatnik)

---

### Beeswax
> 2D language using bees.
```beeswax
_`Hello, World!
```
[Try it](https://tio.run/#beeswax)

---

### Bitwise Cyclic Tag
> Based on the Cyclic Tag system. Only 0s and 1s.
```bct
1111111111111111111111111111111111111111111111111111111110110...
```

---

### Boolfuck
> Brainfuck where cells are single bits.
```boolfuck
;;;+;+;;+;+;+;+;+;+;;+;;+;;;+;;+;+;;+;;;+;;+;+;;+;+;;;;+;+;;+;;;+;;+;+;+...
```
[Try it](https://tio.run/#boolfuck)

---

### Bot Engine
> Programs control a simple robot.
```botengine
vHello, World!
>eeeeeeeeeeeeeP
```
[Try it](https://tio.run/#bot-engine)

---

### Brain-Flak
> Only matching brackets. Turing-complete. Everything is a balanced string of `(){}[]<>`.
```brainflak
(((((((((((()()()()){}){}){}()))){}{}())[][][][])[][])[[]]())[[][][][][]]())([([]([])[][]{})]()()()([[]](([()()()]([([][][])](((({}()){}))){}{})))))\n(run with -A flag)
```
[Try it](https://tio.run/#brain-flak)

---

### Brainbash
> Brainfuck but with a bash backend.
```brainbash
--->->->>+>+>>+[++++[>+++[>++++>-->+++<<<-]<-]<+++]>>>.>-->-.>..+>++++>+++.+>-->[>-.<<]
```
[Try it](https://tio.run/#brainbash)

---

### Braingolf
> Stack-based golfing language.
```braingolf
"Hello, World!"&@
```
[Try it](https://tio.run/#braingolf)

---

### Bubblegum
> Compressed binary programs — everything is a compressed string.
```
(binary — see TIO)
```
[Try it](https://tio.run/#bubblegum)

---

### BuzzFizz
> A language with keywords based on the FizzBuzz game.
```buzzfizz
print "Hello, World!"
```
[Try it](https://tio.run/#buzzfizz)

---

### Cardinal
> 2D language with 4 pointer directions.
```cardinal
%"Hello, World!";x
```
[Try it](https://tio.run/#cardinal)

---

### Cascade
> Programs are waterfalls of characters.
```cascade
"
H
e
l
l
o
,
 
W
o
r
l
d
!
```
[Try it](https://tio.run/#cascade)

---

### Changeling
> 2D language where the grid changes shape.
```changeling
(2D grid — see TIO)
```
[Try it](https://tio.run/#changeling)

---

### Commentator
> Programs are entirely inside C-style comments.
```commentator
(72 spaces then /*# per character — see TIO)
```
[Try it](https://tio.run/#commentator)

---

### Condit
> Condition-driven language.
```condit
when H=""then set H="Hello, World!"put H
```
[Try it](https://tio.run/#condit)

---

### Cood
> "I'm very hungry" style language.
```cood
I want 72 of this.
I'm very hungry.
I want 101 of this.
I'm very hungry.
...
```
[Try it](https://tio.run/#cood)

---

### Cubically
> Programs manipulate a Rubik's cube. ASCII values come from face values.
```cubically
+53@6+1F2L2+0@6L2F2U3R3F1L1+2@66L3F3R1U1B3+0@6:4U1R1+00@6...
```
[Try it](https://tio.run/#cubically)

---

### Deadfish (all variants)
> `iisiiiisiiiiiiiio...` (long sequence) — or use the `~` variant with just `w`.

---

### Dodos
> Mathematical language based on a simple number function.
```dodos
	2 4 2
	1 5 3
	...
```
[Try it](https://tio.run/#dodos)

---

### Dreaderef
> Memory access language.
```dreaderef
chro "H"
chro "e"
chro "l"
chro "l"
chro "o"
chro ","
chro " "
chro "W"
chro "o"
chro "r"
chro "l"
chro "d"
chro "!"
```
[Try it](https://tio.run/#dreaderef)

---

### Drive-In Window
> Programs are fast-food orders.
```diw
Hi, welcome to X. Here is a menu.
C:$30
G:$70
...
May I take your order?
Person 1 would like the G with b.
...
```
[Try it](https://tio.run/#drive-in-window)

---

### Element
> Stack-based with escape characters.
```element
Hello\,\ World\!`
```
[Try it](https://tio.run/#element)

---

### 2DFuck
> 2D Brainfuck variant.
```2dfuck
.!.!..!.!....!..!..!.!.!.!.!..!.!..!...!..!.!..!...!..!.!....!..!.!.!..!....!.!......!.!.!.!.!...!.!..!.!....!.!...!..!.!..!..!.!..!...!..!..!.!....!.!....!.
```
[Try it](https://tio.run/#2dfuck)

---

### 2L
> Two-line 2D language.
```2l
*   +
*+*
 ************************************************************************+
+  +
                                 +                                      +
 +                            +*
   *********************************+
+                               +
  +                                +
```
[Try it](https://tio.run/#2l)

---

### 3var
> Only three variables.
```3var
iisssaa/>emaa->e#aamam->e#dddddddddddddddddddddddPiiiiiiiiiiiiiiiiiiiiiiiiiiiiiP...
```
[Try it](https://tio.run/#3var)

---

### 7
> Highly compressed stack-based language.
```7
5325101303040432004513151401430134321027403
```
[Try it](https://tio.run/#7)

---

### 99
> Variables are repeated 9s. Arithmetic via counting nines.
```99
999 9 9
99 99999999 999 9
99
...
```
[Try it](https://tio.run/#99)

---

### a-gram
> Based on I Ching hexagrams using Unicode trigram/hexagram symbols.
```a-gram
☰䷩䷩䷩䷩䷩䷩䷩䷏䷩䷩䷩䷩䷩䷩䷩䷩⚌
...
```
[Try it](https://tio.run/#a-gram)

---

### A Pear Tree
> Obfuscated Python hidden behind a Christmas carol.
```a-pear-tree
#r3TQJ
print("Hello, World!")
```
[Try it](https://tio.run/#a-pear-tree)

---

### AlphaBeta
> Alphabet-based esolang.
```alphabeta
kjjjggDLeaCLcbbbCLLaaaCLjjjggDLjhhDLsFihhDLCLaaaCLdaaaaCLdaaCLsFiiDL
```
[Try it](https://tio.run/#alphabeta)

---

### Alphuck
> Brainfuck where commands are letters a–h.
```alphuck
iiciccepepceaiiiaiaiaicccsascciijceeeeeejccijjccjcejaajaajcccjeeejaajaaijcccej
```
[Try it](https://tio.run/#alphuck)

---

### Alumin
> Stack-based esoteric language.
```alumin
hhdtdadhatdoddhhhgahhhhhadohhhhhhhadodohhhadoydhhgddhhdtdaaohhhhcoyhhhhhddaaaoydohhhadohhhdacdohhdtdacohhhco
```
[Try it](https://tio.run/#alumin)

---

### Aubergine
> Memory-based esolang.
```aubergine
=aA-a1=oA=bi+b1-Ab-bb:bA+B1=iBGolf by Quintopia
!dlroW ,olleH
```
[Try it](https://tio.run/#aubergine)

---

### Beam
> Data travels through a beam network.
```beam
'''''''''>`++++++++)@'''''''>`++++)+@+++++++@@+++@L...
```
[Try it](https://tio.run/#beam)

---

### Bean
> Ultra-compact binary language.
```
(binary xxd format — see TIO)
```
[Try it](https://tio.run/#bean)

---

### Braille
> Programs use Braille Unicode characters.
```braille
⠆⠄⡒⡆⡘⠀⠊⠦⢦⠗⢾⠽⠂⢢⢾⢦⢦⠮⢄
```
[Try it](https://tio.run/#braille)

---

### Brian & Chuck
> Two tapes interact — Brian reads Chuck, Chuck reads Brian.
```brian-chuck
_#Jgnnq."Yqtnf#_{?
#{<{>-?>--.>?
```
[Try it](https://tio.run/#brian-chuck)

---

### Broccoli
> A green, healthy Lisp-like language.
```broccoli
(print "Hello, World!")
```
[Try it](https://tio.run/#broccoli)

---

### Bitwise Fuckery
> Brainfuck extended with bitwise operations.
```bwfuckery
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++.+++++++++++++++++++++++++++++.+++++++..+++.%+++++++++++...
```
[Try it](https://tio.run/#bwfuckery)

---

### Alice & Bob
> Concurrent language with two stacks.
```alice-bob
(((((((((((()()()()){}){}){}()))){}{}())[][][][])[][])[[]]())[[][][][][]]())(...)
```
[Try it](https://tio.run/#alice-bob)

---

### Bitch / bitch (bit-h) / bitch (shifty)
> Minimal bit-manipulation language.
```bitch
#72/#101/#108/#108/#111/#44/#32/#87/#111/#114/#108/#100/#33/
```
[Try it](https://tio.run/#bitch)

---

### BitChanger
> Bit manipulation esolang using `<`, `>`, `{`, `}`.
```bitchanger
<<<<<}<<<<}<<<}<<<}
...
```
[Try it](https://tio.run/#bitchanger)

---

### Bitwise
> Explicit bit-level operations.
```bitwise
MOV 1    &1 &1
OUT &72  1
OUT &101 1
...
```
[Try it](https://tio.run/#bitwise)

---

### BitCycle
> Programs route bits through a 2D circuit.
```bitcycle
?!
(with args 72,101,108,108,111,44,32,87,111,114,108,100,33)
```
[Try it](https://tio.run/#bitcycle)

---

### Bit
> Programs declare individual bits, then assemble them into bytes.
```bit
BIT 0
BIT 1
BIT 0
...
BYTES 8
PRINT
PRINTLN
```
[Try it](https://tio.run/#bit)

---

### BitBitJump
> One-instruction set computer based on bit copying.
```bitbitjump
start: .deref p X
       .testH X print -1
print: .out X
       ...
```
[Try it](https://tio.run/#bitbitjump)

---

### Binary Lambda Calculus
> Lambda calculus encoded in binary.
```
(binary file — 2a 48 65 6c 6c 6f ...)
```
[Try it](https://tio.run/#blc)

---

### Bubblegum
> Every program is a compressed string.
```
(15 bytes of compressed data — see TIO)
```
[Try it](https://tio.run/#bubblegum)

---

### Commercial
> Language styled as advertising copy.
```commercial
"Hello, World!" - Satisfied Consumer of Hello
Hello has been selling out worldwide!
```
[Try it](https://tio.run/#commercial)

---

## 📊 Summary Table — Practical Languages (Top 50)

| # | Language | Category | Year | Run command |
|---|----------|----------|------|-------------|
| 1 | Python 3 | Multi-paradigm | 1991 | `python hello.py` |
| 2 | JavaScript | Multi-paradigm | 1995 | `node hello.js` |
| 3 | Java | OOP | 1995 | `javac Main.java && java Main` |
| 4 | C (gcc) | Procedural | 1972 | `gcc -o hello hello.c && ./hello` |
| 5 | C++ (gcc) | Multi-paradigm | 1985 | `g++ -o hello hello.cpp && ./hello` |
| 6 | C# | Multi-paradigm | 2000 | `dotnet run` |
| 7 | TypeScript | Multi-paradigm | 2012 | `npx ts-node hello.ts` |
| 8 | PHP | Multi-paradigm | 1994 | `php hello.php` |
| 9 | Swift | Multi-paradigm | 2014 | `swift hello.swift` |
| 10 | Kotlin | Multi-paradigm | 2011 | `kotlinc ... && java -jar` |
| 11 | Rust | Systems | 2010 | `rustc main.rs && ./main` |
| 12 | Go | Systems | 2009 | `go run hello.go` |
| 13 | Ruby | OOP | 1995 | `ruby hello.rb` |
| 14 | R | Statistical | 1993 | `Rscript hello.R` |
| 15 | MATLAB | Numerical | 1984 | `matlab -batch ...` |
| 16 | Scala | Multi-paradigm | 2004 | `scala hello.scala` |
| 17 | Dart | OOP | 2011 | `dart hello.dart` |
| 18 | Lua | Multi-paradigm | 1993 | `lua hello.lua` |
| 19 | Perl 5 | Multi-paradigm | 1987 | `perl hello.pl` |
| 20 | Haskell | Functional | 1990 | `runhaskell hello.hs` |
| 21 | Bash | Scripting | 1989 | `bash hello.sh` |
| 22 | Elixir | Functional | 2011 | `elixir hello.exs` |
| 23 | Clojure | Functional | 2007 | `clojure hello.clj` |
| 24 | F# | Multi-paradigm | 2005 | `dotnet fsi hello.fsx` |
| 25 | Erlang | Functional | 1986 | `erl -noshell -s hello start` |
| 26 | Julia | Multi-paradigm | 2012 | `julia hello.jl` |
| 27 | OCaml | Multi-paradigm | 1996 | `ocaml hello.ml` |
| 28 | Fortran | Procedural | 1957 | `gfortran -o hello hello.f90` |
| 29 | COBOL | Procedural | 1959 | `cobc -x -o hello hello.cob` |
| 30 | Pascal | Procedural | 1970 | `fpc hello.pas` |
| 31 | Ada | Multi-paradigm | 1980 | `gnatmake hello.adb` |
| 32 | Nim | Multi-paradigm | 2008 | `nim compile --run hello.nim` |
| 33 | Crystal | OOP | 2014 | `crystal hello.cr` |
| 34 | Zig | Systems | 2016 | `zig run hello.zig` |
| 35 | D | Multi-paradigm | 2001 | `dmd -run hello.d` |
| 36 | APL | Array | 1966 | `dyalog -script hello.apl` |
| 37 | Haxe | Multi-paradigm | 2005 | `haxe --main Hello --interp` |
| 38 | Common Lisp | Multi-paradigm | 1984 | `sbcl --script hello.lisp` |
| 39 | Scheme | Functional | 1975 | `guile hello.scm` |
| 40 | Racket | Multi-paradigm | 1994 | `racket hello.rkt` |
| 41 | Standard ML | Functional | 1990 | `sml hello.sml` |
| 42 | Prolog | Logic | 1972 | `swipl hello.pl` |
| 43 | Tcl | Scripting | 1988 | `tclsh hello.tcl` |
| 44 | AWK | Scripting | 1977 | `awk -f hello.awk` |
| 45 | Objective-C | OOP | 1984 | `clang -framework Foundation ...` |
| 46 | ALGOL 68 | Multi-paradigm | 1968 | `a68g hello.a68` |
| 47 | Groovy | OOP | 2003 | `groovy hello.groovy` |
| 48 | Smalltalk | OOP | 1972 | `gst hello.st` |
| 49 | Simula | OOP | 1967 | `cim hello.sim` |
| 50 | COBOL (GNU) | Procedural | 1959 | `cobc -x -o hello hello.cob` |

---

## 📊 Summary Table — Esoteric Languages

| Language | Gimmick | Year | Difficulty |
|----------|---------|------|-----------|
| brainfuck | 8 commands only | 1993 | ⭐⭐⭐ |
| Befunge-93 | 2D code grid | 1993 | ⭐⭐⭐ |
| INTERCAL | Must say PLEASE | 1972 | ⭐⭐⭐⭐ |
| LOLCODE | LOLcat memes | 2007 | ⭐ |
| ArnoldC | Arnie quotes | 2013 | ⭐ |
| Shakespeare | Shakespearean plays | 2001 | ⭐⭐⭐⭐ |
| Chef | Cooking recipes | 2002 | ⭐⭐⭐ |
| Ook! | Orangutan sounds | 2001 | ⭐⭐⭐ |
| Malbolge | 8th circle of Hell | 1998 | ⭐⭐⭐⭐⭐ |
| Whitespace | Invisible chars | 2003 | ⭐⭐⭐⭐ |
| COW | Moo variations | 2003 | ⭐⭐⭐ |
| Chicken | One word: chicken | 2008 | ⭐⭐ |
| JSFuck | 6 JS chars | 2012 | ⭐⭐⭐⭐⭐ |
| Rockstar | Rock ballads | 2018 | ⭐⭐ |
| Fish (><>) | 2D fish bowl | 2008 | ⭐⭐⭐ |
| Deadfish~ | `w` = Hello World | 2004 | ⭐ |
| Unlambda | Combinatory logic | 1999 | ⭐⭐⭐⭐⭐ |
| FALSE | Inspired Brainfuck | 1993 | ⭐⭐⭐ |
| /// (Slashes) | String substitution | 2006 | ⭐⭐⭐ |
| Piet | Pixel art bitmaps | 2002 | ⭐⭐⭐⭐ |
| Emojicode | All emojis, typed | 2016 | ⭐⭐ |
| Hexagony | Hexagonal grid | 2015 | ⭐⭐⭐⭐⭐ |
| Velato | MIDI music files | 2009 | ⭐⭐⭐⭐⭐ |
| Aheui | Korean syllables | 2003 | ⭐⭐⭐ |
| Alice | Dual-mode 2D | 2017 | ⭐⭐⭐⭐ |
| Ante | Poker hand programs | 2011 | ⭐⭐⭐⭐ |
| Beatnik | Scrabble scores | 2001 | ⭐⭐⭐⭐ |
| Brain-Flak | Only brackets | 2016 | ⭐⭐⭐⭐⭐ |
| Braille | Braille Unicode | 2016 | ⭐⭐⭐ |
| Cubically | Rubik's cube | 2017 | ⭐⭐⭐⭐⭐ |
| Drive-In Window | Fast-food orders | 2016 | ⭐⭐⭐ |
| Rockstar | Rock song lyrics | 2018 | ⭐⭐ |
| 2DFuck | 2D Brainfuck | 2014 | ⭐⭐⭐ |
| 7 | Compressed stack | unknown | ⭐⭐⭐⭐⭐ |
| 99 | Nines everywhere | 2014 | ⭐⭐⭐ |
| a-gram | I Ching hexagrams | 2019 | ⭐⭐⭐ |

---

## Resources

- **[Try It Online (TIO)](https://tio.run)** — 680+ languages, runs in your browser
- **[Esolangs Wiki](https://esolangs.org)** — 6,600+ esoteric languages catalogued
- **[Rosetta Code](https://rosettacode.org)** — Hello World tasks in hundreds of languages
- **[TIOBE Index](https://www.tiobe.com/tiobe-index/)** — mainstream language popularity
- **[Stack Overflow Developer Survey](https://survey.stackoverflow.co)** — real-world usage data
- **[Code Golf Stack Exchange](https://codegolf.stackexchange.com)** — community using golfing languages

## Contributing

Found a language missing? Open a PR! There are 6,600+ on the Esolangs wiki alone, and TIO adds new ones regularly.

## License

Released into the public domain. Use freely, learn joyfully. 🌍
