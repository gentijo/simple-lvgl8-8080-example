idf_component_register(
    SRCS 
    "main.cpp" 
    "ui/ui.c" 
    "ui/ui_helpers.c" 
    "ui/screens/ui_Screen1.c"
    "display-config/ESP32S3_8048S070C/Display.cpp"
   
    INCLUDE_DIRS 
    "."
    "display-config/ESP32S3_8048S070C")
