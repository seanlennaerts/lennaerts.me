---
layout: post
title: Resetting your MacBook Air
permalink: /ana-cris/
---

Hope this helps. Text or call if you have any questions! :muscle:

1. Back up all the things you want to keep on you MacBook Air. Something I like to do is take screenshots of the dock and the Applications folder (and back those up too).

2. Starting with your laptop turned off. Press the power button and then immediately hold down <kbd>⌘</kbd> + <kbd>R</kbd> until the apple logo appears. This will start your laptop in Recovery Mode. When it finishes loading you should see this:

    ![Recovery](/assets/{{ page.title }}/recovery.png)

3. :warning: This is the point of no return. We are about to erase your harddrive. Select Disk Utlity and then click Continue. You should see something like this:

    ![Disk Utility](/assets/{{ page.title }}/disk-utility.png)

4. Select the top most drive in the sidebar. In the picture above this is APPLE SSD (not the one indented below it that says Macintosh HD).

5. Click the Erase button at the top.

6. Now complete the following fields:
    - Name: "Macintosh HD"
    - Format: Choose Mac OS Extended (Journaled)
    - Scheme: Should be GUID Partition Map  

7. Click Erase to begin erasing your disk.

8. When that finishes close Disk Utility. (Hey! If erasing doesn't work and it complains about mounting [click here](/ana-cris/resetting-your-macbook-air-again).

9. Time to install macOS Sierra again. I know you just did this like a month ago so you probably know what to do. Select Reinstall macOS and then click Continue. Follow the instructions are you're good to go!