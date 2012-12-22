User Guide
######################

:date: 2012-12-12 22:00
:category: guide
:author: Neal Tao

Get your first Clamra addresss
---------------------------------
send to an email to **start@clamra.com** and follow the instructions

Get more Clamra addresss
--------------------------
send to an email to **create@clamra.com** and follow the instructions

Send mute/unmute commands
----------------------------
If your Clamra address is **someuser@claram.com** , send email to  **someuser+command@clamra.com** ,
specfic your command in email body . ::

    mute abc@example.com   # mute abc@example.com
    mute @example.com      # mute the whold example.com domain
    unmute cdf@example.com # unmute cdf@example.com
    unmute @example.com    # unmute domain example.com

You can include multiple commands in the message.

Send email 
----------------------------
If your Clamra address is **someuser@claram.com** , send an email to  **someuser+send@clamra.com** ,
like this ::

    From: you-email@example.com
    To: someuser+send@clamra.com
    Subject: [to:real-target@domain.com]Your Subject

We will send the email to `real-target@domain.com` on behalf of `someuser@clamra.com` .

::

    From: someuser@clamra.com
    To: real-target@domain.com
    Subject: Your Subject

