# awesome-ubuntu-core

> Build secure IoT devices with [Ubuntu Core](https://ubuntu.com/core).
>
> Everything you love about Ubuntu, locked down for security. Helping you make safer things – because we’re all connected.

## Officail Prebuilt Boards and Images

- [Ubuntu Core 18 (stable)](http://cdimage.ubuntu.com/ubuntu-core/18/stable/)

## Packaging

- [snapcore/snapcraft](https://github.com/snapcore/snapcraft) - Package, distribute, and update any app for Linux and IoT.

## Testing

- [snapcore/spread](https://github.com/snapcore/spread) - Convenient full-system test (task) distribution.
- [snapcore/spread-images](https://github.com/snapcore/spread-images) - This project provides a set of tasks and scripts used to create and update images used by spread.
- [snapcore/spread-cron](https://github.com/snapcore/spread-cron) - spread-cron triggers spread tasks in response to events.

## Development Environment

### 5G tracer

- [oai-tracer](https://snapcraft.io/oai-tracer) - OpenAirInterface RAN tracer and visualizer.

### Build server

- [fabrica](https://snapcraft.io/fabrica) - Build snaps by simply pointing a web form to a git tree.

### Containerization

- [distrobuilder](https://snapcraft.io/distrobuilder) - Image builder for LXC and LXD.
- [kubectl](https://snapcraft.io/kubectl) - Command line client for controlling a Kubernetes cluster.

## Databases

- [Beekeeper Studio](https://snapcraft.io/beekeeper-studio) - An open source SQL editor and database management app.
- [DataGrip](https://snapcraft.io/datagrip) - IntelliJ-based IDE for databases and SQL.

### Drivers

- [hw-probe](https://snapcraft.io/hw-probe) - Check operability of computer hardware and find drivers.

### GraphQL

Snaps for development of GraphQL-based communication. For other tools refer to e.g. [awesome-graphql#tools](https://github.com/chentsulin/awesome-graphql#tools).

- [Insomnia](https://snapcraft.io/insomnia) - HTTP and GraphQL Client.

### gRPC

Snaps for development of gRPC-based communication. For other tools refer to e.g. [awesome-grpc#tools](https://github.com/grpc-ecosystem/awesome-grpc#tools).

### JSON

- [fx](https://snapcraft.io/fx) - Command-line tool and terminal JSON viewer.

### Key value stores

- [RedisDesktopManager](https://snapcraft.io/redis-desktop-manager) - Cross-platform GUI management tool for Redis.

### Machine learning

Snaps for development of machine learning models. For other tools refer to e.g. [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning) or [awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning).

- [Netron](https://snapcraft.io/netron) - Visualizer for neural network, deep learning and machine learning models.

### MQTT clients

Snaps for development of MQTT-based communication. For other tools refer to e.g. [awesome-mqtt#tools](https://github.com/hobbyquaker/awesome-mqtt#tools).

- [mqtt-explorer](https://snapcraft.io/mqtt-explorer) - MQTT Client.
- [mqttx](https://snapcraft.io/mqttx) - MQTT 5.0 Client.

### ROS2

- [Micro XRCE-DDS Agent](https://snapcraft.io/micro-xrce-dds-agent) - Bridge between Micro XRCE-DDS clients and DDS.

### Monitoring

- [influxdb](https://snapcraft.io/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
- [grafana](https://snapcraft.io/grafana) - Metrics dashboard and graph editor.
- [prometheus](https://snapcraft.io/prometheus) - Monitoring system and time series database.

### Virtualization

- [Multipass](https://multipass.run/) - Recommended method to create Ubuntu VMs on Ubuntu, Mac or Windows workstations.

### Performance optimization

- [cpustat](https://snapcraft.io/cpustat) - periodic cpu utilization statistics.
- [fast](https://snapcraft.io/fast) - Test your internet download speed from terminal.
- [stress-ng](https://snapcraft.io/stress-ng) - A tool to load, stress test and benchmark a computer system.

### Prototyping

- [arduino](https://snapcraft.io/arduino) - Write code and upload it to your Arduino-compatible board.
- [node-red](https://snapcraft.io/node-red) - Low-code programming for event-driven applications.
- [LibrePBC](https://snapcraft.io/librepcb) - EDA software to develop printed circuit boards.

## Runtime

- [snapcore/snapd](https://github.com/snapcore/snapd) - The snapd and snap tools enable systems to work with .snap files.

## Security hardening

- [nmap](https://snapcraft.io/nmap) - Utility for network discovery and security auditing.
- [ssh-audit](https://snapcraft.io/ssh-audit) - SSH server and client security configuration auditor.

### Base Snaps

- [snapcore/core18](https://github.com/snapcore/core18) - This is a base snap for snapd that is based on Ubuntu 18.04.
- [snapcore/core20](https://github.com/snapcore/core20) - This is a base snap for snapd that is based on Ubuntu 20.04.
- [snapcore/bare-base](https://github.com/snapcore/bare-base) - An empty base snap that contains nothing except the directories required as mount points.

### Gadget snaps (board support)

- [snapcore/pi-gadget](https://github.com/snapcore/pi-gadget) - Universal pi (pi2,pi3,pi4,cm3) gadget snap for core18.
- [snapcore/pi3-gadget](https://github.com/snapcore/pi3-gadget) - The gadget snap for the Raspberry Pi 3 development board.
- [snapcore/pc-amd64-gadget](https://github.com/snapcore/pc-amd64-gadget) - The gadget snap for Personal Computers using 64bit Intel or AMD processors.

### Reference models

- [snapcore/models](https://github.com/snapcore/models) -  Reference Models for customized, device specific Ubuntu Core image builds.

### Util libraries

- [snapcore/snapd-glib](https://github.com/snapcore/snapd-glib) - Library to allow GLib based applications access to snapd, the daemon that controls Snaps.
- [snapcore/snapcraft-preloads](https://github.com/snapcore/snapcraft-preloads) - Individual libraries that can be preloaded in snaps to ensure behavior is consistent with confinement rules.

## [Snaps](https://snapcraft.io/store) (for production)

- Application frameworks
  - [Kura](https://snapcraft.io/kura) - Eclipse Kura™, An OSGi-based Application Framework for M2M Service Gateways.
- Bluetooth
  - [bluez](https://snapcraft.io/bluez) - Official Linux Bluetooth protocol stack.
- Cloud integration
  - [AWS IoT Greengrass](https://snapcraft.io/aws-iot-greengrass) - Bring local compute, messaging, data caching, sync and ML inference capabilities to edge devices.
- Containerization
  - [docker](https://snapcraft.io/docker) - Docker container runtime.
  - [kata-containers](https://snapcraft.io/kata-containers) - Lightweight virtual machines that seamlessly plug into the containers ecosystem.
  - [kubernetes-worker](https://snapcraft.io/kubernetes-worker) - A complete Kubernetes worker.
  - [lxd](https://snapcraft.io/lxd) - System container manager and API.
- Deployment
  - [Snap Store Proxy](https://snapcraft.io/snap-store-proxy) - A smart caching proxy for the Snap Store.
- Firewall
  - [ufw](https://snapcraft.io/ufw) - Uncomplicated Firewall.
- Key value stores
  - [etcd](https://snapcraft.io/etcd) - Resilient key-value store by CoreOS.
- Private Cloud
  - [MAAS (Metal as a Service)](https://snapcraft.io/maas) - Very fast server provisioning for your data centre (edge server as a cloud).
- UI toolkits
  - [mir-kiosk](https://snapcraft.io/mir-kiosk) - A minimal Mir based shell for kiosk type applications.
  - [Electron](https://www.electronjs.org/) - Build cross-platform desktop apps with JavaScript, HTML, and CSS (needs to be integrated with mir-kiosk via XWayland and Snapd Wayland interface). Use any JavaScript/TypeScript frontend framework you like.
  - [Qt](https://www.qt.io/ubuntu-built-with-qt) - Create beautiful user interfaces (on Ubuntu Core).
- Wayland compositors
  - [SWAY](https://snapcraft.io/sway) - 3-compatible Wayland compositor.

## Common snap dependencies

- [i3-wm](https://packages.ubuntu.com/search?keywords=i3-wm) - Improved dynamic tiling window manager.
- [libegl1-mesa](https://packages.ubuntu.com/search?keywords=libegl1-mesa) - Free implementation of the EGL API -- runtime.
- [libgl1-mesa-glx](https://packages.ubuntu.com/de/libgl1-mesa-glx) - Free implementation of the OpenGL API -- GLX runtime.
- [xwayland](https://wayland.freedesktop.org/xserver.html) - X Clients under Wayland.

## Documentation

- Ubuntu Core
  - [Ubuntu Core vs. Ubuntu Server comparison table](https://core.docs.ubuntu.com/en/#advantages-for-iot) - More lightweight, faster and more secure by design.
  - Booting
    - [secboot](https://github.com/snapcore/secboot) - Lightweight secure boot mechanism.
  - [NetworkManager](https://docs.ubuntu.com/core/en/stacks/network/network-manager/docs/) - System network service that manages your network devices and connections and attempts to keep network connectivity active when available.
    - [networkd](https://www.freedesktop.org/software/systemd/man/systemd-networkd.service.html) - System service that manages networks.
    - [netplan](https://netplan.io/) - YAML network configuration abstraction for various backends (NetworkManager, networkd).
- [Snapcraft](https://snapcraft.io/docs)
  - Tools
    - [snapctl](https://snapcraft.io/docs/using-snapctl) - provide both specific environmental feedback and limited control from within the context of a snap’s execution environment to snapd (typically run from a script within a snap).
    - [snapd REST API](https://snapcraft.io/docs/snapd-api) - Access to snapd’s state and many of its key functions.
  - [Snapcraft.yaml reference](https://snapcraft.io/docs/snapcraft-yaml-reference) - Single page reference for the [snapcraft format](https://snapcraft.io/docs/snapcraft-format).
  - [hooks](https://snapcraft.io/docs/supported-snap-hooks) - A hook is an executable file that runs within a snap’s confined environment when a certain action occurs.
  - [environment variables](https://snapcraft.io/docs/environment-variables) - consume, set, and pass-through specific environment variables to support building and running snaps.
  - Interfaces (not for Ubuntu Core only, for Ubuntu Desktop as well)
    - [account-control](https://snapcraft.io/docs/account-control-interface) (core) - add/remove user accounts or change passwords
    - [accounts-service](https://snapcraft.io/docs/accounts-service-interface) - allows communication with the accounts service
    - [adb-support](https://snapcraft.io/docs/adb-support-interface) - allows operating as Android Debug Bridge service
    - [alsa](https://snapcraft.io/docs/alsa-interface) (core) - play or record sound
    - [appstream-metadata](https://snapcraft.io/docs/appstream-metadata-interface) - allows access to AppStream metadata
    - [audio-playback](https://snapcraft.io/docs/audio-playback-interface) - allows audio playback via supporting services
    - [audio-record](https://snapcraft.io/docs/audio-record-interface) - allows audio recording via supported services
    - [autopilot-introspection](https://snapcraft.io/docs/autopilot-introspection-interface) (core) - be controlled by Autopilot software
    - [avahi-control](https://snapcraft.io/docs/avahi-control-interface) (core) - advertise services over the local network
    - [avahi-observe](https://snapcraft.io/docs/avahi-observe-interface) (core) - detect services and devices over the local network
    - [block-devices](https://snapcraft.io/docs/block-devices-interface) - access to disk block devices
    - [bluetooth-control](https://snapcraft.io/docs/bluetooth-control-interface) (core) - access Bluetooth hardware directly
    - [bluez](https://snapcraft.io/docs/bluez-interface) (core) - use Bluetooth devices
    - [bool-file](https://snapcraft.io/docs/bool-file-interface) - allows access to specific file with bool semantics
    - [broadcom-asic-control](https://snapcraft.io/docs/broadcom-asic-control-interface) (core) - control Broadcom network switches
    - [browser-support](https://snapcraft.io/docs/browser-support-interface) (core) - use functions essential for Web browsers
    - [calendar-services](https://snapcraft.io/docs/calendar-service-interface) - allows communication with Evolution Data Server calendar 	no
    - [camera](https://snapcraft.io/docs/camera-interface) (core) - use your camera or webcam
    - [can-bus](https://snapcraft.io/docs/can-bus-interface) - allows access to the CAN bus
    - [cifs-mount](https://snapcraft.io/docs/the-cifs-mount-interface) - allows the mounting and unmounting of CIFS filesystems
    - [classic-support](https://snapcraft.io/docs/classic-support-interface) (core) - enable resource access to classic snap
    - [contacts-service](https://snapcraft.io/docs/the-contacts-service-interface) - allows communication with the Evolution Data Server address book
    - [content](https://snapcraft.io/docs/content-interface) (core) - access resources across snaps 	
    - ([core-support](https://snapcraft.io/docs/core-support-interface) (core) - deprecated since snap 2.34)
    - [cpu-control](https://snapcraft.io/docs/cpu-control-interface) - set certain CPU values
    - [cups-control](https://snapcraft.io/docs/cups-control-interface) (core) - print documents
    - [daemon-notify](https://snapcraft.io/docs/daemon-notify-interface) - allows sending daemon status changes to service manager
    - [dbus](https://snapcraft.io/docs/dbus-interface) (core) - allow snaps to communicate over D-Bus
    - [dcdbas-control](https://snapcraft.io/docs/dcdbas-control-interface) (core) - shut down or restart Dell devices
    - [desktop](https://snapcraft.io/docs/desktop-interface) - provides access to common desktop elements
    - [desktop-legacy](https://snapcraft.io/docs/desktop-legacy-interface) - enables the use of legacy desktop methods (including input method and accessibility services)
    - [device-buttons](https://snapcraft.io/docs/device-buttons-interface) - use any device-buttons
    - [display-control](https://snapcraft.io/docs/display-control-interface) - allows configuring display parameters
    - [docker](https://snapcraft.io/docs/docker-interface) (core) - start, stop, or manage Docker containers
    - [docker-support](https://snapcraft.io/docs/docker-support-interface) (core) - allows operating as the Docker daemon
    - [dummy](https://snapcraft.io/docs/dummy-interface) - allows testing without additional permissions
    - [dvb](https://snapcraft.io/docs/dvb-interface) - allows access to all DVB devices and APIs
    - [firewall-control](https://snapcraft.io/docs/firewall-control-interface) (core) - configure a network firewall
    - [framebuffer](https://snapcraft.io/docs/framebuffer-interface) (core) - access to universal framebuffer devices
    - [fuse-support](https://snapcraft.io/docs/fuse-support-interface) (core) - enables access to the FUSE filesystems
    - [fwupd](https://snapcraft.io/docs/fwupd-interface) (core) - allows operating as the fwupd service
    - [gpg-keys](https://snapcraft.io/docs/gpg-keys-interface) - read GPG user configuration and keys
    - [gpg-public-keys](https://snapcraft.io/docs/gpg-public-keys-interface) - read GPG non-sensitive configuration and public keys
    - [gpio](https://snapcraft.io/docs/gpio-interface) (core) - access specific GPIO pins
    - [gpio-control](https://snapcraft.io/docs/gpio-control-interface) - allows to export/unexport and control all GPIOs
    - [gpio-memory-control](https://snapcraft.io/docs/gpio-memory-control-interface) - allows write access to all GPIO memory
    - [greengrass-support](https://snapcraft.io/docs/greengrass-support-interface) (core) - allows operating as the Greengrass service
    - [gsettings](https://snapcraft.io/docs/gsettings-interface) (core) - provides access to any GSettings item for current user
    - [hardware-observe](https://snapcraft.io/docs/hardware-observe-interface) (core) - access hardware information
    - [hardware-random-control](https://snapcraft.io/docs/hardware-random-control-interface) (core) - provide entropy to hardware random number generator
    - [hardware-random-observe](https://snapcraft.io/docs/hardware-random-observe-interface) (core) - use hardware-generated random numbers
    - [hidraw](https://snapcraft.io/docs/hidraw-interface) (core) - access hidraw devices
    - [home](https://snapcraft.io/docs/home-interface) (core) - access non-hidden files in the home directory
    - [hostname-control](https://snapcraft.io/docs/hostname-control-interface) - allows configuring the system hostname
    - [i2c](https://snapcraft.io/docs/i2c-interface) (core) - access i²c devices
    - [iio](https://snapcraft.io/docs/iio-interface) (core) - access IIO devices
    - [intel-mei](https://snapcraft.io/docs/intel-mei-interface) - access to the Intel MEI management interface
    - [io-ports-control](https://snapcraft.io/docs/io-ports-control-interface) (core) - allows access to all I/O ports
    - [jack1](https://snapcraft.io/docs/the-jack1-interface) - allows interaction with the JACK audio connection server
    - [joystick](https://snapcraft.io/docs/joystick-interface) (core) - use any connected joystick
    - [juju-client-observe](https://snapcraft.io/docs/juju-client-observe-interface) - read the Juju client configuration
    - [kernel-module-control](https://snapcraft.io/docs/kernel-module-control-interface) (core) - insert, remove and query kernel modules
    - [kernel-module-observe](https://snapcraft.io/docs/kernel-module-observe-interface) - query kernel modules
    - [kubernetes-support](https://snapcraft.io/docs/kubernetes-support-interface) (core) - use functions essential for Kubernetes
    - [kvm](https://snapcraft.io/docs/kvm-interface) (core) - allows access to the kvm device
    - [libvirt](https://snapcraft.io/docs/libvirt-interface) (core) - provides access to the libvirt service
    - [locale-control](https://snapcraft.io/docs/locale-control-interface) (core) - change system language and region settings
    - [location-control](https://snapcraft.io/docs/location-control-interface) (core) - allows operating as the location service
    - [location-observe](https://snapcraft.io/docs/location-observe-interface) (core) - access your location
    - [login-session-control](https://snapcraft.io/docs/the-login-session-control-interface) - allows setup of login sessions and grants privileged access to user sessions
    - [login-session-observe](https://snapcraft.io/docs/login-session-interface) - allows reading login and session information
    - [log-observe](https://snapcraft.io/docs/log-observe-interface) (core) - read system logs
    - [lxd](https://snapcraft.io/docs/lxd-interface) (core) - provides access to the LXD socket
    - [lxd-support](https://snapcraft.io/docs/lxd-support-interface) (core) - allows operating as the LXD service
    - [maliit](https://snapcraft.io/docs/maliit-interface) (core) - use an on-screen keyboard
    - [media-hub](https://snapcraft.io/docs/media-hub-interface) (core) - access snaps providing the media-hub interface
    - [mir](https://snapcraft.io/docs/mir-interface) (mir) - enables access to the Mir display service
    - [modem-manager](https://snapcraft.io/docs/modem-manager-interface) (core) - use and configure modems
    - [mount-observe](https://snapcraft.io/docs/mount-observe-interface) (core) - read mount table and quota information
    - [mpris](https://snapcraft.io/docs/mpris-interface) (core) - control music and video players
    - [multipass-support](https://snapcraft.io/docs/the-multipass-support-interface) - multipass-support allows operating as the Multipass service
    - [netlink-audit](https://snapcraft.io/docs/search?q=netlink-audit) (core) - allows access to kernel audit system through Netlink
    - [netlink-connector](https://snapcraft.io/docs/netlink-connector-interface) (core) - communicate through the kernel Netlink connector
    - [network](https://snapcraft.io/docs/network-interface) (core) - enables network access
    - [network-bind](https://snapcraft.io/docs/network-bind-interface) (core) - operate as a network service
    - [network-control](https://snapcraft.io/docs/network-control-interface) (core) - change low-level network settings
    - [network-manager](https://snapcraft.io/docs/network-manager-interface) (core) - configure and observe networking via NetworkManager
    - [network-manager-observe](https://snapcraft.io/docs/the-network-manager-observe-interface) (core) - allows observing NetworkManager settings
    - [network-observe](https://snapcraft.io/docs/network-observe-interface) (core) - query network status information
    - [network-setup-control](https://snapcraft.io/docs/network-setup-control-interface) (core) - change network settings via Netplan
    - [network-setup-observe](https://snapcraft.io/docs/network-setup-observe-interface) (core) - read network settings
    - [network-status](https://snapcraft.io/docs/network-status-interface) (core) - access the NetworkingStatus service
    - [ofono](https://snapcraft.io/docs/ofono-interface) (core) - allows operating as the oFono service
    - [online-accounts-service](https://snapcraft.io/docs/online-accounts-service-interface) (core) - access to the Online Accounts service
    - [opengl](https://snapcraft.io/docs/opengl-interface) (core) - access OpenGL/GPU hardware
    - [openvswitch](https://snapcraft.io/docs/openvswitch-interface) (core) - control Open vSwitch hardware
    - [openvswitch-support](https://snapcraft.io/docs/openvswitch-support-interface) (core) - enables kernel support for Open vSwitch
    - [optical-drive](https://snapcraft.io/docs/optical-drive-interface) (core) - read/write access to CD/DVD drives
    - [packagekit-control](https://snapcraft.io/docs/packagekit-control-interface) - control the PackageKit service
    - [password-manager-service](https://snapcraft.io/docs/password-manager-service-interface) (core) - read, add, change, or remove saved passwords
    - [personal-files](https://snapcraft.io/docs/personal-files-interface) - read or write files in the user’s home directory
    - [physical-memory-control](https://snapcraft.io/docs/physical-memory-control-interface) (core) - read and write memory used by any process
    - [physical-memory-observe](https://snapcraft.io/docs/physical-memory-observe-interface) (core) - read memory used by any process
    - [ppp](https://snapcraft.io/docs/ppp-interface) (core) - access to configure and observe PPP networking
    - [process-control](https://snapcraft.io/docs/process-control-interface) (core) - pause or end any process on the system
    - ([pulseaudio](https://snapcraft.io/docs/pulseaudio-interface) (core) - play and record sound, deprecated -> audio-playback, audio-record)
    - [raw-usb](https://snapcraft.io/docs/raw-usb-interface) (core) - access USB hardware directly
    - [raw-volume](https://snapcraft.io/docs/raw-volume-interface) - access specific disk partitions
    - [removable-media](https://snapcraft.io/docs/removable-media-interface) (core) - read/write files on removable storage devices
    - [screencast-legacy](https://snapcraft.io/docs/the-screencast-legacy-interface) - allows screen recording and audio recording alongside writing to arbitrary filesystem paths
    - [screen-inhibit-control](https://snapcraft.io/docs/screen-inhibit-control-interface) (core) - prevent screen sleep, lock and screensaver
    - [serial-port](https://snapcraft.io/docs/serial-port-interface) (core) - access serial port hardware
    - [shutdown](https://snapcraft.io/docs/shutdown-interface) (core) - restart or power off the device
    - [snapd-control](https://snapcraft.io/docs/snapd-control-interface) (core) - install or remove software
    - [spi](https://snapcraft.io/docs/spi-interface) (core) - access specific SPI devices
    - [ssh-keys](https://snapcraft.io/docs/ssh-keys-interface) - access SSH private and public keys
    - [ssh-public-keys](https://snapcraft.io/docs/ssh-public-keys-interface) - access SSH public keys
    - [storage-framework-service](https://snapcraft.io/docs/storage-framework-service-interface) (core) - operate as, or interact with, the Storage Framework
    - [system-backup](https://snapcraft.io/docs/the-system-backup-interface) - read-only access to the system for backups
    - [system-files](https://snapcraft.io/docs/system-files-interface) - read or write files in the system
    - [system-observe](https://snapcraft.io/docs/system-observe-interface) (core) - read process and system information
    - [system-packages-doc](https://snapcraft.io/docs/the-system-package-doc-interface) - access system documentation in /usr/share/doc
    - [system-trace](https://snapcraft.io/docs/system-trace-interface) (core) - monitor or control any running program
    - [thumbnailer-service](https://snapcraft.io/docs/thumbnailer-service-interface) (core) - create thumbnail images from local media files
    - [time-control](https://snapcraft.io/docs/time-control-interface) (core) -	change the date and time
    - [timeserver-control](https://snapcraft.io/docs/timeserver-control-interface) (core) - change time server settings
    - [timezone-control](https://snapcraft.io/docs/timezone-control-interface) (core) - change the time zone
    - [tpm](https://snapcraft.io/docs/tpm-interface) (core) - allows access to the Trusted Platform Module device
    - [u2f-devices](https://snapcraft.io/docs/u2f-devices-interface) - use any U2F devices
    - [ubuntu-download-manager](https://snapcraft.io/docs/ubuntu-download-manager-interface) (core) - use the Ubuntu Download Manager
    - [udisks2](https://snapcraft.io/docs/udisks2-interface) (core) - access the UDisks2 service
    - [uhid](https://snapcraft.io/docs/uhid-interface) (core) - create kernel UID devices from user-space
    - [uio](https://snapcraft.io/docs/the-uio-interface) - access uio devices
    - [unity7](https://snapcraft.io/docs/unity7-interface) (core) - access legacy desktop resources from Unity7
    - [unity8](https://snapcraft.io/docs/unity8-interface) (core) - share data with other Unity 8 apps
    - [unity8-calendar](https://snapcraft.io/docs/unity8-calendar-interface) (core) - read/change shared calendar events in Ubuntu Unity 8
    - [unity8-contacts](https://snapcraft.io/docs/unity8-contacts-interface) (core) - read/change shared contacts in Ubuntu Unity 8
    - [upower-observe](https://snapcraft.io/docs/upower-observe-interface) (core) - access battery level and power usage
    - [wayland](https://snapcraft.io/docs/wayland-interface) (core) - access compositors providing the Wayland protocol
    - [x11](https://snapcraft.io/docs/x11-interface) (core) - monitor mouse/keyboard input and graphics output of other apps
  - [Plugins](https://snapcraft.io/docs/snapcraft-plugins)
    - [Local plugin](https://snapcraft.io/docs/writing-local-plugins) - Own plugins for adjusting build system support, adding build system support and/or custom stage-packages deb repos. 
    - Plugins (Programming lanugages)
      - [npm plugin](https://snapcraft.io/docs/npm-plugin)- create parts that use Node.js and/or the JavaScript package manager, npm  (core/20)
      - [nodejs plugin](https://snapcraft.io/docs/nodejs-plugin) -	create parts that use Node.js and/or the JavaScript package manager, npm (core/18)
      - [conda plugin](https://snapcraft.io/docs/the-conda-plugin) - used for parts incorporating the Conda open source package manager system (core/18)
      - [flutter plugin](https://snapcraft.io/docs/flutter-plugin) - easily build and deploy parts for the expressive Flutter UI toolkit (core/18)
      - [python plugin](https://snapcraft.io/docs/python-plugin) - used for parts incorporating projects written with Python 2 or Python 3 (core/18, core20)
      - [rust plugin](https://snapcraft.io/docs/rust-plugin) - build parts from projects written in Rust and using Cargo for dependency management (core/18, core20)
    - Platforms (Platforms)
      - Linux kernel
        - [kbuild plugin](https://snapcraft.io/docs/kbuild-plugin) - build parts that use the Linux kernel build system (kBuild)
        - [kernel plugin](https://snapcraft.io/docs/kernel-plugin) - derived from the kbuild plugin and used to build your own kernel
      - Robot Operating System:
        - [colcon plugin](https://snapcraft.io/docs/the-colcon-plugin) -	build colcon-based parts, typically used with version 2 of the Robot Operating System (ROS 2)
    - Platforms (Tools)
      - dump 	simply dumps the contents from the specified source
      - nil 	useful for parts with no source to import
      - plainbox-provider 	create parts containing a Plainbox test collection known as a provider
  - [Security](https://snapcraft.io/docs/security-sandboxing)
    - [AppArmor](https://wiki.ubuntu.com/AppArmor) - AppArmor is a Mandatory Access Control (MAC) system which is a kernel (LSM) enhancement to confine programs to a limited set of resources.
    - [cgroups](https://www.kernel.org/doc/html/latest/admin-guide/cgroup-v1/cgroups.html) - Control Groups provide a mechanism for aggregating/partitioning sets of tasks, and all their future children, into hierarchical groups with specialized behaviour.
    - [seccomp](http://manpages.ubuntu.com/manpages/bionic/man2/seccomp.2.html)
- Snapstore
  - [Snap Store](https://docs.ubuntu.com/core/en/build-store/)
  - [Snap Store Proxy](https://docs.ubuntu.com/snap-store-proxy/en/)

## Whitepapers

- [Ubuntu Core - Security](https://assets.ubuntu.com/v1/66fcd858-ubuntu-core-security-whitepaper.pdf)
- [Secure IoT device management - Build and deploy a central IoT management solution ](https://ubuntu.com/engage/iot-device-management-whitepaper)

## Blog

- [Snappy Ubuntu Core now on AWS](https://ubuntu.com/blog/snappy-ubuntu-core-now-on-aws)
- [Ubuntu Core: an independent security analysis](https://ubuntu.com/blog/ubuntu-core-security)

## Forums

- [discourse.ubuntu.com](https://discourse.ubuntu.com/)

## Supported distributions

### Snap builtin support

- Ubuntu
  - [Ubuntu Cloud](https://ubuntu.com/download/cloud) (production runtime)
  - [Ubuntu Core](https://ubuntu.com/core) (production runtime)
  - [Ubuntu Desktop](https://ubuntu.com/desktop) (development machine)
  - [Ubuntu Server](https://ubuntu.com/server) (production runtime)
- Ubuntu Desktop flavors (development machines)
  - [Ubuntu Budgie](https://ubuntubudgie.org/)
  - [Kubuntu](https://community.kde.org/Kubuntu)
  - [Ubuntu Kylin](https://wiki.ubuntu.com/Ubuntu%20Kylin)
  - [Lubuntu](https://wiki.ubuntu.com/Lubuntu)
  - [Mate](https://ubuntu-mate.org/)
  - [Ubuntu Studio](https://wiki.ubuntu.com/UbuntuStudio)
  - [Xubuntu](https://wiki.ubuntu.com/Xubuntu)
- [Solus 3](https://getsol.us/home/) and above (development machine)
- [Zorin OS](https://zorinos.com/) (development machine)

### Compatible distribution build systems

- [Yocto project](https://www.yoctoproject.org/) via [meta-snappy](https://github.com/morphis/meta-snappy)

## IoT and Device Services

- [Canonical Ubuntu IoT and device services](https://ubuntu.com/pricing/devices)
  - START SMART: Canonical will validate your hardware, package your apps and prepare your device image (30,000 USD).
  - Full Disk Encryption: Enable full disk encryption with hardware key management and optional key escrow (30,000 USD).
  - Secure Boot: Enable secure boot, ensuring that the device will only run its certified workload (30,000 USD).
  - Device Enablement: If Canonical’s certified hardware list doesn’t include what you need, we may be willing to enable your preferred board (30,000 USD).
  - FIPS Certification: Meet Federal information processing requirements with a FIPS-certified kernel and cryptographic libraries (45,000 USD).
  - Kernel Livepatch: Reduce the number of reboots significantly by live patching your running kernel (60,000 USD).
  - High Availability Kubernetes: With Canonical MicroK8s you gain a fully CNCF conformant cloud-native Kubernetes for device application operations (15,000 USD).

## Companies using Ubuntu Core

- [ABB](https://global.abb/group/en) - [Ubuntu Core 20 secures Linux for IoT](https://ubuntu.com/blog/ubuntu-core-20-secures-linux-for-iot)
- [Bosch Rexroth](https://www.boschrexroth.com) - [Bosch Rexroth adopts Ubuntu Core and snaps for app-based ctrlX AUTOMATION platform](https://ubuntu.com/blog/bosch-rexroth-adopts-ubuntu-core-and-snaps-for-app-based-ctrlx-automation-platform)
- [DELL](https://www.dell.com/) - [The Dell Edge Gateway 3000 launches with Ubuntu Core 16](https://ubuntu.com/blog/the-dell-edge-gateway-3000-launches-with-ubuntu-core-16)
- [Jabil](https://www.jabil.com/) - [Ubuntu Core 20 secures Linux for IoT](https://ubuntu.com/blog/ubuntu-core-20-secures-linux-for-iot)
- [Rigado](https://www.rigado.com/) - [Reducing IoT time to market with Ubuntu Core & Snaps](https://www.youtube.com/watch?v=DbUN0tYM9WU)
- [M2MLabs](http://www.m2mlabs.com/) - [Internet of Things: M2MLabs](https://ubuntu.com/blog/internet-of-things-m2mlabs)
- [Mobica](https://mobica.com/) - [Mobica adopting Ubuntu Core for embedded device development](https://ubuntu.com/blog/mobica-adopting-ubuntu-core-for-embedded-device-development)
- [Rigado](https://www.rigado.com/) - [Rigado cuts customers’ time-to-market with Ubuntu Core and AWS](https://ubuntu.com/engage/case-study-rigado)
- [Plus One Robotics](https://plusonerobotics.com/) - [Ubuntu Core 20 secures Linux for IoT](https://ubuntu.com/blog/ubuntu-core-20-secures-linux-for-iot)

## Books

- [Getting Started with Ubuntu Core for Raspberry Pi 3](https://www.amazon.de/Getting-Started-Ubuntu-Raspberry-English-ebook/dp/B07N6LT9PC?ref_=nav_ya_signin&)
- [Mastering Linux Security and Hardening: Secure Your Linux Server and Protect it](https://www.packtpub.com/eu/cloud-networking/mastering-linux-security-and-hardening-second-edition)
