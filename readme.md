# centos-fat #

`centos-fat` is a fat image for docker which includes many essential 
tools for using a centos image.

The goal of this project is not to have a docker image for your project
but to experiemnt with centos without having the overhead to install a
whole vm. This is specially great because you can quickly reset your
experiemnt and do not have to worry about side effects too much.

While it is safe to do a lot with this image then on your personal computer,
please keep in mind that docker does not offer full isolation. Be careful
with running untrusted code.

Also this image does not have all things a VM or bare matel server has and
might act differently. If one feature is missing, please create an issue
on github so we can discuss how to implement this to the docker file. 

The docker file has been released under the MIT license and comes without
any warranties.

