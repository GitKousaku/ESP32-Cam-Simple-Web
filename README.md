# ESP32-Cam-Simple-Web
Just send Camera picture for usage PC disposition

CameraWebServer.FaceReco_flash_XPS.ino   APMODE
CameraWebServer.FaceReoc_falas_YPS.ino   Station Mode
  Need to change the project directory for each name.

camera_index.h    simple web page Hex Code
camera_pins.h 

to make the date of camera_index.h
   index_simple.html 
 is htmle file
 
 first compress with gzip
 gzip index_simple.html
    and make index_simple.html.gz
    
 after  with filetoarray to Hexcod
 a.array index_simple.html.gz > index20.txt

 
 copy the content index20.txt to camera_index.h
    replace length number
 
    

