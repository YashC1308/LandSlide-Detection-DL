# LandSlide-Detection-DL

This project explores the idea of multiple Landslide detection in cases of natural calamities such as heavy rainfall or earthquakes using Sattelite images to assess and identify damage quickly; this project has the potential to reduce manual annotation by a significant portion, allowing deep machine learning models to pick up on damage caused by calamities.

Multiple landslide events occur often across the world which have the potential to cause significant harm to both human life and property. Although a substantial amount of research has been conducted to
address mapping of landslides using Earth observation (EO) data, several gaps and uncertainties remain with developing models to be operational at the global scale.

A dataset available at https://zenodo.org/records/7189381#.Y0a2UHZBxD9 has been used for this project.

HR-GLDD, a high-resolution (HR) dataset for landslide mapping composed of landslide instances from ten different physiographical regions globally: South and South-East Asia, East Asia, South America, and Central America. The dataset contains five rainfall-triggered and five earthquake-triggered multiple landslide events that occurred in varying geomorphological and topographical regions.

Using the dataset, which has images in 4 channels of RGB+Nir, we were able to build a UNet++ model that is able to identify landslides to a fair degree.
You can find the results and the metrics in the repo itself. The Images of landslides and the model tracking the landslides are shown below.


This is the affected region in Haiti:
![download](https://github.com/YashC1308/LandSlide-Detection-DL/assets/83706455/a610cad1-e74f-4e6d-94c6-10201491ffe1)


These are the model results, i.e the landslides it was able to identify:

![download (1)](https://github.com/YashC1308/LandSlide-Detection-DL/assets/83706455/4c963b08-e9f8-4d28-bd03-35cd0e96c7bf)



A slide deck can also be found here:
(https://drive.google.com/file/d/1m3CKnGdIgeTEUE_nbmWFyHOcN8NrVOQe/view?usp=sharing)
