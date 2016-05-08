My inspricd mods
=======

* ModAuthor: Nikos `UrL` Papakonstantinou
* ModAuthorMail: url@mirc.com.gr
* ModDepends: core 2.0-2.1 
* ModVersion: $Rev: 22 $ 
* Thanks to Attila for various fixes.
* Thanks to Ctcp for the tests.

Desc
=======
* m_antibotctcp.cpp (Blocks clients not replying to CTCP like botnets/spambots/floodbots)
* m_ctcpxline.cpp (Under dev)
* m_timedbans.cpp (Under dev)
* m_youtube.cpp (Under dev)

Installation
=======
* 1. Download the module
* 2. Move it to the src/modules directory
* 3. Run "make install" to build and install the module.

Antibotctcp Configuration
=======
* modules.conf `<module name="m_antibotctcp.so">`
* modules.conf `<antibotctcp link="http://yoursite.gr" ctcp="VERSION" quitmsg="true" msgonreply="true">`
* inspircd.conf `<connect name="NoSpamBots" antibotctcp="true" port="7000">`
* inspircd.conf `<connect name="DisabledOnThatPort" antibotctcp="false" port="6667">`
