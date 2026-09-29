# APT44

* Malware : **Industroyer**
* Threat Actor : **APT44**
* Malware Goal : Attack on **Ukraine's** Digital Infrastructure

**29.09.2026**


---

## Information:
```
Basic properties
MD5
a193184e61e34e2bc36289deaafdec37
SHA-1
94488f214b165512d2fc0438a581f5c9e3bd4d4c
SHA-256
7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad
Vhash
115066655d1515556az4dvza6z1
Authentihash
4809faeda710286b4e6d47e5b1962d075818a7d498392188b2ab51b02171fa5d
Imphash
f3fa7eda5f4e7d94a714ad0e0880245e
Rich PE header hash
f6daf61d0ce580dbd845f5b414c4c5fb
SSDEEP
3072:McaprOfoaXmgD31r4VWBvRZoiTprUZNZ9VQ6s6W9:McuOJ2gD31QW51pgE6st9
TLSH
T120D38D12B181C072D1BF19390978D6765B6E7930DF749AD7378802BA9FB40C06E39E6B
File type
Win32 DLL 
executable
windows
win32
pe
pedll
Magic
PE32 executable (DLL) (GUI) Intel 80386, for MS Windows
TrID
Win64 Executable (generic) (29.5%)  Win16 NE executable (generic) (22.8%)  Win32 Executable (generic) (20.3%)  OS/2 Executable (generic) (9.1%)  Generic Win/DOS Executable (9%)
DetectItEasy
PE32  Compiler: EP:Microsoft Visual C/C++ (2013) [DLL32]  Compiler: Microsoft Visual C/C++ (19.00.24210) [LTCG/C++]  Linker: Microsoft Linker (14.00.24210)  Tool: Visual Studio (2015)
Magika
PEBIN
File size
133.50 KB (136704 bytes)
History
First Seen In The Wild
2017-03-12 19:07:29 UTC
First Submission
2016-12-19 10:06:04 UTC
Last Submission
2026-03-02 01:14:00 UTC
Last Analysis
2026-09-29 14:33:01 UTC
Names
fxrhgtw.exe
_7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad.dll
7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad.bin.sample
.bin
industroyer2.exe
7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad_unpacked
7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad
industroyer3
VirusShare_a193184e61e34e2bc36289deaafdec37
myfile.exe
a193184e61e34e2bc36289deaafdec37_RKDDPvfDl.DLL
a193184e61e34e2bc36289deaafdec37.vir
94488f214b165512d2fc0438a581f5c9e3bd4d4c_104.dl
7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad.bin
104.dll
94488F214B165512D2FC0438A581F5C9E3BD4D4C
Portable Executable Info
Compiler Products
[IMP] VS2008 SP1 build 30729 count=5
[---] Unmarked objects count=106
[LT+] VS2015 Update 3 [14.0] build 24210 count=8
[EXP] VS2015 Update 3 [14.0] build 24210 count=1
[RES] VS2015 UPD3 build 24210 count=1
[LNK] VS2015 Update 3 [14.0] build 24210 count=1
id: 0xf1, version: 40116 count=10
id: 0xf3, version: 40116 count=137
id: 0xf2, version: 40116 count=24
id: 0xc7, version: 41118 count=2
```
## Investignation
I read all the information about this file on [VirusTotal](https://www.virustotal.com/gui/file/7907dd95c1d36cf3dc842a1bd804f0db511a0f68f4b3d382c23a3c974a383cad) and found this clue:
<img width="1000" height="68" alt="image" src="https://github.com/user-attachments/assets/9333a716-1c79-4b68-b8c1-d02ec6850e76" />
And I started wondering, what kind of files are these? But I ran into a problem—there was NO information about the dropped files
<img width="1403" height="745" alt="image" src="https://github.com/user-attachments/assets/f409c25c-c4ef-412a-954f-8a98ed99792f" />

Here's what VirusTotal showed. It looks like this investigation might be closed by tomorrow. Bye for now, everyone.
