
# Command
# Command Structure
It is the way of Defining the Command.It defines the structure of command.Every Linux Command consist of three Parts
1. Command name 2.Option (Given by -sign) and 3. Argument ,parameter for execution(file name or string)
 		      +--------------+
                      |   Command    |
                      +------+-------+
                             |
                             ^
          +-------------------------------------+
          |                  |                  |
+---------+--------+   +-----+-------+    +-----+-----------+
|  Command Name    |   |Options      |    |  argument       |
+------------------+   +-------------+    +-----------------+

example of command using  options 
$ readit -a https://www.github.com/

# Execution Of Multiple Commands
User can execute more than one command in single statment by separating commands with a semicolon(;)
example : $readit -a https://www.google.co.in ; readit -v


#Use of Secondary Prompt
If a user is unable to complete the command within a line and press enter key then system displays the secondary prompt '>' to continue the command on next line.
eg. $ echo "GOOD
 >>MORNING ! "

# Command Substitution
It is the way of substituting the output of any command at the required place.User can enclose the Command within quote for placing output of any command at desired place.
example.
$echo "my terminal filename is 'tty'
Output:my terminal filenames is /dev/tty01
