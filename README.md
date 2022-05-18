# Serilog.Enrichers.WithCaller

Performance of this approach is *low* due to Reflection and Diagnostic. However, it's helpful if you need the method Parameters and Values in your log output.

Example OutputTemplate: [{Timestamp:HH:mm:ss} {Level:u3}] {Message} (at {Caller}){NewLine}{Exception}

* Since version 1.1.0 (thanks to 0xced), supports including file info in caller property
* Since version 1.2.0 (thanks to Khaos66), supports adding max frame depth of stack 
* Since version 1.2.1 only polish of code and improved ReadMe

### how to use, code example see unit test code

### Note: version 1.3.0 is abandoned (there is no nuget), support for templates is out of the box from Serilog
