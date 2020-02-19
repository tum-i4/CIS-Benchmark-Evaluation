# CIS Benchmark Evaluation

In this repository, we have collected our evaluation data.
For each benchmark:

1. We have set up a clean VM with the tested OS.
If the tested software was not an OS, the software was installed on a Windows 10 instance.
2. We installed the CIS-CAT tool on the VM.
3. We executed the OVAL checks of the tested CIS benchmark with the CIS-CAT tool on the VM.
The results are stored as `before.html`.
4. Next, we executed the automatic remediation of the benchmark using our generated scripts.
5. Finally, we executed the OVAL checks again.
This time, the results are stored as `after.html`.
