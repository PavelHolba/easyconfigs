# easyconfigs
Easyconfigs from Easybuild tutorial and self induced challenges

1. openmpi.eb, easyconfig file for openmpi/5.0.5-GCC-13.3.0, self induced challenge. Had to change include wrap_system_openssl = False option at OpenSSL-3.eb file.

2. python-graph-core.eb and python-graph-dot.eb to be able to use eb --dep-graph. Had to install pydot (pydot-1.4.2-GCCcore-11.2.0.eb) as a depencency

3. Lukas's challenge
   - [x] create easyconfig for MyMan (use template)
   - [x] EASYBLOCK ... choose easyblock
   - [x] NAME ... defined name of the software
   - [x] VERSION ... defined versions of the software
   - [x] VERSIONSUFFIX ... add your name
   - [x] HOMEPAGE ... homepage url
   - [x] DESCRIPTION ... basic software information
   - [x] TOOLCHAIN ... choose toolchain
   - [x] SOURCE_URLS ... source urls
   - [x] SOURCES ... package name definition
   - [x] DEPENDENCY ... Tcl/8.6.6
     - not needed
   - [x] SANITY_CHECK_PATH ... you must check exists binary file
   - [x] MODULECLASS ... choose class
   - [x] rename teplate to MyMan-2009-10-30.eb
   - [x] install MyMan from easyconfig
   - [x] load module and run myman
