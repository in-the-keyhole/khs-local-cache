khs-local-cache
===============

JavaScript library that caches AJAX Api calls. Useful for offline support and caching of drop down list data for applications 

Features
--------

Transparent usage hooks into AJAX get/put/post calls... 

AMD Installation 

     Comming soon...
  
Non AMD Installation

     <script src='khs-local-cache.js'</script>

Example Configurations
----------------------

Load States json data once

     LocalCache.loadOnce('api/states');
  
Load Customer list refresh from server on change (i.e. put/post/delete)

     LocalCache.refreshOnChange('api/customers');

