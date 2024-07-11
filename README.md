# FIO testing
This FIO command tests sequential and random, reads and writes at 4KiB and 1MiB block sizes. 

# Usage
Install FIO first, then download this repo onto your machine.<br/>

Run in the extracted dir to test the speed of a filesystem<br/>
```sudo fio fio-test.fio --filename=/testdir/testfile.fio --output=fio-output```

Run in the extracted dir to test the speed of a blockdevice directly<br/>
```sudo fio fio-test.fio --filename=/dev/testdevice --output=fio-output```
