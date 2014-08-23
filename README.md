#Intervarsity Christian Fellowship Rochester Institute of Technology

This page is hosted on github pages.

The entire page is divided into 5 different parts. The source code is located in ```_include/*```. Being separated helps understand the site structure better. Please refer to ```_layout/default.html``` for general layout, and then index.html.

* Banner
* Mission statement
* Plug
* Large group
* Small groups

### Banner - ```_include/banner.html```
The banner holds the graphics on top. The background is one image, while the edge diagonal lines is another image overlay over.
### Mission statement -```_include/mission.html```
This is the Mission statement.
### Plug - ```_include/plug.html```
This is useful for making certain information distinctive, such as Baseliea, expedition, or general "LOOK AT ME".
### Large group - ```_include/largegroup.html```
This holds a very large picture named ```images/largegroup.jpg```. With a short description of what is large group, and some event details.
### Small groups - ```_data/smallgroup.yml```
This is a YAML file, not an HTML file. The jekyll template will look into this specific file and generate the list of small groups. Archiving previous small groups list is really easy, simply rename it other than ```smallgroup.yml```, such as ```old-2013-smallgroup.yml```.

This was developed using Jekyll. 
