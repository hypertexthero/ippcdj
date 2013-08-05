# Todo:
    
- Restricted Work Area
   - [Restricted area working group pages and working group view/add permissions](http://djangosnippets.org/snippets/2736/).
   - In sidebar only list pages that are available to the user
    - [File & publication uploads tied to pages and restricted pages](https://github.com/sigurdga/django-jquery-file-upload)
      - Fix media upload button not displaying in Firefox (is it dependent on Flash? If so, get rid of this dependency.) **Or** use new file upload app.
    - List pages accessible to each user [according to permissions](http://stackoverflow.com/a/16016717)
    - Permissions groups: 
        - Anonymous User - AUTO
        - Logged In User - AUTO
        - Administrator - AUTO
        - Secretariat
        - Country Chief Editor
        - Country Editor - DONE
        - Partners/RPPO Editor
        - Working Groups
            - Standards Committee 
            - TPDP 
            - TPPT 
            - TPG 
            - TPFQ 
            - TPFF 
            - Bureau 
            - SBDS 
            - IFQR 
            - TPDPC 
            - CDC 
            - ISLG 
            - Observers 
            - EphytoXml 
            - EphytoSecurity 
            - WGSeaContainer 
            - EwgSeeds 
            - EwgUsedEquipment 
            - FaoPlantProtectionOfficers 
            - FrameworkforStandards

- Country pages:
    - Other country forms
    - [Pest Report mapping](http://leafletjs.com/examples/choropleth.html)
    - Versioning of Pest Reports. Report number: GBR-32/1. When edited: GBR-32/2.
    - Prevent hidden report titles from appearing in search results

- Public Pages
    - Versioning of all page content?

- User registration open but behind login-required and super-user required so only admins can add new users, OR, user registration open to all, but need approval by admins.

- Sitemap
- [Calendar](https://github.com/shurik/mezzanine.calendar)
- Forums
- Email utility
- Contact form
