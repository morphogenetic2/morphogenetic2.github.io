# Fluoplate programmer
Simple web interface for the fluoplate programmer project.

## How to use
Usage is very simple. You can access the main file at https://morphogenetic2.github.io/index.html and you will be shown a web app with the multiwell P24 layout corresponding to the physical hardware.

From there you can enter the intensity values in $\mu W/cm^2$, to an approximate maximum of 2000 $\mu W/cm^2$, depending on the LEDs you use.

The plate can be filled at once using the `FILL PLATE` button, or set up a gradient, row-wise, using the input fields below. 

Then you can define the on/off duty cycles in the other fields below, and set up the total experiment runtime in either minutes or hours, you can select the time units using the dropdown menu right to this field.

Finally, there are two buttons to clear the plate and download the `out_plate.json` file that needs to be placed in the same folder as the `code.py` script in the root folder of the microcontroller.

## Planned features

Update the UI to allow for row/column-wise gradients and other features.

Add more functions (constant, sine wave, etc)

Well-independent time control