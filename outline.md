# Osbridge 2012 - Puppet Modules: A Brick and Mortar Pattern

* This is the evolved version of the last two BeaverBarCamp presentations titled "Puppet Sucks, Use Puppet"

## Influenced by

* Tim Sharpe: http://bombasticmonkey.com/2011/12/27/stop-writing-puppet-modules-that-suck/

## Brick modules

* reusable, sharable unit of code
* takes input produces output
* not specific to your organization or site
* black box
* sane defaults, should be able to override
* should be able to support multiple operatingsystems
* don't revinvent the wheel
* optional: tests, github, forge

## Mortar modules

* configuration specific to your organization
* should leverage brick modules

## Hiera 

* the secret sauce in the motar
* use hiera so can give access to the mortar modules to trusted users
