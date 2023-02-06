Changelog
=========

1.3.1
-----
 - added helper class to handle publication info of "hidden" contents
 - added support for Python 3.11

1.3.0
-----
 - added helper functions to get last versions of a given content
 - added support for Python 3.10
 - updated translations
 - updated versions menu status

1.2.0
-----
 - added workflow label
 - added workflow information property to keep first publication date of a managed content,
   including all it's versions
 - don't allow setting of publication date before current datetime
 - remove workflow management task interface from package
 - small updates in base workflow transition management form
 - updated style of workflow versions menu options
 - use iterator in versions sub-locations adapter

1.1.1
-----
 - import Invalid from zope.interface instead of zope.interface.interfaces

1.1.0
-----
 - removed support for Python < 3.7
 - updated workflow content transition form
 - added check against previous state before applying any transition
 - added workflow adapter for any IWorkflowVersion content
 - added timezone to all generated datetimes

1.0.1
-----
 - updated Gitlab-CI configuration
 - removed Travis-CI configuration

1.0.0
-----
 - initial release