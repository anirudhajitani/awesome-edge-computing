# Awesome edge computing

# Simulators
- [iFogSim](https://github.com/Cloudslab/iFogSim): The iFogSim Toolkit for Modeling 
and Simulation of Resource Management Techniques in Internet of Things, Edge and 
Fog Computing Environments.

- [EdgeCloudSim](https://github.com/CagataySonmez/EdgeCloudSim): EdgeCloudSim: An 
Environment for Performance Evaluation of Edge Computing Systems.

- [pFogSim](https://github.com/jihall77/pFogSim): pFogSim (/p/-fôg-/sɪm/) is a 
play off iFogSim; A simulator made to handle large-scale FOG networks with the 
HAFA Puddle Strategy to help evaluate the potential advantages/disadvantages 
within user-customizable scenarios.

- [Veins LTE](http://veins-lte.car2x.org/): Veins LTE is a simulator for 
heterogeneous vehicular networks. It provides fine-grained simulation of vehicular
networks based on IEEE 802.11p and TE.

- [CloudSim](https://github.com/Cloudslab/cloudsim): CloudSim goal is to provide 
a generalized and extensible simulation framework that enables modeling, simulation,
and experimentation of emerging Cloud computing infrastructures and application 
services, allowing its users to focus on specific system design issues that they 
want to investigate, without getting concerned about the low level details related 
to Cloud-based infrastructures and services.

- [CloudSimSDN](https://github.com/Cloudslab/cloudsimsdn): An SDN extension of
CloudSim project to simulate SDN features in the context of a cloud data center.
CloudSimSDN supports calculating power consumption by both hosts and switches.
For instance, network-aware VM placement policies can be evaluated using CloudSimSDN.

- [lightMANO](https://github.com/lightmano/lightmano-core): A lightweight distributed
service orchestrator designed for resource constrained multi-access edge computing
environments.

- [FogTorchPI](https://github.com/di-unipi-socc/FogTorchPI): FogTorchΠ is an open
source prototype, developed in Java, based on a model for Fog computing infrastructures
and applications. 1), It takes into account non-functional parameters within the model
(i.e., hardware, software, latency and bandwidth) to determine, compare and contrast
different eligible deployments of a given application over a Fog infrastructure.
2), In the case of hardware capabilities, it considers CPU cores, RAM and storage 
available at a given node or required by a given software component. 3), Software 
capabilities are represented by a list of software names (operating system, 
programming languages, frameworks etc). 4), It considers latency, and both download
and upload bandwidths as QoS attributes. Latency is measured in milliseconds (ms),
while bandwidth is given in Megabits per second (Mbps).
**Note**: Outputs of __FogTorchPI__ can be the input of __iFogSim__.

# Frameworks

## Engine
- [Apache Edgent(incubating)](https://edgent.incubator.apache.org/): Apache Edgent
is a programming model and micro-kernel style runtime that can be embedded in 
gateways and small footprint edge devices enabling local, real-time, analytics 
on the continuous streams of data coming from equipment, vehicles, systems,
appliances, devices and sensors of all kinds (for example, Raspberry Pis or smart 
phones). Working in conjunction with centralized analytic systems, Apache Edgent 
provides efficient and timely analytics across the whole IoT ecosystem: from the
center to the edge.

- [OpenStack++](http://elijah.cs.cmu.edu/development.html): is a framework developed 
by Carnegie Mellon University Pittsburgh for providing VM-based cloudlet platform
on regular x86 computers for mobile application offloading. A set of new mobile 
computing applications that build upon OpenStack++ and leverage its support for 
cloudlets is also supported.

- [WSO2-IoT Server](https://wso2.com/iot): An extension of the popular open-source
enterprise service-oriented integration platform WSO2 server that consists of 
certain IoT-related mechanisms, such as connecting a broad range of common IoT
devices with the cloud using standard protocols such as MQTT and XMPP. Further,
WSO2–IoT server includes the embedded Siddhi 3.0 component that allows the system 
to deploy real-time streaming processes in embedded devices. In other words,
WSO2–IoT server provides the FEC computing capability to outer-edge devices.


## Networks
- [EdgeNet](https://github.com/EdgeNet-Project): edgeNet is a distributed edge
cloud, in the family of PlanetLab, GENI, Canada’s SAVI infrastructure, Japan’s 
JGN-X, Germany’s G-Lab, and PlanetLab Europe. It is a modern distributed edge 
cloud, incorporating advances in Cloud technologies over the past few years.

- [MinNet](http://mininet.org/): Mininet creates a realistic virtual network, 
running real kernel, switch and application code, on a single machine (VM, cloud
or native), in seconds, with a single command:`sudo mn`. Mininet is also a great
way to develop, share, and experiment with OpenFlow and Software-Defined Networking 
systems.

- [Mosquitto](http://mosquitto.org/): Eclipse Mosquitto is an open source (EPL/EDL
licensed) message broker that implements the MQTT protocol versions 5.0, 3.1.1 and
3.1. Mosquitto is lightweight and is suitable for use on all devices from low power
single board computers to full servers. 
The MQTT protocol provides a lightweight method of carrying out messaging using
a publish/subscribe model. This makes it suitable for Internet of Things messaging 
such as with low power sensors or mobile devices such as phones, embedded computers 
or microcontrollers.
The Mosquitto project also provides a C library for implementing MQTT clients, 
and the very popular `mosquitto_pub` and `mosquitto_sub` command line MQTT clients.

- [OMNeT++](https://github.com/omnetpp/omnetpp): OMNeT++ is a public-source, 
component-based, modular and open-architecture simulation environment with strong
GUI support and an embeddable simulation kernel. Its primary application area is
the simulation of communication networks, but it has been successfully used in 
other areas like the simulation of IT systems, queueing networks, hardware 
architectures and business processes as well.

- [POX](https://github.com/noxrepo/pox): POX is a networking software platform
written in Python. POX started life as an OpenFlow controller, but can now also 
function as an OpenFlow switch, and can be useful for writing networking software
in general. An useful link of how to simulate a SDN can check the link:
http://www.brianlinkletter.com/using-the-pox-sdn-controller/

- [VerneMQ](https://vernemq.com/): VerneMQ is a high-performance, distributed 
MQTT message broker. It scales horizontally and vertically on commodity hardware
to support a high number of concurrent publishers and consumers while maintaining 
low latency and fault tolerance. VerneMQ is the reliable message hub for your IoT 
platform or smart products.


# Test (data, benchmark)
- [CloudSuite](https://www.cloudsuite.ch/): CloudSuite is a benchmark suite for 
cloud services. The third release consists of eight applications that have been 
selected based on their popularity in today’s datacenters. The benchmarks are 
based on real-world software stacks and represent real-world setups.

- [DeFog](https://github.com/qub-blesson/DeFog): DeFog, a first Fog benchmarking 
suite to: (i) alleviate the burden of Fog benchmarking by using a standard 
methodology, and (ii) facilitate the understanding of the target platform by 
collecting a catalogue of relevant metrics for a set of benchmarks.


# Tools
- [netem](https://wiki.linuxfoundation.org/networking/netem) : netem provides 
Network Emulation functionality for testing protocols by emulating the properties
of wide area networks. The current version emulates variable delay, loss, 
duplication and re-ordering.

