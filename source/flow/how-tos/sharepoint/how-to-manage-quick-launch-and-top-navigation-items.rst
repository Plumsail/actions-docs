How to manage quick launch and top navigation items for a SharePoint site using Power Automate (Microsoft Flow) or Azure Logic Apps
===================================================================================================================================

This article will show how to manage quick launch and top navigation items for a SharePoint site using these Plumsail actions:

- `Add SharePoint site navigation node <https://plumsail.com/docs/actions/v1.x/flow/actions/sharepoint-processing.html#add-sharepoint-site-navigation-node>`_ .
- `Remove SharePoint site navigation node <https://plumsail.com/docs/actions/v1.x/flow/actions/sharepoint-processing.html#remove-sharepoint-site-navigation-node>`_ .


You can add/remove a navigation node to/from two places: Top navigation bar or Quick launch 

.. image:: ../../../_static/img/flow/how-tos/sharepoint/place-selection.png

Let's say you need to add a Quick launch navigation node each time an item is created in a specific list.


.. image:: ../../../_static/img/flow/how-tos/sharepoint/add-remove-nodes-site-example.png


We can use this simple flow which is triggered when an item is created.

.. image:: ../../../_static/img/flow/how-tos/sharepoint/flow-example.png


Also we can add navigation nodes to the top menu. For example, there could be this flow

.. image:: ../../../_static/img/flow/how-tos/sharepoint/top-menu-navigation-node-example.png

When you create a subsite the flow adds navigation node to the top menu of the parent site.

The same way you can program Power Automate (Microsoft Flow)s to remove navigation nodes when an item or subsite is removed.

.. image:: ../../../_static/img/flow/how-tos/sharepoint/remove-example.png


Conclusion
----------

That's all! It's possible to manage your SharePoint site navigation very effectively using Plumsail Add/Remove navigation node action.