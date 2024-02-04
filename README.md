# geom99lab2
URL 1: Developers Details Item Page 
https://developers.arcgis.com/layers/eebe713349fa41f586b3f9905505fc1a
The ArcGIS Developers site has its own UX for interacting specifically with Hosted Feature Layers in ArcGIS Online. This page should be shown after you create your new layer. The link will look similar to https://developers.arcgis.com/layers/3226b7ae87cf4f1a8bb3b36cac8108fb/. Can you find the Item id in the url? Note only the owner of the hosted feature layer will be able to open this developers URL. 

URL 2: ArcGIS Online Items Page
https://fleming.maps.arcgis.com/home/item.html?id=eebe713349fa41f586b3f9905505fc1a
ArcGIS Online's main UX has a generic AGOL Item viewer that is found in the main interface for ArcGIS Online. The URL will look similar to this: https://fleming.maps.arcgis.com/home/item.html?id=3226b7ae87cf4f1a8bb3b36cac8108fb. Anyone with the rights to see this item will be able to open this URL.
Tip: You can "paste" any item id in the place of the parameter id= to open it directly! It's like a URL shortcut. 

URL 3: REST API
https://services1.arcgis.com/pMeXRvgWClLJZr3s/arcgis/rest/services/tree_survey_geom991/FeatureServer/0 ???? (Missing access token)
The final link is different and references access to the actual data store (AKA the database and tables themselves). In the case of the item above, this URL provides access to the REST Services Directory. 
https://services1.arcgis.com/pMeXRvgWClLJZr3s/arcgis/rest/services/Geocommunity_Project_Listings/FeatureServer
Opening this URL above you can actually see the REST API endpoint has an entry to link back to the item ID! Use the Tip in URL 2 to open the ArcGIS Online Item associated with this dataset (this displays the item metadata). 
Service ItemId: 3226b7ae87cf4f1a8bb3b36cac8108fb
Important: If opening a service URL from ArcGIS Online Esri embeds this into an iframe (which hides the power of seeing the services URL directly!). So your URL will not look like above and instead like this URL (notice how the domain part is very different):
https://fleming.maps.arcgis.com/home/item.html?id=3226b7ae87cf4f1a8bb3b36cac8108fb&view=service (pretty much the same as URL 2, with view=service added). 
To open the REST API Endpoint URL directly in a new tab using Chrome:
•	Option 1: Right click on the framed part of the window, then select View Frame Source. It will open the code section but you can just remove the view-source: portion of the URL and it will open exposing the desired URL. 
•	Option 2: Right-Click on one of the blue "breadcrumb" links at the top of the window and tell Chrome to open it in "a new tab".
