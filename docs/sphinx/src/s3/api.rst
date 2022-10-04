======
S3 API
======

Empty Bucket
------------

.. code:: bash

   $ aws s3 rm --recursive s3://<bucket-name>

Copy recursively from local to bucket
-------------------------------------

.. code:: bash

   $ aws s3 cp --recursive s3://<bucket-name>