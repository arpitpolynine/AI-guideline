AI - Dataset Annotating and Labelling Guidelines 
================================================

.. image:: https://readthedocs.org/projects/example-sphinx-basic/badge/?version=latest
    :target: https://example-sphinx-basic.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status
`View the web version. <https://ai-guideline.readthedocs.io>`_

Guidelines on products to be considered for Annotation:
-------------------------------------------------------

This section includes guidelines to follow to make a decision on which products need to be included into the dataset and the products that should be excluded.

#. **Annotate** products which are clearly visible and recognisable.
   
   .. image:: images/CORRECT_BOUNDING_BOX.jpg
      :width: 300 

#. **Do not** annotate products which are not recognisable completely or may not be present in the catalogue.

   .. image:: images/NOT_COMPLETELY_VISIBLE.jpg
      :width: 300

#. **Annotate** products which have other products along with them or having other products on them, such as: 

   #. Pillows on sofa, chair, bed
   #. Lamps, bowl, vase, books, etc. on top of Tables
   #. Blanket, comforter on bed or chaise
   #. etc.

   .. image:: images/PRODUCT_ON.jpg
      :width: 300 

#. **Do not** annotate products which are obscured or have other objects/products blocking that product which makes the product hardly recognisable like below example:

   .. image:: images/INCORRECT_BOUNDING_BOX_OBSCURED_PRODUCTS.jpg
      :width: 300

#. Top view images are to be **excluded** from the dataset. **Do not** include images which contain top view of products, unless those type of products are present in the catalogue. (Refer example below)

   .. image:: images/TOP_VIEW_IMAGE_TO_EXCLUDE.jpg
      :width: 300



