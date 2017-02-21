---
title: Islandora Staff UI
layout: post
author: mike.demers.jr
permalink: /islandora-staff-ui/
source-id: 1BcnwE0wQSsWPbEyr2ztx9u7o1njRoNgzmTVZzDTgrVo
published: true
---
# Downloading Files from Repository

* In order to access all HDA files you should have Islandora user account with either the role av-staff or administrator. 

* You can download files from both the public site (digital.hagley.org) or the ingest site (hagley.ingest.dgicloud.com).

To download files, first log into the islandora site of your choosing by navigating to the /user page. Logging in will allow you to view available datastreams for each object.

Navigate to the item you want to download. Beneath the item label you will see a set of tabs like the group below.

![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_0.png)

If you are attempting to download a page of a newspaper or book you'll need to select the Pages tab and locate the page, otherwise select **Manage**.

You'll now see a set an administrative overview of that item. Select the option for **Datastreams**.![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_1.png)

On the datastreams page you will see a list of files associated with the item. Locate the format you want from the list and select the download link from the operations column in the corresponding row.Alternatively, you can select the datastream ID to open the file in your browser, if applicable. ![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_2.png)![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_3.png)![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_4.png) 

The **OBJ** datastream is typically the master copy of the item and will be the highest resolution/quality. Other datastreams are derivative copies or contain administrative information. These datastreams will vary depending on the type or format of item you are accessing. For more information on datastreams see appendix I. 

# Editing Metadata

* To edit the metadata of objects in Hagley Digital Archives you should have Islandora user account with either the role av-staff or administrator. 

* All metadata changes **MUST** be made using the ingest site (hagley.ingest.dgicloud.com).

There are multiple ways to edit metadata in Islandora. The guide below only details how to use the Drupal user interface.

Log onto the ingest site at [http://hagley.ingest.dgicloud.com/user](http://hagley.ingest.dgicloud.com/user) and navigate to the item you wish to work on. 

Beneath the item label you will see a set of tabs like the group below.

![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_5.png)

To access the MODS metadata form select the **Edit Metadata** tab. Alternatively, you may select **Manage **→ **Datastreams** and select the **edit** link from the operations column of the row labeled **MODS**..

You may be presented with a list of forms to choose from. You can use any form to access the MODS but the most comprehensive will be labeled "Full MODS".

Assuming there is existing metadata, you will see the form populated with these values. To change an existing value simply overwrite it.

Many fields will include a brief explanation but for further assistance please see the [Hagley MODS data entry guide](http://drive.google.com/open?id=16gs2RIyJGwlfbPt2bHJAbnOpX0-lKPZsF6UFR40Ds14) and the [LoC detail of MODS elements](https://www.loc.gov/standards/mods/v3/mods-userguide-elements.html). 

![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_6.png)

The forms can be deceiving when entering new fields. If a field is not yet populated  just enter the values into the blank field. Important: You do not need to select an 'Add' button or a "plus" icon when entering a field for which no entries yet exist.

If entering multiple values for a field you can use these buttons to create additional input fields to the form.

![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_7.png)

![image alt text]({{ site.url }}/public/FLcPRvOs6JEZZLTrNiF2Cg_img_8.png)

When you are finished editing select **Update **at the bottom of the form. 

# Appendix I. Datastream Reference

Sourced from: [https://wiki.duraspace.org/display/ISLANDORA/APPENDIX+C+-+DATASTREAM+REFERENCE](https://wiki.duraspace.org/display/ISLANDORA/APPENDIX+C+-+DATASTREAM+REFERENCE)

<table>
  <tr>
    <td>Datastream ID (DSID)</td>
    <td>Found in:</td>
    <td>Comments</td>
  </tr>
  <tr>
    <td>COLLECTION_POLICY</td>
    <td>Collection Object</td>
    <td>The COLLECTION_POLICY Datastream specifies which content models are associated with a particular collection object, the relationship that child objects ingested into this collection will have with the collection object.</td>
  </tr>
  <tr>
    <td>DC</td>
    <td>All Objects (required)</td>
    <td> Dublin Core metadata. Derived from ingested MODS metadata.</td>
  </tr>
  <tr>
    <td>FULL_TEXT</td>
    <td>PDF Solution Pack</td>
    <td>Text of a PDF, pulled from the PDF format's text stream (as opposed to being pulled via OCR)</td>
  </tr>
  <tr>
    <td>HIGH_QUALITY</td>
    <td>Collection, Large Image</td>
    <td>HDA-specific. A large high resolution jpeg used as part of a rotating set of front-page background covers. Part of the Hagley theme.</td>
  </tr>
  <tr>
    <td>HOCR</td>
    <td>Paged Content module</td>
    <td>Formatted OCR text stream used to more accurately display the OCR output</td>
  </tr>
  <tr>
    <td>JP2</td>
    <td>Large Image solution pack and Paged Content module</td>
    <td>Web-viewable JPEG2000 image created from TIFF files</td>
  </tr>
  <tr>
    <td>JPG</td>
    <td>Large Image solution pack and Paged Content module</td>
    <td>Plain JPG derivative created from TIFF files</td>
  </tr>
  <tr>
    <td>MEDIATRACK</td>
    <td>Oral Histories</td>
    <td>A WEBVTT file generated from the TRANSCRIPT datastream. Used to sync time coded index display..</td>
  </tr>
  <tr>
    <td>MEDIUM</td>
    <td>Collection</td>
    <td>An image to display as part of the collection description.</td>
  </tr>
  <tr>
    <td>MEDIUM_SIZE</td>
    <td>Objects created with the Basic Image Solution Pack</td>
    <td>Provides a derivative web-suitable file for display.</td>
  </tr>
  <tr>
    <td>MODS</td>
    <td>All objects</td>
    <td>Datastream holding MODS Metadata</td>
  </tr>
  <tr>
    <td>MP4</td>
    <td>Video Solution Pack</td>
    <td>MPEG-4 video derivative</td>
  </tr>
  <tr>
    <td>OBJ</td>
    <td>Audio, Basic Image, Large Image, PDF and Video solution packs, and the Paged Content module</td>
    <td>Default datastream for the actual original binary ingested with an object</td>
  </tr>
  <tr>
    <td>OCR</td>
    <td>Paged Content module</td>
    <td>OCR text stream</td>
  </tr>
  <tr>
    <td>PDF</td>
    <td>Book and Newspaper solution pack, Paged Content module</td>
    <td>PDF derivative created either during ingest of a page, or stitched together into an entire book or newspaper</td>
  </tr>
  <tr>
    <td>POLICY</td>
    <td>Any digital object can contain a POLICY datastream. (optional)</td>
    <td>This Datastream is an XACML policy that describes who can view/edit/delete a collection, object, or datastream.</td>
  </tr>
  <tr>
    <td>PROXY_MP3</td>
    <td>Audio Solution pack</td>
    <td>Provides a derivative web-suitable file for download and display.</td>
  </tr>
  <tr>
    <td>RELEASE</td>
    <td>Varies</td>
    <td>An HDA-specific datastream representing a release form for audio or video interviews and oral histories. Typically a PDF.</td>
  </tr>
  <tr>
    <td>RELS-EXT</td>
    <td>All Objects (required)</td>
    <td>"Relationships-External." This Datastream contains digital object relationship information.</td>
  </tr>
  <tr>
    <td>RELS-INT</td>
    <td>Paged Content module</td>
    <td>Interior relationship datastream defining a page's relationship to other pages and the book as a whole</td>
  </tr>
  <tr>
    <td>TECHMD</td>
    <td>All Objects</td>
    <td>Technical Metadata. Generated using FITS.</td>
  </tr>
  <tr>
    <td>TN</td>
    <td>Audio, Basic Image, Book, Large Image, Newspaper and Video solution packs, and the Paged Content module</td>
    <td>Thumbnail image used to represent the object in lists</td>
  </tr>
  <tr>
    <td>TRANSCRIPT</td>
    <td>Oral Histories</td>
    <td>An XML file containing the imported index data for oral histories. This can be created though Islandora but in the HDA will typically come from an OHMS exported index transformed via XSLT and imported into Islandora.</td>
  </tr>
</table>


