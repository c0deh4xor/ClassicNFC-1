# ClassicNFC

Example code to demonstrate cloning Mifare Classic and sniffing credit card data using NFC on Android

### Ruxcon 2015 Presentation

  - https://github.com/gsbabil/ClassicNFC/blob/master/gsbabil-ruxconf2015.pdf

### Compiling

  ```
  ./gradlew assembleDebug
  ```

### Disclaimer

The code was compiled and tested using the following:

  - Phone: Google Nexus S (codename: `crespo`)
    - http://imgur.com/P9dleUj
    - http://cdn.redmondpie.com/wp-content/uploads/2012/07/google-nexus-s-540x424.jpg
  
  - Operating System: Cyanogenmod version - `10.1-20130411-EXPERIMENTAL-crespo-M3`
    - https://download.cyanogenmod.org/get/jenkins/24767/cm-10.1-20130411-EXPERIMENTAL-crespo-M3.zip 
  
  - Emulation button is currently disabled
    - My primary intention was to emulate Mifare Classic
      - Mifare Classic Emulation doesn't seem to be possible without access to the Secure Element (SE) that's ships with Nexus S
      - Google doesn't share the credentials to access the SE
    - Credit card emulation should be possible with Android's Host Card Emulation (HCE) API 
