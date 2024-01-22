---
layout: page
title: Latest Project
tags: maya modelling Hardwork 
description: this is my latest maya project
img: /assets/img/OIP.jpg
---
I modelled a disney character from a sheet which is always essential for modelling artisits to have. But this is only the begining of it, there is much to do like rigging and UV and texture editing which can be done better and faster when you work in a team.

![Alt Text](/assets/img/EgyptionDisney.jpg){:width="400" height="300"}

here's all the packages used for the rendering part:

{% highlight mel %}

// File read in  3.1 seconds.
commandPort -securityWarning -name commandportDefault;
onSetCurrentLayout "Rigging";
updateRendererUI;
// Bifrost: Pre-loaded mayaUsdPlugin to access proper Maya USD libraries.
// Loading Bifrost version 2.7.0.1-202303200742-06aa76e
// Bifrost: Loading library: Amino, from: Autodesk.
// Bifrost: Loading library: AminoMayaTranslation, from: Autodesk.
// Bifrost: Loading library: bif, from: Autodesk.
// Bifrost: Loading library: bifrostObjectMayaTranslations, from: Autodesk.
// Bifrost: Loading library: geometries, from: Autodesk.
// Bifrost: Loading library: fluids, from: Autodesk.
// Bifrost: Loading library: particles, from: Autodesk.
// Bifrost: Loading library: file, from: Autodesk.
// Bifrost: Loading library: mpm, from: Autodesk.
// Bifrost: Loading library: modeling, from: Autodesk.
// Bifrost: Loading library: nucleus, from: Autodesk.
// Bifrost: Loading library: simulation, from: Autodesk.
// Bifrost: Loading library: riv_types, from: Autodesk.
// Bifrost: Loading library: riv, from: Autodesk.
// Bifrost: Loading library: scatter_pack, from: Autodesk.
// Bifrost: Loading library: graphs, from: Autodesk.
// Bifrost: Loading library: usd_pack, from: Autodesk.
// Bifrost: Loading library: usdMayaTranslations, from: Autodesk.
// AbcExport v1.0 using Alembic 1.8.3 (built Apr 19 2023 14:41:12)
// AbcImport v1.0 using Alembic 1.8.3 (built Apr 19 2023 14:41:12)

{% endhighlight %}