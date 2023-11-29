# CF10-CertMan

An extension for ColdFusion Administrator (for CF10 and above--tested to CF2023) that allows adding/viewing/removing of SSL certificates in the Java certificate store from within the Administrator.

For a CF versions 7, 8 & 9 please check out [CF-Certman](https://github.com/coldfumonkeh/CF-Certman).

## CommandBox Compatible

If you have [CommandBox](http://www.ortussolutions.com/products/commandbox) running on your local machine (and you should) you can download this project using the following command:

    box install cf10-certman


## Installation

Extract the contents of this repository into the CFIDE/administrator/certman/ directory. (If you download the zip from Github, it will contain a folder called CF10-Certman-master. Extract that folder and then rename it to certman and place THAT folder within the CFIDE/administrator/ folder.)

Edit the CFIDE\administrator\custommenu.xml file to add the following submenu xml key:-

    <submenu label="SSL Certificates">
      <menuitem href="certman" target="content">Certificate Management</menuitem>
    </submenu>

### Notes

The CertMan project was originally developed by Paul Connell.

This is a fresh fork taken to separate the specific ColdFusion versions for easier use.
