============
Manage Collections
============

Collections
---------------

Collections are sub categories of the Central Data Catalog. They allow administrators of a NADA instance to group studies into what can be thought of as sub-catalogs of the Central Data Catalog.

Collections provide a number of benefits both from the user and the administrator perspective. From the users’ perspective, being able to filter and view groups (collections) of studies that logically belong together makes finding what they are looking for easier. From the administrators’ perspective, the ability to create collections of studies that may logically belong together facilitates the ability to decentralize the management of each collection of studies to specific administrators (for example collections can be managed by different departments in an institution). 

.. note::

	The creation of collections will in general only be useful and necessary for large catalogs or for catalogs that desire more decentralized management of groups of studies by different departments.

Creating collections
--------------------------
 
	Login to the Site administration using an administrator password.
	Collections are managed and created by going to the Studies, Manage collections menu link.

	There are no collections defined in the default NADA 4 installation. 


	To create a new collection click on the Create new collection button.

 
A.	Under Collection Identification, provide a short name for the collection. This will become the URL for the collection so pick carefully. For Title, fill in the fill title for the collection. This will be the name displayed at the top of the collection page.

B.	Fill in a 3 or four line short description of the collection. This text will display on the front end in the collections list. For examples  see: 
 http://microdata.worldbank.org/index.php/contributing-catalogs

C.	Fill in a more detailed description of the collection. This will display on the About page for that collection. For example see:
 http://microdata.worldbank.org/index.php/catalog/dhs/about

To format the page and include images it is possible to enter HTML code into this box: below is an example piece of code that includes an image.

<img src="files/dhs-fp-01.jpg" alt="Health Surveys Image" class="about-photo">
<h2> Health Surveys Collection</h2>
<p align="justify">The Health Surveys collection aims to provide frequent  high quality and timely health data needed by the decision makers when designing  public health programs.</p>
<p>Health surveys provide useful information on health status and health consumption and their determinants.</p>

Copy any images to be displayed  into the NADA “files” folder on your server 

D.	Upload a file to display next to the collection as it is listed on the collection page. NOTE: This image should be 82 X 82 pixels. If the upload does not work automatically then copy the thumbnail image to the “files” folder as shown above.
 
E.	The Weight field determines in what order collections are shown in the collection list.  0,1,2,3 etc. 
The Select collection type drop-down is a system value to distinguish between collections that should be viewed as internal to the organization or external. For example, some collections may be made up entirely of studies from an organization outside the host catalog. These collections can be designated as external. The Section dropdown allows for the categorization as either a collection based on a specialized collection (like health) or based on a regional breakdown. Selecting Publish – publishes the collection.

	Click on Submit to save the changes.

To view the results click on the Preview link on the far right:
 
 
	The new collection now also shows in the collection list on the Central Catalog About page (this is where the thumbnail and short description fields are displayed).

 
 

	Visiting the Dashboard will now also show the new collection listed below the Central Data Catalog. With a number of green buttons as shortcut links to manage the studies on the collection, assign administrators for the collection, a history of activity on the collection and a link to edit the collection as in the steps above.
 

