Angular XML2Json
=======

thomas frank's xml2json wrapped in angularjs module as well as bower package
-----------

Steps:

  1. bower install angular-xml2json
  2. add **angularXml2json** as dependency in app.js (main module)
  3. inject **ngXml2json** in your service or controller
  4. var jsonObject = ngXml2json.parser(XML);