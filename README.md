# CHGSTR

REXX version of the ANSI REXX CHANGESTR for use with z/OS

CHGSTR was inspired by the ANSI REXX CHANGESTR for use under z/OS REXX.

Since you can't have a member name longer than 8 characters the name was
changed to CHGSTR.

Install the code into either a library in the SYSEXEC allocation or in
the SYSPROC allocation.

The syntax is: `new_string = chgstr(needle,haystack,new_needle)`

Examples:

`new_string = chgstr('def','abcdefghi','zzz')`

with new_string being `abzzzdefghi`
