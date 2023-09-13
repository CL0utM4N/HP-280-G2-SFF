# Opencore EFI for HP 280 G2 SFF
Hackintosh Opencore EFI for HP 280 G2 SFF

Don't use this EFI for your PC, only use as a reference when making your one.

Note 1 - Specifications are subject to change and as such will be posted/updated with every release.

Note 2 - Release Opencore 0.9.4 will have a version with Big Sur support but will not be updated past 0.9.4 as I won't be able to test it. This version could support older versions of macOS but I haven't tested it.

Note 3 - You will need to use Opencore Legacy Patcher to get this working on anything past Big Sur. This is what I do.


![Screenshot 2023-09-13 at 2 13 49 pm](https://github.com/CL0utM4N/HP-280-G2-SFF/assets/69705346/63c8cb63-aaf3-478a-bd7a-675c4ac9247b)



# What doesn't work?

WiFi/Buetooth - Needs card, will probably get a natively supported one.

Integrated Graphics - iGPU support was pretty much impossible to get working due to this desktop using a proprietary mainboard. Tried every configuration I could find on the internet with it but couldn't get display working with GPU acceleration. To get around this I installed a dGPU.
