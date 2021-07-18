# RecordRanch

Record Ranch is a small online record store, that currently exists at <a href="http://recordranch.com/">recordranch.com</a> and it is getting an update!
All of the website's new pages and resources are stored here, and are in the procces of being moved to recordranch.com.
The contents of this repository was originally stored and tested on another website, which is why the repository is moving in the first place.

The new website includes more information on the home page, links social media accounts and makes the design look better. While the update focuses on a better experience for 
the user it also make changing the website easier. For example, the side bar buttons are loaded in from a file, so if the file is changed and a button is added, the change 
will reflect on the entire website! Before, if a button needed to be added all of the pages would need to be edited. 

The update's biggest feature is the new <a href="https://github.com/Super-Teddy/RecordRanch/blob/main/Catalog.html">catalog</a>. The catalog now organizes records on sale in 
a nice way while keeping it easy to manage for us, However the catalog needs to connect to a node.js server to get the data for the catalog. 
This makes things much more difficult because while the node.js server was configured on our server, 
it needs to be moved with everything else to the other server, requiring it to be reconfigured and run as a daemon process on the other server.

And that's where we are now.
