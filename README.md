# easyconfigs
Easyconfigs from Easybuild tutorial and self induced challenges

1) openmpi.eb, easyconfig file for openmpi/5.0.5-GCC-13.3.0, self induced challenge. Had to change include wrap_system_openssl = False option at OpenSSL-3.eb file.

2) python-graph-core.eb and python-graph-dot.eb to be able to use eb --dep-graph. Had to install pydot (pydot-1.4.2-GCCcore-11.2.0.eb) as a depencency