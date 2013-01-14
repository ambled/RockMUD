RockMUD
=======

RockMUD 0.1.5

History:
RockMUD was spawned out of my love of MUDs and too many late night coffees. 

Doing what I can to keep a test server running on nodejitsu: http://moreoutput.rockmud.jit.su/. Client 'terminal' will be
addressed soon. You can reach me directly: moreoutput@gmail.com.

Goals:
* A Diku-like MUD experience from within the browser using HTML5 and NodeJS.
* Typography is a feature.
* Everything is JavaScript / JSON.

Notes on dependencies: 
* Not using a Node MVC framework. 
* Client side I use DOJO 1.8
* socket.io >= .9
* Node > .8.3

Currently in 0.1.5:
* Simple architecture with no whitelisting of commands
* Character creation (Races, Classes, Stats, Passwords) and saving as json files.
* Channels
* Uniform way of scripting commands -- with permission checking
* JSON areas with room parsing of items, monsters, exits
* Command aliases defined client side.
* Various 'standard' commands: who, look, help, score, save, title, quit, get, drop
* Basic Combat
* Inventory
* AMD loader for client side scripts

