

# QR Code Generator for PHP

 Based on the popular library [PHP QR Code](http://phpqrcode.sourceforge.net), this package lets you create several different QR Codes.

 **Note**  
 Due to the number of permutations this library does, it is normal to have more than one QR Code for the same information.
   
 To demonstrate this behavior, start a server at the **public** folder, enter some data and hit the **Generate QR Code** button a few times.
  
 Each time you hit the button there is a chance a different QR Code with the same encoded information will be generated. 
 Independently of the number of permutations, this package will generate one and only one PNG or SVG file for each content, overwriting the latest one every time.

 ## Installation

 Install using **composer**:

 ```bash
 $ composer require giauphan/qr-code
 ```

 ## QR Code Types

 QR Code Generator for PHP supports the following QR Codes:

  - Calendar Event
  - Email Message
  - Phone
  - SMS
  - Text
  - URL
  - meCard
  - vCard v3
  - Wi-fi Network Settings
  
  Make sure you check the [Documentation](https://giauphan.github.io/qr-code/) for further instructions.
  
 ## [Contributing](CONTRIBUTING.md)
 
 To contribute to this project, please do the following:
 
  - Fork it
  - Create a new branch for your contribution
  - Test it! Make sure it works and it won't break the master code
  - Send pull request
  