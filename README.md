# Misc
Some miscellaneous scripts and whatnot

#Autonet.ulp
This is a script I wrote back in 2004 that enables users to generate circuit designs using a scripting language. It parses the .ulp file or allows the user to run commands to connect groups of nets en-masse for repetitive circuits using older versions of EAGLE PCB CAD. The usefulness of this is that for building things with repetitive nets, the user can write a script to define the nets and autonet.ulp will connect them in EAGLE. Difficulties with this were that the ULP syntax is a /very/ limited subset of the C language, so parsing the syntax of the commands and the .ulp files was tricky using the limited string manipulation functions. 
