Naming convention
=================

Technology
----------

Technologies in OSeMBE are named according to the following structure:

+---------+-----------+-------------------+--------------+-------+-------+-----+----------------+
| **AA**  |  **BB**   |       **CC**      |     **D**    | **E** | **F** |     | **AABBCCDEF**  |
+---------+-----------+-------------------+--------------+-------+-------+-----+----------------+
| Country | Commodity | Technology /      | Energy level | Age   | Size  | --> | Technology     |
|         |           | connected Country |              |       |       |     | name           |
+---------+-----------+-------------------+--------------+-------+-------+-----+----------------+

The different codes are available under :doc:`Countries <../countries>`, :doc:`Fuels/Commodities <../fuels>` and :doc:`Technologies <../technologies>`. The energy level is either P if a primary energy commodity is the output, or F if final electricity is the output, I indicates an import technology, and X an extraction or generation technology. The age can have the values H or N which stand for historic and new. The size can be 1 indicating small, 2 medium or 3 large technologies. 

Fuels
-----

Commodities in OSeMBE are named according to the following structure:

+---------+-----------+-----+----------------+
| **AA**  |  **BB**   |     |    **AABB**    |
+---------+-----------+-----+----------------+
| Country | Commodity | --> | Commodity name |
+---------+-----------+-----+----------------+
