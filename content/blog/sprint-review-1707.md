Title: Sprint Review 17.07
Date: 2017-05-15
Author: The Wazo Authors
Category: Wazo IPBX
Tags: wazo, development
Slug: sprint-review-1707
Status: published

Hello Wazo community! Here comes the release of Wazo 17.07!

New features in this sprint
---------------------------

**Admin UI**: The new web interface based on our REST API is now available for preview. See [Wazo admin UI](wazo-admin-ui)

**Admin UI**: IVR can now be managed from the admin UI

**Admin UI**: CDR can now be listed and searched from the admin UI instead of downloading a CSV from the old web interface.

**Admin UI**: Conference rooms using Asterisk confbridge can be managed using the admin UI

**Admin UI**: Parkings using Asterisk parking lots can be managed using the admin UI

**Admin UI**: Plugins can be managed from the admin UI

**REST API**: We have added a new REST API to manage wazo plugins using wazo-plugind. This new API is used by the administration UI to install and enable features.

**REST API**: CDR can now be queried by user to get its own call logs.


Ongoing features
----------------

**Call logs**: We are attaching more data to the call logs and generating new views to have a summary for a given query instead of a list of call logs.

**Admin UI**: We are working to improve the new web interface.

**Plugin management**: There is still a lot to be done to the plugin management service. e.g. dependency, upgrade, wazo version constraint, HA, ..


---

The instructions for [installing Wazo](http://documentation.wazo.community/en/stable/installation/installsystem.html) or [upgrading Wazo](http://documentation.wazo.community/en/stable/upgrade/upgrade.html) are available in the documentation.

For more details about the aforementioned topics, please see the roadmap linked below.

See you at the next sprint review!

Sources:

* [Upgrade notes](http://documentation.wazo.community/en/wazo-17.07/upgrade/upgrade.html#upgrade-notes)
* [Wazo 17.07 Roadmap](https://projects.wazo.community/versions/259)
