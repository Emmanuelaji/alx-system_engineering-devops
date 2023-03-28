Tasks
0. Create a file
mandatory
Using Puppet, create a file in /tmp.

Requirements:

File path is /tmp/school
File permission is 0744
File owner is www-data
File group is www-data
File contains I love Puppet

GitHub repository: alx-system_engineering-devops
Directory: 0x0A-configuration_management
File: 0-create_a_file.pp

1. Install a package
mandatory
Using Puppet, install flask from pip3.

Requirements:

Install flask
Version must be 2.1.0
File: 1-install_a_package.pp

2. Execute a command
mandatory
Using Puppet, create a manifest that kills a process named killmenow.

Requirements:

Must use the exec Puppet resource
Must use pkill
Example:

Terminal #0 - starting my process
File: 2-execute_a_command.pp
