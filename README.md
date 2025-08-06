# GVM and the Video-Mapa
## Summary: The GVM was created to monitor and inventory traffic signs.
### Legacy History:
<p>The prototype of the GVM System was created to monitor and inventory traffic signs.</p>
<p>This system was developed and funded by FAPESP, with Grant TT5, Process 2013/14956-9, from September 1, 2013, to June 30, 2014, during part of my doctoral studies at the LTG laboratory of the Department of Transportation of the Polytechnic School of the University of São Paulo. </p>
<p>This entire experiment can be read in Chapter 7 of my thesis, which can be accessed at [Teses Usp website] https://teses.usp.br/teses/disponiveis/3/3138/tde-16062016-114254/publico/CarlosEnriqueCorrigida.pdf, where several questions can be answered.</p>
<p>This system used a user interface I developed and called Video-Mapa.</p>
<p>Video-Mapa can be used as the interface for a low-cost Mobile Mapping System, and the various versions can be reused in other projects if interested, given that it is open-source.</p>
<p>Video-Mapa was created in 2009 using MXML, ActionScript, Adobe Video Server, and Google Maps API for ActionScript in the GeoRTA project. </p>
<p>Video-Mapa has been refactored and versioned since then.</p>
<p>In 2009, Video-Map was developed using MXML, ActionScript, Adobe Video Server, and Google Maps API for ActionScript, aiming for a variety of use cases.</p>
<p>It was later updated to HTML5, CSS3, JavaScript, JQuery, and the Google Maps API.</p>
<p>Later, to make it open-source and cost-effective, I updated the code and used Leaflet, replacing the Google Maps API, and used the OSM layers and Esri images, which are freely available.</p>
<p>Recently, in 2025, at the Unisinos VizLab, I used in this latest version a database of Brazilian traffic signs created and trained, available on the [Roboflow website](https://universe.roboflow.com/projetos-abip9/brazilian-traffic-signs-hnifq).</p>
<p>I used the convolutional neural network technique in computer vision, specifically Yolo8, to automatically recognise and identify traffic signs following the CONTRAN standard. </p>
<p>This was an important missing feature.</p>
<p>With this, you can obtain all the data necessary for automated monitoring and inventory of traffic signs.</p>
<p>Simply conduct a field survey with the appropriate sensors and process it in the office, updating it in a database periodically.</p>
<p>Certainly, dealerships and traffic departments would be interested in an application like this, as road safety means mitigating traffic accidents and fatalities.</p>
<p>As this is a constantly updated project, it can and should be updated and expanded with new existing UI/UX technologies.</p>





