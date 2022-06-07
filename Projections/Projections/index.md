> # INTRODUCTION

**Xarray Map Plotting** comes with a variety of projections. There are basically four types of projections available namely Azimuthal, Conic, Cylindrical and Pseudo-cylindrical.<br>
The Azimuthal projection depicts the surface of the earth with the help of a flat plane. It is also known as 'Plane Projection.' This simple projection type forms a family of projections by considering the poles in "normal aspect." Another form of this projection is Azimuthal Equidistant Projection. It preserves both directions and distance from the central point of the earth. The stereographic projection which is a type of azimuthal projection was created before 150AD and deployed while mapping areas over the poles.
The conic type is based on the concept of projecting the surface of the Earth on a conical surface which is unrolled into a plane  surfaced map. Some of the examples of conic type of projections are : Albers Equal Area Conic, Equidistant Conic, Lambert Conformal Conic, and Polyconic. This type of projection basically has a big implementation in aviation navigation.<br> The cylindrical type is based on the concept of plotting the geographical features on the surface of the cylinder and then it is unrolled to present as a flat projection. Some examples of cylindrical projections are : Cylindrical Equal Area, Behrmann Cylindrical Equal-Area , Stereographic Cylindrical, Peters, Mercator, and Transverse Mercator. Mercator is one of the most famous and preferred type of projection. The straight lines (Rhumb Lines) are best for the navigation process.<br>In the pseudo cylindrical type of projection , the meridians are straight instead of being curved. These kinds of projections are characterised by straight horizontal lines for parallels of latitude and (usually) equally-spaced curved meridians of longitude. Oval projections pinched or flattened at the poles are its identifying features.


<br> <br> <br>
> ## COLOR MAPS
There are about **35 different kinds of projections available in the proj option. The basic knowledge of projections is very essential in plotting out the best fit map. Below is the list of plots deployed using the various kinds of projections supported by the NetCDF xarray mapplotting tool.<br><br>


<br>**PlateCarree** <br>
**Syntax: {"proj":"PlateCarree"}**
![PlateCarree](images/PlateCarree.png)

<br> **EquidistantConic** <br>
**Syntax: {"proj":"EquidistantConic", "central_longitude": 20.0, "central_latitude": 70.0 }**
![EquidistantConic](images/EquidistantConic.png)


<br> **AlbersEqualArea** <br>
**Syntax: {"proj":"AlbersEqualArea", "central_longitude": 20.0, "central_latitude": 70.0 }**
![AlbersEqualArea](images/AlbersEqualArea.png)


<br> **EuroPP** <br>
**Syntax: {"proj":"EuroPP"}**
![EuroPP](images/EuroPP.png)

<br> **LambertConformal** <br>
**Syntax:{"proj":"LambertConformal"  }**
![LambertConformal](images/LambertConformal.png)

<br> **AzimuthalEquidistant** <br>
**Syntax: {"proj":"AzimuthalEquidistant" }**
![AzimuthalEquidistant](images/AzimuthalEquidistant.png)


<br> **LambertCylindrical** <br>
**Syntax:{"proj":"LambertCylindrical"}**
![LambertCylindrical](images/LambertCylindrical.png)

<br> **Mercator** <br>
**Syntax: {"proj":"Mercator" }**
![Mercator](images/Mercator.png)

<br> **Miller** <br>
**Syntax: {"proj":"Miller"  }**
![Miller](images/Miller.png)


<br> **Mollweide** <br>
**Syntax: {"proj":"Mollweide" }**
![Mollweide](images/Mollweide.png)

<br> **Orthographic** <br>
**Syntax:{"proj":"Orthographic"  }**
![Orthographic](images/Orthographic.png)

<br> **Robinson** <br>
**Syntax: {"proj":"Robinson"  }**
![Robinson](images/Robinson.png)

<br> **Sinusoidal** <br>
**Syntax: {"proj":"Sinusoidal"  }**
![Sinusoidal](images/sinusoidal.png)

<br> **Stereographic** <br>
**Syntax: {"proj":"Stereographic"  }**
![Stereographic](images/Stereographic.png)

<br> **TransverseMercator** <br>
**Syntax:{"proj":"TransverseMercator"  }**
![TransverseMercator](images/TransverseMercator.png)



<br> **InterruptedGoodeHomolosine** <br>
**Syntax: {"proj":"InterruptedGoodeHomolosine"  }**
![InterruptedGoodeHomolosine](images/InterruptedGoodeHomolosine.png)

<br> **RotatedPole** <br>
**Syntax: {"proj":"RotatedPole"  }**
![RotatedPole](images/RotatedPole.png)

<br> **OSGB** <br>
**Syntax:{"proj":"OSGB"  }**
![OSGB](images/OSGB.png)



<br> **Geostationary** <br>
**Syntax: {"proj":"Geostationary"  }**
![Geostationary](images/Geostationary.png)

<br> **NearsidePerspective** <br>
**Syntax:{"proj":"NearsidePerspective" }**
![NearsidePerspective](images/NearsidePerspective.png)

<br> **EckertI** <br>
**Syntax: {"proj":"EckertI" }**
![EckertI](images/EckertI.png)

<br> **EckertII** <br>
**Syntax: {"proj":"EckertII" }**
![EckertII](images/EckertII.png)

<br> **EckertIII** <br>
**Syntax: {"proj":"EckertIII" }**
![EckertIII](images/EckertIII.png)

<br> **EckertIV** <br>
**Syntax: {"proj":"EckertIV" }**
![EckertIV](images/EckertIV.png)

<br> **EckertV** <br>
**Syntax: {"proj":"EckertV" }**
![EckertV](images/EckertV.png)

<br> **EckertVI** <br>
**Syntax: {"proj":"EckertVI" }**
![EckertVI](images/EckertVI.png)

<br> **EqualEarth** <br>
**Syntax:{"proj":"EqualEarth" }**
![EqualEarth](images/EqualEarth.png)

<br> **Gnomonic** <br>
**Syntax: {"proj":"Gnomonic" }**
![Gnomonic](images/Gnomonic.png)

<br> **LambertAzimuthalEqualArea** <br>
**Syntax: {"proj":"LambertAzimuthalEqualArea" }**
![LambertAzimuthalEqualArea](images/LambertAzimuthalEqualArea.png)


<br> **NorthPolarStereo** <br>
**Syntax: {"proj":"NorthPolarStereo" }**
![NorthPolarStereo](images/NorthPolarStereo.png)

<br> **OSNI** <br>
**Syntax: {"proj":"OSNI" }**
![OSNI](images/OSNI.png)

<br> **SouthPolarStereo** <br>
**Syntax: {"proj":"SouthPolarStereo" }**
![SouthPolarStereo](images/SouthPolarStereo.png)


<br>
<br>
[back to top](https://github.com/Quickbeasts51429/Xarray_Projections/blob/main/Projections/index.md)