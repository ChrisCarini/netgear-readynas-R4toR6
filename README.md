# netgear-readynas-R4toR6

This repo is intended to store two `.bin` files for upgrading Netgear ReadyNAS from version 4.* to 6.* - you can find more details on [my blog post covering the upgrade steps](https://blog.chriscarini.com/2020/11/upgrading-readynas-ultra-2-from.html).

These files were originally found on [the Netgear Community forum](https://community.netgear.com/t5/ReadyNAS-Storage-Apps-Current/ReadyNAS-OS-6-9-3-Run-on-existing-x86-4-2-notsupported/m-p/905274) - I'm saving them here for myself for posterity.

I have also created md5 checksums for the two `.bin` files, included as `.bin.md5sum` files; you can verify using the below command:
```
$ md5sum -c *.bin.md5sum
R4toR6_6.9.5.bin: OK
R4toR6_Prep_Addon.bin: OK
```

I, nor Netgear, support these files - following the steps in the above blog post are unsupported by Netgear, and myself. I take no responsibility for any data loss caused by using the files in this repo, or steps on the blog post. Use at your own risk.
