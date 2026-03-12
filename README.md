# command-collections
A collection of interesting commands that aren't large enough to warrant becoming a script

grep -q hypervisor /proc/cpuinfo  && echo "VM" || echo "Bare Metal" : A command to find out whether the linux server you are on is running on a VM or Bare Metal.
