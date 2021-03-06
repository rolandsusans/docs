REST API
========

**Please remember to use the API specific variant of a product.**

Quote Data
----------
Query string data appended to the quote request

.. csv-table::
   :header: "Name", "Type", "Description", "Example Value"
   :widths: 20, 20, 80, 20

   "cover", "int", "Insurance cover amount. Available values: 100000,500000,1000000",      "100000"


Policy Data
-----------
JSON data posted to /policies on creation of policy

.. csv-table::
   :header: "Name", "Type", "Description", "Example Value"
   :widths: 20, 20, 80, 20

   "city",            "string", "Name of City obtained from Google Maps API",     "München"
   "street",          "string", "Name of Street obtained from Google Maps API",   "Arnulfstraße"
   "house_number",    "string", "House Number obtained from Google Maps API",     "1"
   "postcode",        "string", "DE postcode obtained from Google Maps API",      "80335"
   "first_name",      "string", "Free text string up to 255 characters.",         "Name"
   "last_name",       "string", "Free text string up to 255 characters.",         "Surname"
   "email",           "string", "Free text string up to 255 characters.",         "name@test.de"
