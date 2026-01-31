These are patched versions of package3 that support Tinfoil app on Firmwares 21+. Replace the package3 in sdmc://atmosphere/ folder with the respective compile for your version. Enjoy!

New AIO compatible for installation.
This should be obvious but since the patches are within package3, using fusee will bypass this and render useless. When setting up hekate_ipl.ini use fss0=atmosphere/package3.
Do not use Payload=bootloader/payloads/fusee.bin.
