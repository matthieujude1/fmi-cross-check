Model:
      Modelica Standard library model
      Engine1b
      
      FMI Type:
      ModelExchange
      
      Generation Tool:
      Dymola 2017
      
      Available Platforms:
      win32, win64
      
      Known Errors:
      
      Additional Information:
      
      
        
      FMUChecker:
      FMUChecker Version 2.0.3b2 
      
      run command:
      set FMUName=Engine1b
      fmuCheck.win64.exe -k me -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 1e-5 -s 0.5 %FMUName%.fmu
      
      Contact info: karl.wernersson@3ds.com
