<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="UW Green Bay Cofrin Library 2022 Workshop"
       author="Ann Hanlon"
       banner="https://upload.wikimedia.org/wikipedia/commons/b/be/Downtown_Mural-_Green_Bay%2C_WI_-_Flickr_-_MichaelSteeber.jpg"
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q47430"> <!-- Green Bay -->
<param ve-entity eid="Q2378091"> <!-- University of Wisconsin-Green Bay -->
<param ve-entity eid="Q178193"> <!-- steamboat -->


# Introduction

This is a sample visual essay to demonstrate how to use Juncture for the a workshop at the Cofrin Library at the University of Wisconsin-Green Bay. The banner image features a photograph of a downtown Green Bay mural taken in 2016 [^1]. The first image featured in this essay is an image of the James Baudhuin farm, 1976, from the University of Wisconsin - Green Bay. Cofrin Library Belgian-American Research Collection
<param ve-image 
       url="https://asset.library.wisc.edu/iiif/1711.dl%2FS5FOMADT6D5BH85/full/full/0/default.jpg">

       
## From the UW Madison Digital Collections - using IIIF

From the UW Madison Digital Collections. This image uses the fit=contain parameter to make sure the default view is the entire image. You can find the record here: [https://collections.si.edu/search/detail/edanmdm:siris_sic_13621](https://collections.si.edu/search/detail/edanmdm:siris_sic_13621)
<param ve-image fit="contain"
       manifest="https://ids.si.edu/ids/manifest/SIA-SIA2010-0721">

## Image without zoom

Carte de l'Isle Saint-Domingue..., 1730: Full size with no zoom or fit="contain" code.
<param ve-image  
       manifest="https://collections.lib.uwm.edu//digital/iiif-info/agdm/1435/manifest.json">
       
## Image with zoom
Carte de l'Isle Saint-Domingue..., 1730: Zoomed in using image coordinates to focus on a particular part of the image (in this case, an image of a map).
<param ve-image region="2135,1939,706,586"
       manifest="https://collections.lib.uwm.edu//digital/iiif-info/agdm/1435/manifest.json">
       
## Image with zoom-to
In this map, you can also see the island of <span data-click-image-zoomto="1496,1258,847,703">Inague</span>, to the east of Cuba. Further to the east is the western tip of <span data-click-image-zoomto="3145,1878,2107,1750">Puerto Rico</span>. 
<param ve-image  
       manifest="https://collections.lib.uwm.edu//digital/iiif-info/agdm/1435/manifest.json">

## Map

The Citadelle Laferrière is several miles inland from Cap-Haitien. We are using the map information from Wikidata to create the map to right.
<param ve-map center="Q206194">

Lat/long based map - using decimal-based lat/long for Port-au-Prince
<param ve-map center="18.5425, -72.338611" zoom="10">


## Video

You can also include Youtube videos by using the param ve-video code and the youtube video ID. This is a TED-Ed video called "The first and last king of Haiti," by Marlene Daut, created in 2019. This is about Henri Christophe.
<param ve-video id="q7lfSjjMNU8" title="The first and last king of Haiti">

## Finding IIIF resources

This object is from the National Archives of Haiti, and is found in the Library of Congress's [World Digital Library](https://www.loc.gov/collections/world-digital-library/about-this-collection/) collection. *The Laws of the French Colony of Saint-Domingue.* Cap-Français: P. Roux, -07 to -08, 1801, [https://www.loc.gov/item/2021666967/](https://www.loc.gov/item/2021666967/).
<param ve-image 
       manifest="https://www.loc.gov/item/2021666967/manifest.json">
       
## Multiple pages in a IIIF object

This object from the Harvard University Digital Collections is a book with multiple pages. You can identify a specific page to focus on by using the "seq" tag after the manifest address. 
<param ve-image 
       manifest="https://iiif.lib.harvard.edu/manifests/drs:492788288" seq="5">
       
       
# References

[^1]: Michael Steeber from USA, CC BY-SA 2.0 <https://creativecommons.org/licenses/by-sa/2.0>, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Downtown_Mural-_Green_Bay,_WI_-_Flickr_-_MichaelSteeber.jpg)
