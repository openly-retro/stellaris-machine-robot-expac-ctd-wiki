.. Machine & Robot Expansion: Continued documentation master file, created by
   sphinx-quickstart on Sat Apr 26 19:53:40 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Machine & Robot Expansion: Continued documentation
==================================================

This mod is a continuation of XVCV's "Machines & Robot Expansion" , which is/was loved by many. A great addon for Machine empire enthusiasts which I loved playing -- it adds a variety of ascension perks, new playstyles, civics, traits, and much-needed love for Machines & Robots!

Unfortunately, since XVCV has left the Stellaris modding scene, the M&RE mod became unsupported. The original mod by XVCV can be found here. https://steamcommunity.com/sharedfiles/filedetails/?id=2441507863 

This adaptation/continuation will continue to make the original Machine & Robot Expansion compatible with the latest versions of Stellaris. In addition to bug fixes, new features are being added!

**Only one DLC is required for this mod: Synthetic Dawn** and it will stay that way.

Machine & Robot Expansion: Continued, on the Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=3163759042

Welcome
-------

I (openly-retro) am a web developer by day, and a fan of Stellaris. I enjoy science fiction a lot. Stellaris has been one of my favorite games for some time now.

Communicating
-------------

There are a few ways to get in touch about this mod, with general comments, feedback, questions:

1. Chat with me about this mod in the Stellaris Modding Den discord, Look for `Openly Retro` in the `machines-robots-expac` channel. To find a link to the discord, visit this page: https://stellaris.paradoxwikis.com/Modding#Help_links

2. Create an issue in the Github issues page for this mod: https://github.com/openly-retro/stellaris-machine-robot-expansion/issues

3. Participate in discussions on the workshop page for this mod (or create a new discussion there)

   1. Suggestions for improvements: https://steamcommunity.com/workshop/filedetails/discussion/3163759042/7260435610011379418/

   2. Bug reports: https://steamcommunity.com/workshop/filedetails/discussion/3163759042/529855118245500889/



About this documentation
------------------------

All the documentation here has been hand-written by me and where kind volunteers have helped, I have credited them.

In some places I have swapped in screenshots for text, simply because there is so much to document and I only have ten fingers.

.. important:: The documentation is a work in progress and in some places may be out of date. Please create an issue on the Github repo if you would like to report an error, as this site is non-interactive.


Recent mod updates
------------------

Update: Feb 2 @ 1:46pm (Mod version 3.0.13)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- Update and expand Simplified Chinese localisation

Many thanks to Krukal and the Doves Team for their continued dedication and time for translating this mod.

Update: Feb 1, 2026 @ 10:48pm
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Mod version 3.0.11

- Fixed Mind Separation project completion event not firing because there is no completed project in the log
- Fixed Mechanical World decision not working as expected, because it was changing the planet class to a placeholder/dummy class and that method is not necessary anymore
- Distributed Multikernel AP (vassals for machine gestalts) was being stopped by a base game rule "can_release_vassal", which I overwrote to let Machine empires with this AP release vassals, even though the rule "can_release_vassal_from_species" was working but still blocked releasing vassals (because of "can_release_vassal").
- Triggers for adding/removing genetic traits from species got updated, they were slightly out of date with what is in the base game

----



.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Contents:

   core
   ascension_perks
   civics
   origins
   planets_districts
   traits
   technologies
   overwrites
   credits
   patch_notes/index
   devlog/index


----


The Unicorn of Insanity, my companion during many a coding session. Say hello!::

                    \\
                     \%,     ,'     , ,.
                      \%\,';/J,";";";;,,.
         ~.------------\%;((`);)));`;;,.,-----------,~
        ~~:           ,`;@)((;`,`((;(;;);;,`         :~~
       ~~ :           ;`(@```))`~ ``; );(;));;,      : ~~
      ~~  :            `X `(( `),    (;;);;;;`       :  ~~
     ~~~~ :            / `) `` /;~   `;;;;;;;);,     :  ~~~~
    ~~~~  :           / , ` ,/` /     (`;;(;;;;,     : ~~~~
      ~~~ :          (o  /]_/` /     ,);;;`;;;;;`,,  : ~~~
       ~~ :           `~` `~`  `      ``;,  ``;" ';, : ~~
        ~~:                             `'   `'  `'  :~~
         ~`-----------------------------------------`~

