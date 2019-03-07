# gentoo_settings
All of Gentoo Setup including make.conf, tips and tricks after installation

## To make Portage compile silent without messy output use

'''
EMERGE_DEFAULT_OPTS="${EMERGE_DEFAULT_OPTS} --quiet-build=y"
'''

## If the system setup as KDE Plasma desktop, not META, some problem might arise such as

*Sound not working can be solved by* 

'''
emerge kde-apps/meta-multimedia
'''



