# MacADDR
A lookup tool for MAC addresses

## Description
This is an example of how you'd use OCaml to determine the vendor for various MAC addresses.  A MAC address is a six-digit hexadecimal code unique to your networking hardware (network card).  The first three hex numbers are assigned to specific vendors, and the last three are reserved for identifying the specific card.

This tool illustartes how to use OCaml to connect to a remote HTTP service (in this case a mac address lookup tool), make a request, and display the value.  

## Operation

This tool relies on the `ocamlnet` library, and maybe compiled to a standalone executable with the command-line invocation shown in the top of the file.

When run, the following output should be expected:

`N/A
Apple, Inc.
Cisco Systems, Inc
Intel Corporate
`
