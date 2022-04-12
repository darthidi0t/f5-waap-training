Logging into Distributed Cloud Console
========================

You should have received an email with an invitation to access Distributed Cloud Console.

The name of the tenant that we will be using is ``f5-sales-public``

Exercise #1: Login to Distributed Cloud Console
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You will need to create a password that will be associated with your email address.

If you have NOT received an email from our system you may need to provide an alternate
email address that we can use for the purposes of this lab.


**Distributed Cloud Console**

Distributed Cloud Console is a SaaS control-plane for Volterra services that provides a UI and API for managing network, security, and compute services.

Distributed Cloud Console can manage "sites" in existing on-prem data centers and sites in AWS, Azure, and GCP cloud environments.

Using Distributed Cloud Console, an end-user can centrally manage a distributed application environment.

Terminology
~~~~~~~~~~~~~

Namespace
    Namespace is a term that is commonly used in Kubernetes.  It can be thought of as a grouping of resources.

Exercise 2: Select your Persona
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Please log into your assigned Volterra tenant. https://f5-sales-public.console.ves.volterra.io/

    .. note:: The Distributed Cloud Console GUI has a relatively short timeout. This is not configurable. We have an enhancement request to allow this to be configured.

#. When you first login you will need to select your "persona"

   Enter your persona as "SecOps" and level as "Intermediate".  You can change these settings after logging in as well.

   Your persona will highlight workflows within Distributed Cloud Console.  You will be able to access all services, but making use of
   personas can focus your view on particular tasks that are relevant to your role.

#. Several tooltips will appear.  You can close these out.

Exercise 3: Identity your Namespace
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Click on "Account Settings" by expanding the "Account" icon in the top right of the screen and 
   clicking on "Account Settings"

   .. image:: ../_static/screenshot-account-settings.png
#. Next click on "My Namespaces" and take note of the `studentxxx` namespace that you have been assigned.  Each student will have a unique number.

   .. image:: ../_static/screenshot-mynamespaces.png 
