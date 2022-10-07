Do's and Don'ts
===============

Do's
----

#. Annotate products which are clearly visible and recognisable.

   .. image:: images/CORRECT_BOUNDING_BOX.jpg
      :width: 600 

#. Products that are easily recognizable or that are only 20% hidden or covered should be **annotated** and **included**.

#. Annotate products which have other products along with them or having other products on them, such as: 

   #. Pillows on sofa, chair, bed
   #. Lamps, bowl, vase, books, etc. on top of Tables
   #. Blanket, comforter on bed or chaise
   #. etc.

   .. image:: images/PRODUCT_ON.jpg
      :width: 600 

Don'ts
------

#. Do not annotate products which are not completely visible in image or may not be present in the catalogue.

   .. image:: images/NOT_COMPLETELY_VISIBLE.jpg
      :width: 600

#. Do not annotate products which are obscured or have other objects/products blocking that product which makes the product hardly recognisable like below example:

   .. image:: images/INCORRECT_BOUNDING_BOX_OBSCURED_PRODUCTS.jpg
      :width: 600

#. Top view or elevated angle images should be **excluded** from the dataset. **Do not** include images which contain top view or elevated angle of products. (Refer example below)

   .. image:: images/TOP_VIEW_IMAGE_TO_EXCLUDE.jpg
      :width: 600

#. Back view images of products can be included if those products are recognisable completely.





.