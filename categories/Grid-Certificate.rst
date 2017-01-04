
Grid certificate
****************

.. contents:: 
    :depth: 5


.. _get-cert:

===================================
Getting the Dutch grid certificate
===================================

1. ...

.. _non-dutch:
===============
Non-Dutch CA
===============
1. An Australian user needed the grid certificate. She had to get it from Taiwan as she could not find the local CA [`t1`_]

2. Two users from Switzerland needed the ceritifcate. They were pointed to the `Swiss CA`_  [`t2`_]

*Is there a list of CAs for all countries? What should be our standard response?*

..  _prob-cert:
===================================
Problems with using the certificate
===================================

1. ...

.. _renew-cert:
===================================
Renewing the certificate
===================================

1. The users can do it themselves (`renew certificate`_). However, some users at UvA could not do it [`t3`_].

- The user should go to https://www.digicert.com/sso where he/she has to enter the University name and is redirected to login via their internal (UvAnet) ID. Here the user can renew the certificate.

- This works only if they have the right attributes/entitlements (can be checked via https://profile.surfconext.nl). They get an error
 .. code-block:: console
 
    SAML Error
    You do not have permission to order a certificate

- The users missing the following attributes could not renew the certificate

  .. code-block:: console

   urn: mace: terena.org: TCS: eScience user
   urn: mace: terena.org: TCS: personal-user

- Write to servicedesk-icts@uva.nl and ask them to add these to the user's profile on https://profile.surfconext.nl. That should do the trick.

*How do we solve this problem for all the users? Contact the UvA ICT or update our wiki so the users do it themselves?*

.. Links:

.. _`t1`: https://helpdesk.surfsara.nl/ticket/12805 

.. _`Swiss CA`: https://www.switch.ch/pki/manage/request/user-certificate/

.. _`t2`: https://helpdesk.surfsara.nl/ticket/15070

.. _`renew certificate`:  http://doc.grid.surfsara.nl/en/latest/Pages/FAQ.html#how-can-i-renew-my-certificate.html

.. _`t3`: https://helpdesk.surfsara.nl/ticket/13282


