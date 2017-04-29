<a href="http://www.sackfix.org/"><img src ="http://www.sackfix.org/assets/sf_logo.png" /></a>

# SackFix

A Scala Fix Engine implementation.  It is a full implementation of the session level protocol, tested using the sackfix tester project, supporting acceptor and initiators using AKKA and Scala.

To get started simply download the [examples project](https://github.com/PendaRed/sackfixexamples) and start the acceptor and then the initiator.   The SackFix suite consists of

* [Examples](https://github.com/PendaRed/sackfixexamples): This is all you need!
* [Tester](https://github.com/PendaRed/sackfixtests): A very simple test suite to stress out any Session level implementation.
* [Session](https://github.com/PendaRed/sackfixsessions): All of the statemachines and message handling for the Fix Session.  ie the business logic lives here.
* [Messages](https://github.com/PendaRed/sackfixmessages): Code generated Fix Messages for all versions of fix.
* [Common](https://github.com/PendaRed/sackfix): The code generator and common classes - including all the code generated Fields.

Full documentation is at [SackFix.org](http://www.sackfix.org/).

## Versions

JDK 1.8, Scala 2.11, SBT 0.13.12, Akka 2.4.16.   Feel free to upgrade.

# What is this project?

SackFix is a Scala Fix Engine - ie a session layer fix implememtion including all messages and fields as strongly typed classes.   This project includes example code on how to write your own Fix acceptor or initiator 
using AKKA.   This is probably the only project you should copy - and then cut and paste the code you want into your own projects.

Please visit [sackfix.org](http://www.sackfix.org) for instructions on how to run the initiator and acceptor.

Best wishes,
Jonathan

<a href="http://www.sackfix.org/"><img src ="http://www.sackfix.org/assets/sackfix.png" /></a>
