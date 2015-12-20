# GWT-SmartGWT-Maven-sample
Vytvořil jsme GWT aplikaci přes Ideu. Přidal jsem Maven. Do Mavenu jsem přidal závislosti pro GWT a SmartGWT. Upravil jsme aplikaci tak aby v ní fungovalo SmartGWT

###Přidání SmartGwt ve verzi > 4.1 
Spustíme tento příkaz

    mvn com.isomorphic:isc-maven-plugin:install -Dproduct=SMARTGWT -Dlicense=LGPL -DbuildNumber=5.0p -DbuildDate=2015-11-29

více zde:

https://gist.github.com/jirikrepl/49e59b43cc9d29c9fd49

###superdevmode v 2.7.0 a linkování *.js soubroů v smartGWT-5.1
https://code.google.com/p/smartgwt/issues/detail?id=758

http://www.smartclient.com/smartgwt/javadoc/com/smartgwt/client/docs/SuperDevModeTroubleshooting.html

http://forums.smartclient.com/forum/smart-gwt-technical-q-a/32571-gwt-2-7-smartgwt-5-does-not-load-skins?t=31789

# 2. možnost
Vygenerovat GWT z archetypu pro Maven https://github.com/tbroyer/gwt-maven-archetypes
