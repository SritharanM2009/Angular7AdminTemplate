# Angular7AdminTemplate
Angular 7 Admin Template with Asp.Net Core 2.1


Hi Guys,

1. First Restore Package files,

2. Need to Insert one line into this file '...\ClientApp\node_modules\ng2-dragula\dist\MockDrake.d.ts'
Line no 5 : import { Drake } from 'dragula';

3. Change one line in '...\ClientApp\node_modules\ng2-dragula\dist\MockDrake.d.ts'

 Line No 42 :
  
  on(event: string, callback: Function): void; 
  
  to

 on(event: string, callback: Function): Drake;
 
 
 4. If you want publish in IIS, Install 
 
    I   -  'dotnet-hosting-2.2.1-win.exe'
    III -  'DotNetCore.2.0.9-WindowsHosting.exe'
