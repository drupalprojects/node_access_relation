
Node Access Relation README

CONTENTS OF THIS FILE
----------------------

  * Introduction
  * Requirements
  * Installation
  * Usage
  

INTRODUCTION
------------
Gives content access permissions to users if they are referenced as a source
bundle in a directional relation. Checks view, update, and delete grant 
operations, and can pass those on to the target bundle relation content, or 
trigger a different grant configuration according to settings.

Project page: http://drupal.org/project/node_access_relation.


REQUIREMENTS
------------
http://drupal.org/project/entityreference
http://drupal.org/project/references


INSTALLATION
------------
Install and enable the Relation and Node Access Relation modules.
For detailed instructions on installing contributed modules see:
http://drupal.org/documentation/install/modules-themes/modules-7


USAGE
-----
Create a new Relation Type. Ensure it is a Directional Relation to set node
access relation controls. Set the source bundle as a user and the target bundle as 
a node. Set the node access permissions for the target node bundle as desired. Source 
users should now have acces to target node bundles based on the node access permissions. 

Additional linked relations where the target node bundle used above is the source can
now be created with permissions inherited through node_access_relation.  

For detailed instructions on using Relations see: 
https://drupal.org/node/1274796