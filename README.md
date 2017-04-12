DoctrineFixturesGeneratorBundle
===============================
[![Latest Stable Version](https://poser.pugx.org/webonaute/doctrine-fixtures-generator-bundle/v/stable.svg)](https://packagist.org/packages/webonaute/doctrine-fixtures-generator-bundle) [![Total Downloads](https://poser.pugx.org/webonaute/doctrine-fixtures-generator-bundle/downloads.svg)](https://packagist.org/packages/webonaute/doctrine-fixtures-generator-bundle) [![Latest Unstable Version](https://poser.pugx.org/webonaute/doctrine-fixtures-generator-bundle/v/unstable.svg)](https://packagist.org/packages/webonaute/doctrine-fixtures-generator-bundle) [![License](https://poser.pugx.org/webonaute/doctrine-fixtures-generator-bundle/license.svg)](https://packagist.org/packages/webonaute/doctrine-fixtures-generator-bundle)

*** THIS IS UNSUPPORTED BRANCH ***
==================================
I am merging what I can in this branch from time to time. But I am not testing it. Feel free to create pull request to fix issues. It should work with Symfony < 3.x and PHP < 5.6.x

==================================

Generate Fixture from your existing data in your database. You can specify the Entity name and the IDs you want to import in your fixture.

Only ready stuff are publish on git for now. This is not a functional bundle!!!


Features include:

- Create fixture from existing entity data.
- Option to specify the exact IDs to import in your fixture.
- Option to specify a ranges of ids to import in your fixture. (Thanks to [andreyserdjuk](https://github.com/andreyserdjuk))
- Manually set load order for a fixture from command line. (Thanks to [ioniks](https://github.com/ioniks))
- Allow to specify in the command line the specific load order we want for the generated fixture.
- **NEW** Snapshot : Create a full sets of fixtures from your current database.
- **NEW** Automatically set the load order in the snapshot context.
- **NEW** Generate fixture reference when any other entity is link to this entity in the snapshot context.

**Caution:** This bundle is a development bundle and actually in high development itself and should not be use on production server.

Version note
-------------
- For symfony 2.3 and 2.4, use the version v1.0.*
- For symfony 2.5 and over, use the version v1.1.* or dev-master.
- Our version 1.3 is tested with symfony >=2.7 and PHP 7.0

Documentation
-------------

The bulk of the documentation is stored in the `Resources/doc/index.md`
file in this bundle:

[Read the Documentation for master](https://github.com/Webonaute/DoctrineFixturesGeneratorBundle/blob/master/Resources/doc/index.md)

Installation
------------

All the installation instructions are located in the documentation.

License
-------

This bundle is under the MIT license. See the complete license in the bundle:

    Resources/meta/LICENSE

About
-----

DoctrineFixturesGeneratorBundle is a [Webonaute] initiative.
See also the list of [contributors](https://github.com/Webonaute/DoctrineFixturesGeneratorBundle/contributors).

Reporting an issue or a feature request
---------------------------------------

Issues and feature requests are tracked in the [Github issue tracker](https://github.com/Webonaute/DoctrineFixturesGeneratorBundle/issues).

When reporting a bug, it may be a good idea to reproduce it in a basic project
built using the [Symfony Standard Edition](https://github.com/symfony/symfony-standard)
to allow developers of the bundle to reproduce the issue by simply cloning it
and following some steps.

Help development
----------------

If you like this bundle, you can donate bitcoin to this address : 13zeEE6qdWJfSpNWwtWUuMoKTYGWU6jNwc

Thank you!
