This project aims to be an interims fork from the original Reaver-WPS project which appears to have been abandoned.

Hopefully, the original project will become alive again and, if this happens, this project will be closed.

If any required information such as wiki pages or documentation is not found within this project, please refer to original one: http://code.google.com/p/reaver-wps/

**INSTALL NOTES:**

I still didn't have time to prepare and upload the binaries, but the version is ready to download and install.

Here you have the steps which you can just copy/paste (run as root!):

**NOTE:** If you are running ubuntu, make sure you have libsqlite3-dev installed: (apt-get install libsqlite3-dev)

```
# svn checkout http://reaver-wps-fork.googlecode.com/svn/trunk/ reaver-wps-fork-read-only
# cd reaver-wps-fork-read-only/src
# ./configure
# make distclean && ./configure #(you can skip this step if you never installed reaver before)
# make
# make install
```

If you have any doubts, or you want to contribute in the project with your own changes, please feel free to contact me.