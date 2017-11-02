# Vexillium
Vexillium - DOM based fuzzer for browser based on Google's Domato
	Copyright Cycure Labs 2017. Licensed under Apache 2.0

# How-to Use
    To use this fuzzer, simply open the browser you want to fuzz and visit http://rajesh.sillycon.org:1337/
    To simply check the status of the fuzzer, visit http://rajesh.sillycon.org:1337/status

# Notes
Vexillium uses Google's Domato as the generator to generate testcases for the fuzzer, and flask to serve you the fuzzer online.

# Bugs
    Some testcases leads the flask server to keep the pipeline open, due to which for some testcases the page stops refresh automatically. Don't worry just press the refresh manually and it would work perfectly fine.

# Contact
If there is something, you want to let us know shoot us a mail at: contact@cycurelabs.com
