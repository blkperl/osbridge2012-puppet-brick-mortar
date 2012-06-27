# Osbridge 2012 - Puppet Modules: A Brick and Mortar Pattern

* This is the evolved version of the last two BeaverBarCamp presentations titled "Puppet Sucks, Use Puppet"

## Influenced by

* Tim Sharpe: http://bombasticmonkey.com/2011/12/27/stop-writing-puppet-modules-that-suck/

## Brick modules

* reusable, sharable units of code
* takes input produces output
* not specific to your organization or site
* black box
* sane defaults, should be able to override
* should be able to support multiple operatingsystems
* don't revinvent the wheel
* should follow the puppet style guide / pass puppet lint
* optional: spec tests, smoke tests, github, puppet forge

## Mortar modules

* configuration specific to your organization
* should leverage brick modules
* brings together the components of a "role"

## Hiera 

* the secret sauce in the motar
* Allows you to share mortar modules for feedback and example usage
