## ioctl.py
Quick script to decode I/O control values for Windows drivers:
+ Determine Device Type,
+ Determine Access Check,
+ Determine Function Code,
+ Determine I/O Method, and
+ Output `CTL_CODE` macro template.

## Usage
`Usage: example.py <ioctl code>`

`Usage: example.py 0x222003`

## Notes
Harcoded dictionary values come from: `ntddk.h`, `devioctl.h`, and `irclass_ioctl.h`. 

Inspired by the OSR online tool: https://www.osronline.com/article.cfm%5earticle=229.htm

Created with help from: https://social.technet.microsoft.com/wiki/contents/articles/24653.decoding-io-control-codes-ioctl-fsctl-and-deviceiocodes-with-table-of-known-values.aspx

***Could have bugs, only tested 3 IOCTLs.***
