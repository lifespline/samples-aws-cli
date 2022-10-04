==============
CloudFront API
==============

Invalidate all cloudfront edge cached files
-------------------------------------------

.. code:: bash

   aws cloudfront create-invalidation --distribution-id <dist-id> --paths "/*"