## Table of Content
- [Overview](#overview)
- [History](#history)
- [Installation](#installation)
- [Modules](#modules)
- [Appendix](#appendix)

## Overview
- Javascript is world’s most misunderstood language. It’s the only language where people don’t bother to learn before they use.
- Javascript (JS) is a lightweight interpreted or just-in-time compiled programming language with first-class functions. It was developed to run on the client side of the Web Browser.
- While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat.
- Javascript is a prototype-based, multi-paradigm, dynamic language, supporting object-oriented, imperative, and declarative styles.
- Javascript borrows most of its syntax from Java, but it is also influenced by Awk, Perl, and Python. 

---
## History
- Java and Javascript are two different programing languages, but they are entangled in evolution chain. To understand Javascript evolution, we have to start with Java.
    - In **1991, The Green Project at Sun Micro Systems(now Oracle)** begins looking for a purpose. They take apart many electronic devices, like cable TV set-top boxes and remote controls to find a way for the appliances to talk to each other.
    - The Green Project (Naughton, Gosling and Sheridan) settles on smart consumer electronics as the delivery platform. **Gosling** starts development of a **new programming language and by August 1991, James Gosling at Sun created a language C++ ++**. His friends asked to name it something else and then he called it as **Oka (on the name of tree found outside his window)**.
    - By **October 1992**, 7 inch a cross between a PDA and a remote control, is ready. This is demoed to **Scott McNealy** who is blown away. Following that demo, the Green Project is set up as **First Person Inc**, a wholly owned Sun subsidiary.
    - In **early 1993**, The Green Project hears about a **Time-Warner request for proposal for a setup box operating system**. First Person Inc quickly shifts focus from smart consumer electronics (which is proving to be more hype than reality) to the **setup box OS market**, and place a bid with Time-Warner. They lose the bid.
    - In **early 1994**, First Person Inc concludes that like smart consumer electronics setup boxes were more hype than reality. Without a market to be seen **First Person is rolled back into Sun**.
    - During the same time, there was another history in the making *The Internet*. In **1993, Mosaic** was the popular browser available from **National Center for Supercomputing Applications (NCSA)**.
    - After failing at interactive media, people at Sun sat together in a coffee shop to figure out what they have to do with Oak and decided rename it to **Java by Gosling after looking at the menu**.
    - In **1994**, a team of Java developers started writing **Web Runner, which was a clone of the internet browser Mosaic**. It was based on the Java programming language. The name Web Runner was a tribute to the Blade Runner movie. Web Runner's first public demonstration was given by **John Gage and James Gosling at the Technology Entertainment Design Conference in Monterey, California in 1995**. It was later renamed **Hot Java, it was officially announced in May the same year at the Sun World conference**.
    - **Hot Java was a modular, extensible web browser from Sun Microsystems implemented in Java**. It was the first browser to support **Java applets**, and was Sun's demonstration platform for the then-new technology.
    - During the same time in **13 October 1994, Netscape Communications** created the proprietary **web browser, Netscape Navigator**. Several original Mosaic authors worked on Navigator.
    - This was a cold war era between **Sun Micro Systems, Microsoft and Netscape**. 
        - Microsoft and Sun sell rival operating systems for business computers that power the Internet. The two clash over competing e-business software that companies use to build Web sites. Their rivalry even extends to office productivity software, with Sun pushing StarOffice as an alternative to Microsoft's popular Office.
        - Microsoft had largely ignored the web (and the Internet at large) for some time. You have to go and purchase a browser separately and its enterprise customers, however, began to ask for this kind of support. To support this Microsoft started working with Netscape. This did not go well and created "Browser War"
            - Netscape’s version, Microsoft came to them with an ultimatum. Join up or move out of the way.
            - Microsoft’s version, the meeting went off without a hitch. In a long, but productive exchange, the two companies shared ideas and visions for the future. Later they created Internet Explorer. 
    - In **1995, Netscape Communications hired Brendan Eich (Co-Founder of Mozilla)** with the promise of letting him implement **Scheme (a Lisp dialect) in the browser**. Before this happened, Netscape got in touch with **Sun Microsystems to include Java in the navigator browser to compete with Microsoft**.
    - Due to the popularity and easy programming of Java, Netscape decided that a scripting language had to have syntax similar to that of Java. **Eich wrote the initial prototype in just 10 days in May 1995**.

        Language | Inspired Attributes
        --- | ---   
        Javascript | Prototype Inheritance and Dynamic Objects
        Java | Syntax and Conventions
        Schema | Loose Typing and Object as first class values
        Perl | Regular Expression

    - Javascript's first code name was **Mocha**, later changed it to **LiveScript**, for trademark reasons. In early **December 1995, Sun licensed the trademark Javascript to Netscape**. The language was renamed to its final name, Javascript.
    - During the same time Microsoft created a clone of Javascript and called it as **JScript in 1996**. They planned to **replace the language with VBScript**.
    - Netscape alarmed with Microsoft development and submitted the language for standardization to **ECMA (European Computer Manufacturer’s Association) in 1998** and because of trademark issues, the standardized version of the language was stuck with the awkward name **ECMAScript**. Because of the power of Microsoft in ECMA, it allowed language to be created with bug and deliver. 

        Year | Name | Description
        --- | --- | ---
        1997 | ECMAScript 1 | First Edition
        1998 | ECMAScript 2 | Editorial changes only
        1999 | ECMAScript 3 | Added Regular Expressions. Added try/catch. Unicode 2.1 or later
        NA| ECMAScript 4 | Was never released
        2009 | ECMAScript 5 | Added "strict mode". Added JSON support. Unicode 3 or later
        2011 | ECMAScript 5.1 | Editorial changes
        2015 | ECMAScript 6 | Added classes and modules
        2016 | ECMAScript 7 | Added exponential operator (**). Added Array.prototype.includes.
    
    - After a decade things changed, Microsoft acknowledged Javascript as a mainstream language for the WEB. To overcome the shortcomings of the language Microsoft created a transpiler called **TypeScript and was first made public in October 2012**. 

---
## Installation
- There are multiple ways to start working with Javascript 
    - Online IDE 
        - [Codepen](https://codepen.io/)
        - [Scrimba](http://scrimba.com)
        - [JSfiddle](https://jsfiddle.net/)
    - Browser Dev Tools
        - [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/)
        - [Firefox Dev Tools](https://developer.mozilla.org/en-US/docs/Tools)
    - Server Environments
        - [Nodejs](https://nodejs.org/en/)
        - [SpiderMonkey](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey)
        - [Java Nashorn](https://openjdk.java.net/projects/nashorn/)
- This tutorial is based on `Visual Studio Code` and `Node.js`. I will be adding a separate tutorial both and will update references here. 

---
## Modules
- There are multiple modules of the language that we have to go through to master Javascript Language.
    - Basics
        - Comments
        - Variables
        - Data Types
        - Operators
        - Statements 
        - Loops
        - Exception Handling
    - Advance
        - Event Loop
        - Objects
        - Arrays
        - Functions
        - Modules
        - Regular Expressions
        - Memory Management
    - ES6 and Beyond
        - ES6
            - Data Types
                - Let
                - Const
                - Symbol
                - Proxy
                - Template Literals
                - Multi-line Strings
                - Destructing Assignment
            - Data Structures
                - Set
                - Weak Set
                - Map
                - Weak Map 
            - Loops
                - For of
                - Iterator
                - Generator
            - Object Enhancements
                - Enhanced Object Literals
                - Classes
            - Functions
                - Default Parameters
                - Promises
                - Arrow Functions
            - Module
                - Module Loader

---
## Appendix
- Reference
    - [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
    - [Microsoft Vscode](https://code.visualstudio.com/)