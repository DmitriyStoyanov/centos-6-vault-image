# centos-6-vault-image

Because of CentOS 6 End of life mirrorlist is not accessible from centos image, I've created new image based on `centos:6.10`
with changed baseurl to http://vault.centos.org, to fix this issue.

Thank for such fix information received from [how-to-fix-yum-after-centos-6-went-eol](https://www.getpagespeed.com/server-setup/how-to-fix-yum-after-centos-6-went-eol)

DockerHub Image should be available here: `scorpio2002/centos-6-vault-image:6.10`

So you can change your image from `centos:6` to this one and use it.
