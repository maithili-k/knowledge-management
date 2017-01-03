
Grid certificate
******************


**Getting the Dutch grid certificate**

**Non-Dutch CA**

**Problems with using the certificate**

**Renewing the certificate**

1. The users can do it themselves [renew certificate](http://doc.grid.surfsara.nl/en/latest/Pages/FAQ.html#how-can-i-renew-my-certificate.html). However, some users could not do it.

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

*How do we solve this problem for all the users? Contact the ICT or update our wiki so the users do it themselves?*
