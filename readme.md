WordPress' excellent wpautop function as a standalone library.

Usage
-----

Install via Composer:

    {
        "require": {
            "xmeltrut/autop": "1.0.0"
        }
    }

Then call in the code:

    \Xmeltrut\Autop\Autop::format('string');

References
----------

* [http://ma.tt/scripts/autop/](http://ma.tt/scripts/autop/)
* [https://core.trac.wordpress.org/browser/trunk/src/wp-includes/formatting.php](https://core.trac.wordpress.org/browser/trunk/src/wp-includes/formatting.php)
