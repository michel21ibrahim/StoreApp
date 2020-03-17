# StoreApp
Android application that allows you to seamlessly audit the store.

# Introduction
As we all know, working in retail stores can be frustrating, especially when it’s the end of the month and you are in charge of conducting an inventory count of all items. One day, the manager requests a full inventory count of all items, and you are sick of having to stay late at night counting everything manually, searching in an excel sheet, updating it, saving it, re-updating it, making an error while counting, and having to repeat the whole process again.

# Compatibility
    This Android application is compatible with Android 4.4 Kitkat (API 19) and later
    
# About the App 
When the user open it , a splash screen appear for 3 seconds ,  after that you should import your CSV file by Clicking to the button for import it to the DATABASE. Once the file imported you can now start your audit by clicking on the scanner button to open the barcode reader ( othwerwise the camera ). 
You should generate the barcode name from the CSV as barcode via barcode generator on your PC or ... 
once you generated them , u can now read the items..

This is about the 5 boxes that are you seeing in the activity :
  a. Expected Items Count: The summation of quantities of all items provided in the database
  b. Found Items Count: The summation of quantities of all items that are read by the barcode scanner and exist in the database
  c. Added Items Count: The summation of quantities of all items that are read by the barcode scanner but doesn’t exist in the imported CSV file
  d. Missing Items Count: The summation of quantities of all items that not read by the barcode scanner but exist in the imported CSV file
  e. Total Items Count: Sum of both Found and Added items count

After that , the user can click the menu button on the right to choose if he would reset the auditing by clicking the reset button or exporting the auditing data by clicking the submit button and a new excel will be created in the storage of your device as CSV .
