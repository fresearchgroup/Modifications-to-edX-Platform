#Modifications-to-edX-Platform

For edX installation, please refer to our Installation Documentation at [IITB-FRG-Site](http://www.it.iitb.ac.in/frg/brainstorming/sites/default/files/P4_rajarshi14_Week_04_Report_01_2014_06_04_edX_Installation_Guide.zip)
##Remote Course Management System

###Up and Running with RCMS

Your edX Installation folder should have this structure.
* cms
  * envs
    * common.py
  * urls.py
* common
  * djangoapps
    * rcms
      * dump
      * logs
        * rcms.log
      * update
      * admin.py
      * \_\_init\_\_.py
      * models.py
      * rcms.cfg
      * tasks.py
      * views.py
 * static
 * templates

Change the **dump\_path**, **update\_path**, **log\_path** in **rcms.cfg** to **rcms** folder in your edX Installation directory.
See the **rcms.cfg** file for more information.
