.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Physics2DShapeQueryParameters.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Physics2DShapeQueryParameters:

Physics2DShapeQueryParameters
=============================

**Inherits:** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Parameters to be sent to a 2D shape physics query.

Member Functions
----------------

+-------+-------------------------------------------------------------------------------------------------------------------+
| void  | :ref:`set_shape<class_Physics2DShapeQueryParameters_set_shape>` **(** :ref:`Resource<class_resource>` shape **)** |
+-------+-------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_Physics2DShapeQueryParameters_collision_layer:

- :ref:`int<class_int>` **collision_layer** - The physics layer the query should be made on.

  .. _class_Physics2DShapeQueryParameters_exclude:

- :ref:`Array<class_array>` **exclude** - The list of objects or object :ref:`RID<class_rid>`\ s, that will be excluded from collisions.

  .. _class_Physics2DShapeQueryParameters_margin:

- :ref:`float<class_float>` **margin** - The collision margin for the shape.

  .. _class_Physics2DShapeQueryParameters_motion:

- :ref:`Vector2<class_vector2>` **motion** - The motion of the shape being queried for.

  .. _class_Physics2DShapeQueryParameters_shape_rid:

- :ref:`RID<class_rid>` **shape_rid** - The :ref:`RID<class_rid>` of the queried shape. See :ref:`set_shape<class_Physics2DShapeQueryParameters_set_shape>` also.

  .. _class_Physics2DShapeQueryParameters_transform:

- :ref:`Transform2D<class_transform2d>` **transform** - the transform matrix of the queried shape.


Description
-----------

This class contains the shape and other parameters for intersection/collision queries.

Member Function Description
---------------------------

.. _class_Physics2DShapeQueryParameters_set_shape:

- void **set_shape** **(** :ref:`Resource<class_resource>` shape **)**

Set the :ref:`Shape2D<class_shape2d>` that will be used for collision/intersection queries.


