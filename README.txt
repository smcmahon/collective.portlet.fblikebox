Introduction
============

Advertise your organization's desire to be liked with a Facebook "Like Box"
in a portlet. For more information on FB Like Boxes, see
https://developers.facebook.com/docs/plugins/page-plugin.

Like boxes are implemented via Facebook's jssdk.

Configurable properties include the FB Page URL, facepile, height and tabs.

Installation
============

Simply add collective.portelet.fblikebox to your egg list. Run buildout,
restart Plone, then use the add/remove add-on configlet in site setup to
enable the add on for a particular site.

Compatibility
=============

This should work with Plone 3 or 4 -- until Facebook changes the API and
breaks it.