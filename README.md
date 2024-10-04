# powershell 2

 Id CommandLine                                                                     
  -- -----------                                                                     
   1 Set-Location C:\                                                                
   2 Get-ChildItem -Path C:\Temp                                                     
   3 Get-ChildItem -Path C:\                                                         
   4 Set-Location -Path C:\...                                                       
   5 Get-ChildItem -Path C:\FolderTest1                                              
   6 Move-Item -Path C:\FolderTest1\File2 -Destination .\Temp\EvenFolder             
   7 Move-Item -Path C:\FolderTest1\File4 -Destination .\Temp\EvenFolder             
   8 Move-Item -Path C:\FolderTest2\File6 -Destination .\Temp\EvenFolder             
   9 Move-Item -Path C:\FolderTest2\File8 -Destination .\Temp\EvenFolder             
  10 Move-Item -Path C:\FolderTest2\File10 -Destination .\Temp\EvenFolder            
  11 Get-ChildItem -Path .\Temp\EvenFolder                                           
  12 Move-Item -Path C:\FolderTest1\File1 -Destination .\Temp\OddFolder              
  13 Move-Item -Path C:\FolderTest1\File3 -Destination .\Temp\OddFolder              
  14 Move-Item -Path C:\FolderTest1\File5 -Destination .\Temp\OddFolder              
  15 Move-Item -Path C:\FolderTest2\File7 -Destination .\Temp\OddFolder              
  16 Move-Item -Path C:\FolderTest2\File9 -Destination .\Temp\OddFolder              
  17 et-ChildItem -Path .\Temp\OddFolder                                             
  18 Get-ChildItem -Path .\Temp\OddFolder                                            
  19 Get-History                                                                     
  20 Get-History > historique.txt                                                    
  21 Get-ChildItem -Path *Folder* -Recurse >listing.txt                              
  22 Get-ChildItem -Path \*Folder*\ -Recurse >listing.txt                            
  23 Get-ChildItem -Path \Temp *Folder* -Recurse > listing.txt                       
  24 Get-ChildItem  \Temp *Folder* -Recurse > listing.txt                            
  25 ls .\listing.txt                                                                
  26 Get-ChildItem -Path \Temp *Folder* -Recurse > listing.txt                       
  27 Get-ChildItem .\listing.txt                                                     
  28 Get-History                                                                     
  29 Get-ChildItem -Path .\Temp\EvenFolder -Recurse >.\listing.txt                   
  30 Get-ChildItem -Path .\Temp\OddFolder -Recurse >.\listing.txt                    
  31 Get-ChildItem -Path .\listing.txt                                               
  32 Get-History > .\historique.txt                                                  
  33 Get-History > .\historique.txt .\listing.txt                                    
  34 Get-History > .\listing.txt                                                     
  35 Ls .\historique.txt                                                             
  36 Ls .\listing.txt                                                                
  37  5 Get-ChildItem -Path C:\FolderTest1                                           
  38 Get-ChildItem -Path C:\FolderTest1                                              
  39 Get-ChildItem -Path C:\Temp\EvenFolder                                          
  40 Get-ChildItem -Path C:\Temp\OddFolder                                           
  41 Get-History > historique.txt                                                    
  42 Get-ChildItem -Path *Folder* -Recurse > listing.txt                             
  43 Get-ChildItem -Path *Temp* -Recurse > listing.txt                               
  44 Get-ChildItem -Path C:\Temp\EvenFolder                                          
  45 Get-ChildItem -Path C:\Temp\OddFolder    

  LISTING.TXT
  Directory: C:\Temp\EvenFolder


Mode                 LastWriteTime         Length Name                               
----                 -------------         ------ ----                               
-a----         10/4/2024  11:46 AM              0 File10                             
-a----         10/4/2024  11:46 AM              0 File2                              
-a----         10/4/2024  11:46 AM              0 File4                              
-a----         10/4/2024  11:46 AM              0 File6                              
-a----         10/4/2024  11:46 AM              0 File8                              


    Directory: C:\Temp\OddFolder


Mode                 LastWriteTime         Length Name                               
----                 -------------         ------ ----                               
-a----         10/4/2024  11:46 AM              0 File1                              
-a----         10/4/2024  11:46 AM              0 File3                              
-a----         10/4/2024  11:46 AM              0 File5                              
-a----         10/4/2024  11:46 AM              0 File7                              
-a----         10/4/2024  11:46 AM              0 File9                              



  

