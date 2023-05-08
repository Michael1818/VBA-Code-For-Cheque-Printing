# VBA-Code-For-Cheque-Printing
If you work in treasury, like I do, and you raise cheques by writing, you may find the code here useful if you have multiple cheques of the same amounts to write.

# How it works

Usually the name of the beneficiaries and amount to pay are in two coluwns in Excel.

# Create a new module in VBA
From Excel under the developer tab, go to Visual basic, and create a new module, name it, paste the code and save.

The code loops over one of the columns, which represents the changing names of the beneficiaries, while the second column contains constant amounts payable to each beneficiary.

i have yet to discover how to loop on the two columns together.

If there is power outage during the production, the printer may not print the rest of the cheque by itself, so you need to know where the production stopped, to pick up from there.

# Tools Needed
I use a Laserjet Pro MFP M130a for this, I cut out the number of cheques i need to write per amount leaving the stub, fix the cheques, and fit the shutter to hold the cheques properly on both sides. 
Ensure your printer toner cartridge is ok so the printing is sharp.



# Benefits
With this simple VBA code, I have been able to print in less than 3 hours what it takes 3 of my colleagues about 3 days to write, and i do it in a neat and orderly way. Now tell me why I won't love coding.

Let me know your thoughts on this repo @SeunMicGeek on twitter
