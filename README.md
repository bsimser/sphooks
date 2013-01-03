Webhooks for SharePoint
==

This project provids Webhooks for SharePoint (2010/2013) and allows you to create user-defined HTTP callbacks and attach them to SharePoint lists. A hook is created and attached to an event on a SharePoint list then whenever that event occurs, your hook is triggered with some metadata about the event and your system can respond to it.

The project is modelled on the [Repo Hooks API](http://developer.github.com/v3/repos/hooks) from github and offers various methods to hook into a SharePoint list.

* List
* Get single hook
* Create a hook
* Edit a hook
* Test a hook
* Delete a hook

Hooks can be configured to trigger to one or more events. The available events are:

* item_added
* item_updated
* item_deleted

Once the Webhooks feature is activated on a site, all lists are "Hook enabled". All you need to do is create a hook using the API below to start using it.

All responses are on JSON format.

List
---
Lists all hooks attached to a list.

Get
---
Gets a single hook

Create
---
Create a hook

Edit
---
Edit a hook

Test
---
This will trigger a hook with the latest contents of a SharePoint list.

Delete
---
Deletes an installed hook.

Many thanks to Javier Lozano (@jglozano) for the inspiration for creating this.

Hope it helps!
