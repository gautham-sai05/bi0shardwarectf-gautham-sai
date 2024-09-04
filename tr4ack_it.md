#**tr4ack_it**<br>

##**Objective**:<br>Examine the log file in the file and find the flag<br>

##Steps taken:<br>

**1.** Downloaded the given file and found the file format(squashfs) and using unsquash command unzipped the file<br>

**2.** Opened the file and got inside the file 

**3.** Used grep command to find date since logs contain them 

**4.** Got the logs and sorted them

**5.** Substracted the serial numbers of adjacent entries to get a set of numbers which was converted to ascii to get flag

**6.**Entered the flag
