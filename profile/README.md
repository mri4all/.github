# MRI4ALL Hackathon 2023

Here you can find source code and resources created during the MRI4ALL Hackathon 2023 that took place from October 16-21, 2023 in New York City.

<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/render_built_image.jpg" width="800"/>
</p>

Goal of the MRI4ALL Hackathon was to jointly develop a fully-fledged low-field MRI scanner in just 4 days and to release all developed resources as open-source packages, so that other groups can utilize them for own projects. 52 researchers from 16 different institutions participated in the hackathon, and they created a scanner named "Zeugmatron Z1" - in reference to the term "Zeugmatography" that was initially used by Nobel-price winner Paul Lauterbur when he invented MRI. The scanner is now operational, and the hackathon participants continue to improve it.

In the section below, you can find more information about the event and the created scanner. Over the next weeks, we will complete the repositories and include all tools for calculating the magnet placement, gradient coils, shims, and the developed console software.

<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/logo.jpg" width="550"/>
</p>

## Resources

* [JMRI paper](https://github.com/mri4all#jmri-paper)
* [Impressions from the hackathon](https://github.com/mri4all#impressions-from-the-hackathon)
* [Console software](https://github.com/mri4all/console)
* [Component list of the scanner](https://github.com/mri4all/component_list)
* [3D model of scanner](https://github.com/mri4all/3d_model)
* [Code for magnet design](https://github.com/mri4all/magnet_design)
* [Code for gradient design](https://github.com/mri4all/gradient_design)
* [Code for calculating passive shim](https://github.com/mri4all/passive_shimming)
* [Code for calculating active shim](https://github.com/mri4all/active_shimming)
* [Field-mapping software](https://github.com/mri4all/field_mapper_3DFM)
* [Code for fieldmap calculation](https://github.com/mri4all/field-mapper_matlab)

## JMRI Paper

An overview paper with background information on the event and technical scanner details has been published in the Journal of Magnetic Resonance Imaging:

https://doi.org/10.1002/jmri.29771

## Impressions from the Hackathon

You can learn more about the event and the created scanner by <a href="https://www.youtube.com/embed/qQ7QVIVaeXs?si=--VZ2_hBI6DZcPoZ&amp;start=77" target="_blank">watching the following talk on YouTube</a> (presented at the "ESMRMB MRI Together 2023" workshop).

<p align="center">
  <a href="https://www.youtube.com/embed/qQ7QVIVaeXs?si=--VZ2_hBI6DZcPoZ&amp;start=77" target="_blank">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide1.JPG" width="800"/>
  </a>
  <br>
  <span><a href="https://www.youtube.com/embed/qQ7QVIVaeXs?si=--VZ2_hBI6DZcPoZ&amp;start=77" target="_blank">Open talk on YouTube</a></span>
</p>

<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide2.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide3.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide4.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide5.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide6.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide8.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide9.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide10.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide11.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide12.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide13.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide14.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide15.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide16.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide18.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide19.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide20.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide21.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide22.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide23.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide24.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide25.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide26.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide27.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide28.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide29.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide30.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide31.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide32.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide33.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide34.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide35.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide36.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide38.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide39.JPG" width="800"/>
</p>
<p align="center">
  <img src="https://github.com/mri4all/.github/blob/main/profile/Slide40.JPG" width="800"/>
</p>



