# Writeup DF-IR

- https://www.linkedin.com/pulse/aero-ctf-forensics-challenge-memory-dump-ighor-tavares/
- https://gist.github.com/1259iknowthat/8cb818f0a37566b1fc25151ef074d9af

```bash
vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.pslist | grep conhost.exe

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.netscan | grep LISTENING

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.filescan | grep conhost.exe

vol -f Windows\ 10\ x64-ff6b1a74.vmem windows.dumpfiles --pid 3022
```
