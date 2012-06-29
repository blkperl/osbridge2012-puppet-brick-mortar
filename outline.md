# Osbridge 2012 - Puppet Modules: A Brick and Mortar Pattern

## Influenced by

* Tim Sharpe: Stop Writing Puppet Modules That Suck, http://bombasticmonkey.com/2011/12/27/stop-writing-puppet-modules-that-suck/
* Craig Dunn: Designing Puppet – Roles and Profiles, http://www.craigdunn.org/2012/05/239/

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

* the secret sauce in the mortar
* Allows you to share mortar modules for feedback and example usage
