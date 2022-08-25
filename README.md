# cisco_security
cisco security device

1.	Create a virtual environment for python
a.	python3 -m venv ftd_virtual_env
2.	activate the virtual environment
a.	source ftd_virtual_env/bin/activate
3.	Install necessary file
a.	pip3 install fireREST 
b.	pip3 install netaddr 
c.	pip3 install datetime 
d.	pip3 install ipaddress
4.	Move into the location where the script is located, run the command and provide necessary variable
a.	python3 policyCSV.py 
i.	Enter the IP Address of the FMC: 
ii.	Enter the username for the FMC: 
iii.	Enter the password associated with the username entered: 
Reference: https://github.com/raghukul-cisco/csvExportFirepower
