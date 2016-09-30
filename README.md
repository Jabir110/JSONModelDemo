# JSONModelDemo
".pch" File Include. Set BASEURL

Library
-------------
-> SDWebImage

-> IQKeyBoardManager

-> JSONModel

-> MBProgressHUD

-> Reachability

App Transport Securit
----------------

     <key>NSAppTransportSecurity</key>

        <dict>

           <key>NSAllowsArbitraryLoads</key>

           <true/>

        </dict>
        
NSUserDefault
--------------------

      NSUserDefaults *defaults = [NSUserDefaults standardUserDefaults];
                     
      [defaults setObject:[@"Jabir" forKey:@"strVanue"];
                     
      [defaults synchronize];
                      
      NSLog(@"strVanue : %@",[defaults valueForKey:@"strVanue"]);


