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

* *item_adding* - An item is being added
* *item_added* - An item has been added
* *item_updating* - An item is being updated
* *item_updated* - An item has been updated
* *item_deleting* - An item is being deleted
* *item_deleted* - An item has been deleted
* *item_checking_in* - An item is being checked in
* *item_checked_in* - An item has been checked in
* *item_checking_out* - An item is being checked out
* *item_checked_out* - An item has been checked out

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
