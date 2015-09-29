==============
pingdom-python
==============
**Depricated**

Special Note 9/29/2015:  The original author has long since merged the 
PR reference in the previous note. Please use his new version! 

Special Note 3/16/2011: I have an email out to the original author about
 a pull request back to the original trunk. I'd like to see these changes
 pulled into the original for pypi consideration.

3rd-party Python library for Pingdom_.'s new REST API.
Note that this API is still in beta, so may change at any time.  For more
information about the API, see Pingdom's blog post_.

Currently, the library supports:

* Checks (create, delete, get, list)

============
Requirements
============

- Pingdom account
- simplejson (Python 2.5 and earlier)
- requests

=============
Documentation
=============

More project documentation can be found in the docs directory. Documentation
can be built using sphinx.

    pip install sphinx

    cd docs

    make html

.. _Pingdom: http://pingdom.com
.. _post: http://royal.pingdom.com/2011/03/22/new-pingdom-api-enters-public-beta/
