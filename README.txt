= makea

* FIX (url)

== DESCRIPTION:

=== Scenarios

==== Cairngorm

starting at .
in the flex/src root directory in the com.site package structure

make a 

cairngorm

[options]
* directory structure
* model locator named FooModelLocator
* front controller named FooFrontController
* service locator
* command sequence named DoThing
  - which is composed of
    > a command named DoThingCommand
    > an event named DoThingEvent
* responder sequence named GetThingFromServer using the D delegate
    > a responder named GetThingFromServerCommand
    > an event named GetThingFromServerEvent

if it doesn't already exist

==== Rails

starting at .

make a 

rails

[options]
* project named foo
* migration named foo
* model named foo with properties bar, which is a string and baz which is an integer
 - which includes
	> a unit test for foo
	> a fixture file for foo

* controller named foo with actions bar and baz
* scaffold named foo with properties bar, which is a string
(You get the picture)

== FEATURES/PROBLEMS:

* FIX (list of features or problems)

== SYNOPSIS:

  FIX (code sample of usage)

== REQUIREMENTS:

* FIX (list of requirements)

== INSTALL:

* FIX (sudo gem install, anything else)

== LICENSE:

(The MIT License)

Copyright (c) 2008 Tony Hillerson

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.