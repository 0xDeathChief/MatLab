1. Extract Or Mount R2024a_Windows

2. Run setup.exe go in upper right corner in  "Advanced Options"  select setup mode  "I have a File Installation Key"
     If internet access is absent then required setup mode will be auto-selected and you do not need to select it manually

3. When you will be asked to  "Enter File Installation Key"  enter

##### **Full desktop**
- `21471-07182-41807-00726-32378-34241-61866-60308-44209-03650-51035-48216-24734-36781-57695-35731-64525-44540-57877-31100-06573-50736-60034-42697-39512-63953`

MATLAB Parallel Server:
- `43296-06676-07870-11638-24594-37138-06914-15363-16593-04565-51182-24173-61441-08788-59492-28817-10943-02487-06356-22775-14309-64503-07854-49011-55634`

4. When you will be asked to  "Select License File"  select file  `"license.lic"`  from folder with  `R2024a_Windows.iso`  file

MATLAB Production Server:
`40343-25684-40525-09488`

Polyspace Bug Finder + Polyspace Code Prover:
`15315-49347-54135-38668`

Polyspace Bug Finder Server + Polyspace Code Prover Server:
`45569-59682-06610-64133`

DO Qualification Kit + IEC Certification Kit:
`42610-52008-16202-14804`

5. go in Crack copy .dll and apply it on C:\Program Files\MATLAB\R2024a\bin\win64\matlab_startup_plugins\lmgrimpl

6. Done....

7. for polyspace re-run the setup.exe add the above keys too install Polyspace and replace the libmwlmgrimpl from Crack on this **path:C:\Program Files\Polyspace\R2024a\bin\win64\matlab_startup_plugins\lmgrimpl**
   
8. run product and point on .lic
