# Skirts for Voron V2.4r2 with honeycombs

In [this video](https://www.youtube.com/watch?v=K6sHfXldK4k) of Eddie the Engineer discribes how to add an accent mesh to voron skirts with a dual toolhead printer (Voron Tridex).

This repo contains stl files for skirts for a 350 Voron V2.4r2 build, which could be printed with a filament change to get the same result. (I also added the my project files for PrusaSlicer)

![Front Skirt](images/front-skirt.jpeg)

<figure>
    <img src="/images/front-skirt.jpeg"  width="700" >
    <figcaption>Front Skirt</figcaption>
</figure>

<figure>
    <img src="/images/side-skirt.jpeg"  width="700" >
    <figcaption>Side Skirt</figcaption>
</figure>


1. The M600 GCode for filament change must be implemeted
2. The skirts a solid for 1.6 mm - a "High range modifier" must be added for 0m - 1.6mm (8 layers). For this 8 Layers bootom and top layers must be set to 0 and a Honeycomb infill of 20% must be set. To get a nice look adjust the Fill angel to 90 or 0 degree and place the skirts with the same distance to the center of the print bed
3. Add a filament change after layer 8 /1.6mm

<figure>
    <img src="/images/slicer-settings.jpeg" >
    <figcaption>Slicer settings</figcaption>
</figure>

<figure>
    <img src="/images/slicer-front.jpeg"  width="700" >
    <figcaption>Slicer front</figcaption>
</figure>

<figure>
    <img src="/images/slicer-side.jpeg"  width="700" >
    <figcaption>Slicer side</figcaption>
</figure>

<figure>
    <img src="/images/printing.jpeg"  width="700" >
    <figcaption>Printing</figcaption>
</figure>


On [this](https://www.youtube.com/watch?v=eeo5JyMqiJw&t=9377s) the Tridex build video of Steve Builds at minute 18, he explains to create and print this skirts on a better way.
