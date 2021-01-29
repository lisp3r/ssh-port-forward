# Bash script to setup SSH Port Forwarding
Perfect for creating Bash/ZSH/*SH aliases around

Usage:  ./ssh-port-forward <forward_name> <local_port> <forwarded_host> <forwarded_port> <ssh_host>
        ./ssh-port-forward -f <config_file>

common options:
    -f <config file>
    -b <forward_name>       Opens the specified forward in the default browser
    -h|--help               Prints this help message
    -k <forward_name>       Closes the forward by the specified name
    -l                      Lists all currently forwarded ports

SSH options:
    -i <identity_file>      Specify ssh keyfile to use for authentication
    -p <ssh_port>           Specify a port that the ssh server is running on

Browser options:
    -s                      Use HTTP instead of HTTPS when opening in the browser
    -o                      Setup forwarding and open in browser


When run, creates a $FORWARD_NAME-ssh.run file in /var/run/user/$UID/ssh-port-forward/ which contains the PID of ssh, the local port, remote host, and remote port.

If /var/run/user/$UID/ does not exist, script will exit 1


Thanks to:
	- https://ryanstutorials.net/bash-scripting-tutorial/bash-functions.php for showing me the syntax for functions (and making quips about their use of paraenthesis)
	- http://tldp.org/LDP/abs/html/complexfunct.html for bash function tips
	- http://tldp.org/LDP/abs/html/fto.html for testing file / folder / socket existence
	- http://tldp.org/* at this point for teaching me everything
	- https://gist.github.com/scy/6781836 for some intersting ssh backgrounding information that I did not make use of
	- first comment at $ABOVE for linking me to $BELOW
	- second comment at https://stackoverflow.com/questions/2241063/bash-script-to-setup-a-temporary-ssh-tunnel/15198031#15198031 for introducing me to ssh control sockets (which are super cool)
	- the colorado school of mines for breaking me so much that after finished finals all I wanted to do is create more work for myself
	- people on stack overflow for teaching me bash scripting (and everything else I know)
	- the maker of the statue of liberty for being french
	- the dinosaur on the Firefox "Unable to connect" page for being cute the *-thousand time I forgot how to script
	- madeon for creating music to accompany me
