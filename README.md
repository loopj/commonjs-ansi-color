ANSI Color Code Output Support for CommonJS
===========================================

This CommonJS module provides basic ANSI color code support, to allow you to
format your console output with foreground and background colors as well as
providing bold and underline support.

Tested on node.js.

Basic usage:
-----------

    // Load the module
    var color = require("ansi_color");

    // Print the word "Error" to stdout in red
    console.log(color("Error", "red"));

    // Print the word "Error" in red and underlined
    console.log(color("Error", "red+underline"));

    // Print the word "Success" in bold green, followed by a message
    console.log(color("Success", "green+bold"), "Something was successful!");