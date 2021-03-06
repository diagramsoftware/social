
    .. image:: https://github.com/blooparksystems/website/blob/8.0/website_social_media_icon_extention/static/description/XING.png?raw=true
       :width: 100
       :target: http://www.xing.com
    
Extend Social Media Links
=========================

.. image:: https://github.com/blooparksystems/website/blob/8.0/website_social_media_icon_extention/static/description/settings.png?raw=true
   :width: 700

.. image:: https://github.com/blooparksystems/website/blob/8.0/website_social_media_icon_extention/static/description/webpage.png?raw=true
   :width: 700

Currently added:

- Xing

Info:
-----

- By default, the icon will be shown on the footer, about us, and the Blog, like the original icons.

Configuration
-------------

- go in the backend under settings / website
- you can now also add your Xing Account

Usage:
------

- normal social icons:

    <a t-att-href="website.social_facebook" t-if="website.social_facebook"><i class="fa fa-facebook-square"/></a>
    
    <a t-att-href="website.social_twitter" t-if="website.social_twitter"><i class="fa fa-twitter"/></a>
    
    <a t-att-href="website.social_linkedin" t-if="website.social_linkedin"><i class="fa fa-linkedin"/></a>
    
    <a t-att-href="website.social_youtube" t-if="website.social_youtube"><i class="fa fa-youtube-play"/></a>
    
    <a t-att-href="website.social_googleplus" t-if="website.social_googleplus"><i class="fa fa-google-plus-square"/></a>
    
    <a t-att-href="website.social_github" t-if="website.social_github"><i class="fa fa-github"/></a>

- the new social icons:

    <a t-att-href="website.social_xing" t-if="website.social_xing"><i class="fa fa-xing"/></a>    

Credits
=======

Contributors
------------

* Benjamin Bachmann (benniphx@gmail.com)

Maintainer
----------

.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose mission is to support the collaborative development of Odoo features and promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.