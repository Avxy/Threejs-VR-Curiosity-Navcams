# Threejs-VR-Curiosity-Navcams (under construction)

Explore Curiosity Navcams 3D images in Oculus Quest.

<img src="images/IMG_5730.jpg" width="640">

Stereoscopic view.<br>

# Threejs-VR-Curiosity-Navcams Pages

[https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/](https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/)

# Hardware

Oculus Quest tested (6DoF headset/controllers).<br>

# Software

Oculus Browser (tested Quest update > 17.0).

# Installation

No installation.<br>

In Oculus Quest, open Oculus Browser and link:<br>

[https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_vr_curiosity_sol1151.html](https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_vr_curiosity_sol1151.html)

File sol1151_wheel_measure.glb shows one of Curiosity's six wheels on the lower right. Any Navcam image with wheel(s) is selected because a wheel is used in Blender to scale the 3D mesh. The author of Blender-Navcam-Importer has stated that, "resulting mesh...is in no way scientifically accurate". Nevertheless, the result does not appear distorted or unusual.

If no Oculus Quest (tested 2018 9.7" iPad/iPadOS 13/Safari, Windows 10/Google Chrome/Firefox, Raspberry Pi 3 B+/Raspbian Buster).<br>

[https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_curiosity_sol1151.html](https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_curiosity_sol1151.html)

# Stereoscopic views of Sol 1431

[https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_curiosity_sol1151.html](https://physicslibrary.github.io/Threejs-VR-Curiosity-Navcams/examples/threejs_curiosity_sol1151.html)

# Making Sol 1151 .glb (Feb 20, 2020)

# References

Go to Curiosity, Multimedia, Raw Images in link:<br>

[https://mars.nasa.gov/msl/home/](https://mars.nasa.gov/msl/home/)<br>

Or Sol images for left navigation camera:<br>

[Curiosity Left Navigation Camera](https://mars.jpl.nasa.gov/msl/multimedia/raw-images/?order=sol+desc%2Cinstrument_sort+asc%2Csample_type_sort+asc%2C+date_taken+desc&per_page=50&page=0&mission=msl&af=NAV_LEFT_A%7CNAV_LEFT_B%2C%2C%2C)<br>

To find the image used to make sol1151_wheel_measure.glb, enter 1151 for Sol and sort by "oldest to newest". It should be the 13th image (2015-11-01T21:33:08.000Z).<br>

[Raw image used to make sol1151_wheel_measure.glb](https://mars.jpl.nasa.gov/msl-raw-images/proj/msl/redops/ods/surface/sol/01151/opgs/edr/ncam/NLB_499684496EDR_F0501222NCAM00354M_.JPG)<br>

A Blender addon is used to import Curiosity Navcams.<br>

[https://github.com/phaseIV/Blender-Navcam-Importer](https://github.com/phaseIV/Blender-Navcam-Importer)

The Blender-Navcam-Importer github has an excellent introduction about the addon.<br>

Blender 2.82 is used to export "glTF Binary" sol1511-wheel-measure.glb with Decimate Modifier(Ratio 0.1) and Draco compression.<br>

[https://www.blender.org/](https://www.blender.org/)

[https://mars.nasa.gov/msl/spacecraft/rover/cameras/#navcams](https://mars.nasa.gov/msl/spacecraft/rover/cameras/#navcams)

[https://mars.nasa.gov/msl/spacecraft/rover/wheels/](https://mars.nasa.gov/msl/spacecraft/rover/wheels/)

[https://threejs.org/](https://threejs.org/)

[https://github.com/mrdoob/three.js/](https://github.com/mrdoob/three.js/)

Three.js examples is the best place to learn and experiment:<br>

[https://github.com/mrdoob/three.js/tree/dev/examples](https://github.com/mrdoob/three.js/tree/dev/examples)

Three.js' excellent documentation on how to convert WebGL examples to WebVR:<br>

[https://threejs.org/docs/index.html#manual/en/introduction/How-to-create-VR-content](https://threejs.org/docs/index.html#manual/en/introduction/How-to-create-VR-content)

Three.js example of how to load .glb file:<br>

[https://github.com/mrdoob/three.js/blob/dev/examples/webgl_loader_gltf.html](https://github.com/mrdoob/three.js/blob/dev/examples/webgl_loader_gltf.html)

<br>Copyright (c) 2020 Hartwell Fong
