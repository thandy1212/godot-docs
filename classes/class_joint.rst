.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Joint.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Joint:

Joint
=====

**Inherits:** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`ConeTwistJoint<class_conetwistjoint>`, :ref:`Generic6DOFJoint<class_generic6dofjoint>`, :ref:`SliderJoint<class_sliderjoint>`, :ref:`HingeJoint<class_hingejoint>`, :ref:`PinJoint<class_pinjoint>`

**Category:** Core

Brief Description
-----------------

Base class for all 3D joints

Member Variables
----------------

  .. _class_Joint_collision/exclude_nodes:

- :ref:`bool<class_bool>` **collision/exclude_nodes** - If ``true`` the two bodies of the nodes are not able to collide with each other.

  .. _class_Joint_nodes/node_a:

- :ref:`NodePath<class_nodepath>` **nodes/node_a** - The :ref:`Node<class_node>`, the first side of the Joint attaches to.

  .. _class_Joint_nodes/node_b:

- :ref:`NodePath<class_nodepath>` **nodes/node_b** - The :ref:`Node<class_node>`, the second side of the Joint attaches to.

  .. _class_Joint_solver/priority:

- :ref:`int<class_int>` **solver/priority** - The order in which the solver is executed compared to the other Joints, the lower, the earlier.


Description
-----------

All 3D joints link two nodes, has a priority, and can decide if the two bodies of the nodes should be able to collide with each other

