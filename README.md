ZeusBanking Trojan Analysis
Objective

The ZeusBanking Trojan Analysis project aimed to establish a controlled environment to understand how malware works, how to detect it, and how to handle it. In this project, I used the ZeusBanking malware as a basis to achieve these objectives.

Skills Learned

Advanced understanding of how a Malware works.
Proficiency in analyzing and interpreting a Malware.
Ability to use detection and analysis tools.
Enhanced knowledge of security vulnerabilities.
Development of critical thinking and problem-solving skills in cybersecurity.

Tools Used

REMnux as Malware analysis toolkit.
FlareVM as controlled enviroment.
Analysis and detection tools such as PeStudio, CAPA, Cutter, Procmon.

Steps

Ref 1: VirusTotal output to the .exe archive
![VirusTotal output to the  exe archive](https://github.com/user-attachments/assets/3f26ef0b-d898-44ed-ba83-70728c7151cf)

Ref 2: Export domain reported by PeStudio.
![export domain reported by PeStudio](https://github.com/user-attachments/assets/5166fd1d-f53e-4853-a748-6f49b70fa2ed)

Ref 3: Raw and virtual size of the archive.
![Raw size and virtual size almost the same, probably the file isn’t packed](https://github.com/user-attachments/assets/ac8469b1-0f63-41aa-9b42-0b586aba4c84)

Ref 4: CAPA output.
![CAPA output](https://github.com/user-attachments/assets/80725249-a537-46dd-8ab2-1997f24f76d4)

Ref 5: Execution behavior on the API calls “GetTickCount” and “AllowSetForegroundWindow”.
![Execution behavior on the API calls “GetTickCount” and “AllowSetForegroundWindow”](https://github.com/user-attachments/assets/7783e9ac-f03f-4c9d-8f13-d443993b81d5)

Ref 6: “CellrotoCrudUntohighCols” and “KERNEL32.CreateFile executions
![“CellrotoCrudUntohighCols” and “KERNEL32 CreateFile executions](https://github.com/user-attachments/assets/bcddf630-01a9-4b7a-997f-53b8e3719ad3)

Ref 7: After the .exe execution the file deleted itself, but a process with the same name stills running.
![After the  exe execution the file deleted itself, but a process with the same name stills running](https://github.com/user-attachments/assets/1340db04-1c1e-4284-af05-2cb2734d4e61)

Ref 8: Console running in background.
![Console running in background](https://github.com/user-attachments/assets/6c0162b4-281d-4f38-b05d-a39fc7112d71)

Ref 9: GET Request captured after the malware execution.
![GET Request captured after the malware execution](https://github.com/user-attachments/assets/823caeb4-7b63-41a9-95f4-00414fada462)

Ref 10: DLL found in the same folder than the invoice.exe that is running in background, created after the malware execution.
![DLL found in the same folder than the invoice exe that is running in background, created after the malware execution](https://github.com/user-attachments/assets/abdea71d-2e0a-4b2a-9b6c-b0ad22d1ac2b)
