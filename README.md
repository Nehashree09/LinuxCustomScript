Version 1.0

Overview:
*internsctl is a versatile Linux command utility designed to offer diverse functionalities encompassing CPU, memory, user management, and file information. This Bash script facilitates user interaction with the system, enabling them to retrieve valuable insights through a comprehensive set of commands and options.

Installation,Download the Script:
Copy the internsctl script content from the provided source and save it to a file named internsctl on your local machine.

Making it Executable:
Open a terminal, navigate to the directory containing the internsctl script, and run the following command to make it executable:

`chmod +x internsctl`
Install Dependencies (Optional):

If necessary, install any dependencies required by the script using the following command:

`./internsctl --install`

Usage

Basic Commands Display CPU Information:
` ./internsctl cpu getinfo`

Display Memory Information:
`./internsctl memory getinfo`

Create a New User: 
`./internsctl user create <username>`

List All Regular Users:
`./internsctl user list`

List Users with sudo Permissions:
`./internsctl user list --sudo-only`

Get File Information:
`./internsctl file getinfo <file-name>`

Additional Commands

Get Specific File Information:

Size:
`./internsctl file getinfo --size <file-name>`

Permissions: 
`./internsctl file getinfo --permissions <file-name>`

Owner:
` ./internsctl file getinfo --owner <file-name>`

Last Modified Time:
`./internsctl file getinfo --last-modified <file-name>`

Show Help Information:
`./internsctl --help`

Show Version Information:
`./internsctl --version`

View Manual Page:
`./internsctl --manual`

Examples Display CPU Information:
` ./internsctl cpu getinfo`

Create a New User: 
`./internsctl user create john_doe`

List All Regular Users: 
`./internsctl user list`

List Users with sudo Permissions:
` ./internsctl user list --sudo-only`

Get File Information:
` ./internsctl file getinfo example.txt`

Get Specific File Information:` ./internsctl file getinfo --size example.txt ./internsctl file getinfo --permissions example.txt ./internsctl file getinfo --owner example.txt ./internsctl file getinfo --last-modified example.txt` 

Contributing If you encounter issues or have suggestions for improvements, please create an issue or submit a pull request on the GitHub repository.

License This project is licensed under the Xenon Statck Intern Project - see the LICENSE file for details.

















