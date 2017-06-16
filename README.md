# CLIpboard
A simple application to send snippets of text and files over their network

## Commands

`CLIpboard listen`  
  
Goes into receiving mode. 
  
`CLIpboard send [IP].[GOES].[RIGHT].[HERE] [text]`  
  
sends text to the given IP, if it's in recieving mode.

`CLIpboard send [IP].[GOES].[RIGHT].[HERE] < [stdin]`  
 
 sends information from stdin to the given IP, if it's in recieving mode.
