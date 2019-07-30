running rados gw on compute nodes
doing encryption/decryption on the compute nodes then
using s3fs to serve posix interface (running in a container)
definitely slower than cephfs
using singularity to bind mount and isolate ?
not in use in production yet - no security review yet

