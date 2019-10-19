##U nix  terminal networking commands## V1.0 ##
###Unix based networking cheat sheet
######################################

######################################

Syntax - Netstat


netstat [-a] [-b] [-e] [-f] [-n] [-o] [-p Protocol] [-r] [-s] [-t] [-x] [-y] [Interval]



The combination of the individual options works by stringing the individual parameters together, each separated by a space:

netstat [-OPTION1] [-OPTION2] [-OPTION3] …



The parameters are typically preceded by a hyphen (-), but if you want to combine several options, you only have to place this hyphen in front of the first element. Instead of the variant shown above, you can also link different parameters as follows:

netstat [-OPTION1][OPTION2][OPTION3] …




netstat -a - Displays all active ports
netstat -b - Displays the executable file of a connection or listening port (requires admin rights)
