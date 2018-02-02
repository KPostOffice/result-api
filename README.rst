Thoth-core result API
=====================

This simple API service serves as a result storing API service in the `Thoth-core project <https://github.com/fridex/thoth-core>`_.

It's main aim is to abstract database type and database details in analyzers and pods that are run in `thoth-middeend` part. See `Thoth-core <https://github.com/fridex/thoth-core>`_ for more details.

The service is built using OpenShift s2i. The configuration of s2i build is specified in the `.s2i/environment file <https://github.com/fridex/thoth-result-api/blob/master/.s2i/environment>`_. See also `s2i-python-container README <https://github.com/sclorg/s2i-python-container>`_ for more info. There is required Python 3.6 to run this application, the actual s2i build config is part of `Thoth-core OpenShift template <https://github.com/fridex/thoth-core/blob/master/openshift/template.yaml>`_.
