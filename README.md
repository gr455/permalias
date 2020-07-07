# permalias
Add an alias to bash permanently with one command

# Usage

1. Copy the script to /bin/ directory (sudo required for the copy)
	
	`sudo cp permalias /bin/permalias`

2. Run

	`permalias <alias> <command> <user>`

# Examples

1. `permalias doc docker-compose`

2. `permalias hello "echo 'hello world'"`

3. `permalias hello "echo 'hello world'" grass` (if I want to add the alias for 'grass' user. user argument is also needed if running as root)