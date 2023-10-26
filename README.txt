
Create a suite in testim

Generate an API key

Edit myconfig.js and change the following:
 grid:       "<GRID>",
 project:    "<TestimprojectID>",
 token:      "<Testimtoken>",
 const fileDir = "<path/reports>/";
 const api_key = "<APIkey>";

Open terminal prompt 
testim  --config-file "myConfig.js" --suite "<suiteNameInTestim>""

Results in the dir you specified in the config file, example 

Test-Results-Report__Rwz6tQraVfmBEgau__2023-10-26T13:03:25+00:00__PASSED.html
Test-Results-Report__Tl5uBpbLQLlvXXTc__2023-10-26T13:03:25+00:00__FAILED.html
Test-Results-Report__iJRTbPiQ6R7DSisZ__2023-10-26T13:03:25+00:00__PASSED.html

