# wt3020-backport
A backport patch of support for the Nexx WT3020 (only those with 8MB of flash) to OpenWRT 14.07 Barrier Breaker

Based on code from Openwrt changeset 42983 
https://dev.openwrt.org/changeset/42983
Thanks Roger Pueyo!

And also code from Justin Liu
https://github.com/rssnsj/openwrt-xiaomi-mini

##To use
1. Download .patch file
2. Move into the OpenWRT buildroot
eg. `cd /home/openwrt`
3. Import the .patch file
`quilt import 0001-wt3020_backport.patch`
4. Apply the patch
`quilt push 0001-wt3020_backport.patch`
5. Build OpenWRT as normal