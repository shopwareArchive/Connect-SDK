# Shopware Connect SDK


This package contains the SDK for Connect - the Vending Network, http://www.connect.shopware.com

To request an account for testing the SDK in integration with Connect send an
e-mail to `info@shopware.com`.

## Installation

   $ git clone git@github.com:shopware/Connect-SDK.git
   $ cd Connect-SDK
   $ git submodule update --init

Via ZIP, go to [Releases](https://github.com/shopware/Connect-SDK/releases)
and download the latest version.

## Documentation

See the `docs/` folder for the API documentation.

## Support

You can open issues on this project or use your Connect Account to open a
feedback request from within the Connect SocialNetwork.

## Running the Tests

You can run the testsuite through Ant Build Commons, to do this call
from the root directory:

    $ git submodule update --init
    $ ant verify

You might need to create a file `build.properties.local` with adjusted
database settings.

The testsuite is a combination of acceptance tests written in Behat and
Unit-tests written in PHPUnit.
