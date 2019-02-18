# _downloads
This folder is where downloadable files bundled with the SasView release live!

The files must be linked from the in-program Sphinx-generated help documentation; eg:

 - /sasview/docs/sphinx-docs/source/user/tutorial.rst
 - /sasview/src/sas/sasgui/perspectives/corfunc/media/fdr-pdfs.rst

Files in here may, or may not, be the same as those in 
https://github.com/SasView/sasview.github.io/tree/master/downloads depending 
on how recently files were updated relative to a SasView release.

This folder is populated when build_sphinx.py is called (eg, by python setup.py docs).
DO NOT copy files here directly!
