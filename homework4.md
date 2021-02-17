# Homework 4
## Matthew Day

For this assignment I read the exerpt from "The Practice of Cloud System Administration". This exerpt goes into detail about the differences between virtual machines, containers and physical machines.

Virtual machines are a great way for users to not be constricted to the bounds of their physical machines. They are able to create isolated areas in their physical machines with operating systems of their choosing. A user may have multiple virtual machines on one device. The VMs are isolated from any other part of the physical machine, including other VMs, so other applications will not affect their performance. They are easy to create, move and destroy, making them appealing to only use one as much as a user needs to. Virtual Machines would be perfect for organizations that need to use multiple operating systems.

Containers are isolated like VMs, however they take up much less CPU, disk space and memory. They are only as big as the processes that are inside of them. A huge perk of using containers is that they have their own dependencies and won't interfere with other containers. This leads to no version conflicts.

One might want to use a physical machine over a virtual machine if they want to have predictable performance. If an organzation needs high dependable computing power they may want to choose a physical machine over a virtual machine.

Cloud platforms like AWS host a number of different services that are useful to developers, including virtual machines and containers. Some of these services are especially helpful for building programs that have a microservice architecture. AWS in particular has some good user friendly documentation that will walk developers through how to use these services. https://aws.amazon.com/microservices/ has a quick list of specific services that might be helpful for developers when building a microservice. A more in depth guide to some particular services that can be helpful for microservice development cant be found at https://d1.awsstatic.com/whitepapers/microservices-on-aws.pdf.

Some other perks of being cloud based include services being hosted remotely, which is less infrastructure to pay for and manage. The services are available from anywhere one has an internet connect, which will means teams can work from anywhere as long as they have a device. It is also commodified, so the client only pays for what they use and scale services based on demand.


