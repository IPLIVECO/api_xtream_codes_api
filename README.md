 ## Download api.php and upload to your web hosting, amend URL at top of api.php for your server 
 
 * The methods are accessed via GET or POST by sending some parameters.

 * User login & password = Required on all requests

 * Call Login: api.php?op=login&username=username&password=password

 * Call categorys of channels: api.php?op=category_channels&username=username&password=password

 * Call all os channels: api.php?op=channels&username=username&password=password

 * Call channels by category: api.php?op=channels&category=ID&username=username&password=password
 
 * Call categorys of Vods (Films): api.php?op=category_vods&username=username&password=password
 
 * Call All of Vods (Films): api.php?op=vods&category=ID&username=username&password=password
 
 * Call Vods by category: api.php?op=vods&category=ID&username=username&password=password
 
 * Call Categorys Series: api.php?op=category_series&username=username&password=password
 
 * Call All as Series: api.php?op=series&username=username&password=passwor

 * Call Series by category: api.php?op=series&category=ID&username=username&password=password

 * Call Information of Vod (Film): api.php?op=vod&id=ID&username=username&password=password

 * Call Information of Series: api.php?op=serie&id=ID&username=username&password=password

 * Layer EPG Summarized By Channel: api.php?op=epg_simples&id=ID&username=username&password=password
 
 * Layer EPG Complete By Channel: api.php?op=epg&id=ID&username=username&password=password
 
 * Layer Todo EPG Full: api.php?op=epgfull&username=username&password=password
 
 * Call to convert the M3U list to JSON: api.php?op=lists&username=username&password=password
 
 ## Make the calls through your browser by the URL you use there 
 * Example: www.mydomain.com/api.php?op=epgfull&username=username&password=password

## Version 1.0 
 * Need to Treat and Adapt Arrys and Values

