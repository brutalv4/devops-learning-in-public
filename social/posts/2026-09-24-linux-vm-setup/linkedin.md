# Linux Virtual Machine Setup

Platform: LinkedIn
Status: Published
Published: 2026-09-24
Post URL: https://www.linkedin.com/posts/volodymyr-bredikhin_devops-devopsbootcamp-linux-share-7508803342974910464-bhCJ/

## Post

Today’s lesson covered setting up a virtual machine for more Linux practice.

The tutorial uses VirtualBox and a newer Ubuntu desktop image. I took a different path: VMware Fusion with an existing Ubuntu 24.04 LTS virtual machine.

The underlying concept stays the same:

- a host machine provides the hardware;
- a hypervisor manages the virtual machine;
- the guest OS runs in an isolated environment;
- resources are shared between the host and the guest.

This setup was much easier than my previous attempt.

The last time I created an Ubuntu VM on an ARM-based machine, I had to use a server image without a graphical interface, manually install desktop packages, and disable a service that slowed startup.

This time, I really appreciated how much simpler the process has become: I could use a prepared desktop ISO and get started without all the usual dancing around configuration issues.

It was a useful reminder that a tutorial usually demonstrates one implementation, not the only valid implementation.

Different tools and different setup paths can lead to the same engineering outcome.

#DevOps #DevOpsBootcamp #Linux #Virtualization #LearningInPublic #DevOpsBootcampDay3
