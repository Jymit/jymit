# Dumb notes 
.
.
.
## scripting languages
A scripting language or script language is a programming language for a runtime system that automates the execution of tasks that would otherwise be performed individually by a human operator. Scripting languages are usually interpreted at runtime rather than compiled.

The action of scripting is essentially writing a series of commands that are interpreted one by one by an application or scripting engine. Even though the script guides the platform through what to do (gives it a script to read and interpret), the execution is performed by the runtime environment and not by the scripting language itself.

```
JavaScript
PHP
Python
Ruby
Groovy
Perl
Lua
Bash
PowerShell
R
VBA
Emacs Lisp
```

## Platform-Specific vs Platform-Agnostic
Scripting languages are platform-specific, while programming languages are platform-agnostic (cross-platform) as they have the ability to execute themselves. For instance, you can run a Java program on any operating system.

## Interpreted vs Compiled
While programming languages are compiled, scripting languages are mostly interpreted — even though there are some scripting languages that are both compiled and interpreted, such as Python and Groovy.

‘Compiled’ means that a programming language has its own compiler that translates the syntax into machine code before runtime. In contrast, scripting languages are interpreted line by line during runtime by the interpreter of the platform they are running on.

## Scripting vs Programming Languages
Platform-specific - 	Platform-agnostic (cross-platform)
(Mostly) interpreted - 	Compiled
Faster at runtime -	Slower at runtime
More code-intensive -	Less code-intensive
Creates standalone apps -	Creates apps as part of a stack



## Obj-C vs Swift
Performance. The official Apple website claims that Swift is 2.6 times faster than Objective-C. However some studies indicate that the difference is not as dramatic. Swift and Objective-C are both statistically typed languages that use the same iOS SDK and the high-quality Low Level Virtual Machine compiler.

Swift is easier to read and easier to learn than Objective-C. Objective-C is over thirty years old, and that means it has a more clunky syntax. ... Also, Swift requires less code. Whereas Objective-C is verbose when it comes to string manipulation, Swift employs string interpolation, without placeholders or tokens.

## Swift

https://www.programiz.com/swift-programming



## Objective-C

Objective-C is the primary programming language you use when writing software for OS X and iOS. It’s a superset of the C programming language and provides object-oriented capabilities and a dynamic runtime. Objective-C inherits the syntax, primitive types, and flow control statements of C and adds syntax for defining classes and methods. It also adds language-level support for object graph management and object literals while providing dynamic typing and binding, deferring many responsibilities until runtime.

apple dev [link](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)


## CPP

C++ is still the go-to language for solutions that need fast machine performance. AAA video games, IoT, embedded systems, and resource-heavy VR and AI applications all run on C or C++.

https://www.educative.io/blog/c-is-a-good-first-language-to-learn#reasons

https://www.w3schools.com/cpp/cpp_functions.asp

A semaphore is generally used as a synchronization object between multiple threads or to protect a limited and finite resource such as a memory or thread pool. The semaphore has a counter which only permits access by one or more threads when the value of the semaphore is non-zero.



## Big O
Big O Notation describes the complexity of your code using algebraic terms.
Space and Time Complexity
Big O notation is one of the most fundamental tools for computer scientists to analyze the cost of an algorithm.

## O(n²) time complexity
O(n²) which is usually pronounced “Big O squared”
The letter “n” here represents the input size
A typical algorithm that has the complexity of O(n²) would be the selection sort algorithm. Selection sort is a sorting algorithm that iterates through the list to ensure every element at index i is the ith smallest/largest element of the list. 

### algos
Selection sort algo
in JS
```function selectionSort(inputArr) { 
    let n = inputArr.length;
        
    for(let i = 0; i < n; i++) {
        // Finding the smallest number in the subarray
        let min = i;
        for(let j = i+1; j < n; j++){
            if(inputArr[j] < inputArr[min]) {
                min=j; 
            }
         }
         if (min != i) {
             // Swapping the elements
             let tmp = inputArr[i]; 
             inputArr[i] = inputArr[min];
             inputArr[min] = tmp;      
        }
    }
    return inputArr;
}
```
```
let inputArr = [5, 2, 4, 6, 1, 3];
selectionSort(inputArr);
console.log(inputArr);
```


### other
clang – a compiler that turns source code into an executable program

gcc – the GNU compiler

git – the save-as-you-go version control system

xcode-select --install

xcode-select -p

brew

https://developer.apple.com/xcode/resources/

https://download.developer.apple.com/Developer_Tools/Command_Line_Tools_for_Xcode_12.5.1/Command_Line_Tools_for_Xcode_12.5.1.dmg

