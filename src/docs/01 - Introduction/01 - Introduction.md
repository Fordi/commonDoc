Extending the RSuite User Interface
===================================

General introduction
--------------------

* High level introduction to the idea of extending the RSuite UI and
  what this document is about

* After the first few general sections, each section builds upon the
  others so that the user can create something that looks like the
  workflow admin page.

Core UI framework concepts
--------------------------

* General concepts around model objects, view templates, view objects
  and controllers

* No real detail here and some information can be the general Ember docs
  if needed. Most detail will be in the following
sections.

What are the core abstractions and components that can be reused or extended in the UI framework?
-------------------------------------------------------------------------------------------------

* Summary/Glossary of core terms or concepts

* Basic list of the core UI abstractions and components used in this
  document.

* How do we extend or reuse these components?

How to call a custom web service from javascript?
-------------------------------------------------

* Also include an example that uses a form for basic parameters

How to pop a form dialog and use the values from that form?
-----------------------------------------------------------

* Also include how to handle the basic results like the dialog results,
  or a description on how the framework deals with that response.

How to customize the UI styling and theming?
--------------------------------------------

* Just some basic information on how to do it and where to find the
  appropriate CSS information to override.

* This is not meant to be a guide about creating your own “complete”
  theme.

How to create a new page?
-------------------------

* Just information to create a new page without any real UI components,
  just the page and its tab icon.

How to create the frames for a sidebar and a results area?
----------------------------------------------------------

* Create a sidebar similar to workflow browse/standard searches

* Create the results area, but do not retrieve any results yet.

How to retrieve and display a results?
--------------------------------------

* Like the workflow admin page, click an item and get results (content,
  tasks or anything else)

  * For results that are custom objects, what javascript model objects
    are needed.

* Display the results in the content frame

* Have a context menu appear when clicking the gear for a results
item

How to add context menu actions for a result item?
--------------------------------------------------

How to add context menu actions for a set of results, i.e. bulk actions?
------------------------------------------------------------------------

* Add information on what the web services need to do to handle bulk
  actions and how that is different from the normal actions

How to add an action to a sidebar menu?
---------------------------------------

* Like the workflow/content search pages, create a general menu and add
  actions to it

How to add actions to the global menu and the user menu?
--------------------------------------------------------

* Any other standard menus in the system that we need to talk about?

How to retrieve and display a list of content objects (MOs or CAs)?
-------------------------------------------------------------------

* If they create a page that will display MOs/CAs as its results, how do
  they do that and get all of the built-in functionality like
  collapsing/expanding the items?

How to retrieve and display a list of tasks?
--------------------------------------------

* If they create a page that will display tasks/workflows as its
  results, how do they do that and get all of the built-in
  functionality?
