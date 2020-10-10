# Flipping-LED-Lights-for-SAS-Drives
Flipping the LED indicator lights for SAS drives using sdparm.
<br />

We are using sdparm command line utitlity for performing this task.
<br />

# #sdparm.<br />
sdparm is a new command line utility designed to get and set
SCSI disk parameters (cf hdparm for ATA disks). More generally
it gets and sets mode page information on SCSI devices or devices
that use a SCSI command set. <br />
<br />

# Use the below command for temporarily Flip the activity LED of the SAS drive. <br />

# #sdparm --set=RLM /dev/sdX <br />
Note: Replace the "X" with the drive letter. <br />
<br />
<br />

# Use the below command for permenently Flip the activity LED of the SAS drive. <br />

# #sdparm --set=RLM --save /dev/sdX <br />
Note: Replace the "X" with the drive letter. <br />
<br />
<br />

# Use the below command for clear the RLM. <br />

# #sdparm --clear=RLM /dev/sdX <br />
Note: Replace the "X" with the drive letter. <br />
<br />
<br />

# LRM = Ready Light Meaning. <br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# Thanks!!! <br />





