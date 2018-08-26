# ElectronicFlySwatter-Upgrade
Upgrade a common electrical flyswatter bat to get more punch

# Introduction
The common electronic flyswatter bat might nog give enough punch to your needs, eg you might be able to get it effective on wasps and bigger flying insects.

# Goals 

* higher output voltage
* higher capacity on discharge
* fast charge to ready output
* high output current for continues "frying"
* remove the high pitched sound, not warning the suspects

# Commonly proposed modifications

* Remove the parallel discharge resistor
* add bigger capacitor 
   !["Adding bigger and better capacitor"](pictures/IMG_9746.PNG "IMG_9746.PNG")

# Not seen mentioned before

* Use Alkaline batteries, and not Zink-Chloride
    * Alkaline has much lower internal resistance
     !["Undesired Zink Cloride batteries"](pictures/IMG_9744.PNG "IMG_9744.PNG")
* Replace thin power (battery) wires by thick onces
    * remove unneeded extra resistance
    !["Schema"](pictures/IMG_9747.PNG "IMG_9747.PNG")
* shorten the power wires
    * remove extra resistance
* [Untested] replace switching transistor with lower Vsat
    * leave a higher effective voltage on switching transformer
* [Untested] use a boost convertor to get a little higher voltage (5V)
    * this might impact static current settings, and might need output diode and capacitor upgraded to a higher voltage.

