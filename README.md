
This is a customized version of our [Accordions](https://wordpress.org/plugins/accordions/) plugin to ensure that the ID remains the same when exporting and importing accordions.

##### We recommend using WordPress  default export/import feature since we were unable to replace the accordion ID with an existing one due to the **primary key restriction**. Here is a screenshot of the issue:

![Primary key](https://i.ibb.co/52ZZt15/image-2024-02-21-T06-47-16-635-Z-1.png)



# WordPress default export and import
Export your Accordions by going to **Tools** => **Export** from your WP dashboard. Select the **Accordions** option, and click the 'Download Export File' button.

![enter image description here](https://i.ibb.co/pX1DDPL/default-export.png)


Now run Importer under **Tools** => **Import**
Choose the exported file and click the button to import.

> NB: Please make sure to delete any accordions with identical IDs
> before importing.


![enter image description here](https://i.ibb.co/QXCM9ng/select-file-import.png)


## Content Missing Issue:

The accordion IDs remain the same in both sites. However, some accordion content may be missing. To resolve this issue, please use our plugin import feature to export and import accordions again.

You can upload the exported file to a hosting platform like [https://www.file.io](https://www.file.io) and then copy the link to use on our Import section.

![enter image description here](https://i.ibb.co/4Wr5Pnx/json-file-import.png)

The issue of missing content has now been resolved.
