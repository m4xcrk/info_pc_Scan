# info_pc_Scan
You can see information on all the hardware, like the motherboard, memory, and printers. It also displays the Windows product key and ID, a list of installed software, and all the currently running processes, among many other things



Install Required Libraries:

#bash
Copy code
pip3 install paramiko
pip3 install psutil

#
Ensure SSH Access:
Make sure SSH is enabled on the remote machines, and you have the necessary credentials to access them.


Explanation
Network Scanning:

scan_network(subnet, username, password): Scans the given subnet for active hosts and retrieves their details using SSH.
Retrieving System Information:

get_remote_computer_details(ip, username, password): Connects to a remote computer using SSH and retrieves details.
GUI:

tkinter is used to create a simple GUI where you can input the subnet, SSH username, and password, and trigger the network scan.
Treeview displays the results in a table format.
