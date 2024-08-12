# Changes made to cura

1. Follow PDF file inside of `CuraProfiles` folder

Use this as your _Start G-code_:
```
; M190 S{material_bed_temperature_layer_0}
; M109 S{material_print_temperature_layer_0}
start_print BED_TEMP={material_bed_temperature_layer_0} EXTRUDER_TEMP={material_print_temperature_layer_0}
```

Use this as your _End G-code_
```
end_print
```

2. Install Moonraker plugin

On the _Connection_ tab set _Address (URL)_ to `http://klipper.local/` and in the _Upload_ tab set the format to _UFP with Thumbnail_. Leave everything else as is.