# Welcome to Let there be Lightning! 👋

<img align="left" width="200" height="200" src="https://www.ltbl.io/logo.png">

At Let there be Lightning (LtbL), we are pioneering sound money solutions with intuitive tools and services for Bitcoin, the Lightning Network and layer 2 innovation.

Our mission is to empower application developers with open-source, standards-compliant, and interoperable development tools and infrastructure services that are easy to use and still flexible enough for complex use cases.

The following overview is designed to be your starting point and get you building your applications quickly using our SDKs and services.

## Development Tool Kits 🛠️

A suite of SDKs is available for different programming languages to cater to a wide range of development needs across mobile, desktop and web platforms.

### Bitcoin Development Kit (bindings)

[Bitcoin Development Kit (BDK)](https://bitcoindevkit.org/) is an open-source library that allows you to seamlessly build cross-platform Bitcoin wallets and applications without worrying about bitcoin internals. It is originally written in Rust, so LtbL offers ready-to use and up-to-date Flutter and React Native bindings for it. Saving you the time to write these yourselves and letting you focus on your application logic.

- Flutter: https://github.com/LtbLightning/bdk-flutter
- React Native: https://github.com/LtbLightning/bdk-rn

### LDK Node (bindings)

A ready-to-go Lightning node library built using [Lightning Development Kit (LDK)](https://lightningdevkit.org/) and [BDK](https://bitcoindevkit.org/). Also originally written in Rust, LtbL provides up-to-date bindings for Flutter, React Native and Node.js.

- Flutter: https://github.com/LtbLightning/ldk-node-flutter
- React Native: https://github.com/LtbLightning/ldk-node-rn
- Node.js: https://github.com/LtbLightning/ldk-node-nodejs

### Payjoin Development Kit (bindings)

[Payjoin Development Kit (PDK)](https://payjoindevkit.org/) is a full and completely standalone Payjoin implementation with supporting modules enabling great flexibility. Also originally written in Rust, LtbL provides up-to-date bindings for different programming languages.

- Flutter: https://github.com/LtbLightning/payjoin-flutter
- Python: https://github.com/LtbLightning/payjoin-ffi/tree/main/python

## Services ⚙️

Building self-custodial apps and safely onboarding users can be very challenging. To improve this experience for both developers as for users of your app, we provide a range of free, standardised and opt-in services.

### Esplora

Our Esplora service offers an easy-to-use, API-based access to Bitcoin blockchain data.

All packages like BDK, LDK Node and PDK rely on this information and can be configured with the following URLs depending on the desired network:

- Mutinynet: https://mutinynet.ltbl.io/api
- Testnet: https://testnet.ltbl.io/api
- Mainnet: https://mainnet.ltbl.io/api

This service can be utilized as the default blockchain data source in your app, providing a seamless initial user experience, with the option for users to configure their own node in the application settings later, if preferred.

### Rapid Gossip Sync (RGS)

The Lightning Network's efficiency and performance depend heavily on timely and accurate network information. Our [Rapid Gossip Sync (RGS)](https://github.com/lightningdevkit/rapid-gossip-sync-server) server enhances path finding on the Lightning Network by providing developers and their applications with fast, reliable access to network topology information. This service is crucial for applications requiring up-to-date data for routing payments efficiently, eliminating long sync times for their end-users. This service is compatible with and can be easily configured in the LDK Node package.

- Mutinynet: https://mutinynet.ltbl.io/snapshot
- Testnet: https://testnet.ltbl.io/snapshot
- Mainnet: https://mainnet.ltbl.io/snapshot

### Versioned Storage System (VSS)

In a non-custodial Lightning wallet, it is crucial to securely store and manage various types of state data. This includes maintaining a list of open channels with other nodes in the network and updating the channel state for every payment made or received. Relying solely on user devices to store this information is not reliable, as data loss could lead to the loss of funds or even the entire wallet. To address this challenge, the [VSS project](https://github.com/lightningdevkit/vss-server) introduces a framework and a readily available service that can be hosted by anyone as a Versioned Storage Service.

LtbL runs this service and makes it available for Lightning wallet developers to offer seamless backups to their users without having to maintain any infrastructure themselves.

- Mutinynet: https://mutinynet.ltbl.io/vss
- Testnet: https://testnet.ltbl.io/vss
- 🔜 Mainnet:

## Learn 🎓

To help you quickly familiarize yourself with our tools and services, we offer a range of demo applications and workshops:

### Demo apps

Explore our demo applications to see our SDKs and services in action. They can serve as a quick start guide for your own development efforts.

- BDK Flutter app: https://github.com/LtbLightning/bdk-flutter-quickstart  
  (Accompanying guide: https://bitcoindevkit.org/blog/exploring-bdk-flutter/)
- LDK Node Flutter app: https://github.com/LtbLightning/ldk-node-flutter-demo
- BDK React Native app: https://github.com/LtbLightning/bdk-rn-demo  
  (Accompanying guide: https://bitcoindevkit.org/blog/exploring-bdk-rn/)
- LDK Node React Native app: https://github.com/LtbLightning/ldk-node-rn-demo
- Payjoin Flutter app: https://github.com/LtbLightning/payjoin-flutter-demo

### Workshops

Participate in our workshops for hands-on experience and in-depth understanding of building with LtbL. Workshops can be booked for live training sessions by contacting [hello@ltbl.io](mailto:hello@ltbl.io), they can be assisted at some Bitcoin events, or you can just follow the instructions in the github repositories at your own pace. We have workshops available for Flutter and React Native.

#### Workshops in Flutter

- BDK Flutter: https://github.com/LtbLightning/bdk-flutter-workshop
- LDK Node Flutter: https://github.com/LtbLightning/ldk-node-flutter-workshop

#### Workshops in React Native

- BDK React Native: https://github.com/LtbLightning/bdk-rn-workshop
- LDK Node React Native: https://github.com/LtbLightning/ldk-node-rn-workshop

## Support and Community 🤝

Join our developer community to connect with fellow developers, share ideas, and get support from the LtbL team. Access our Discord server here: https://discord.gg/Zb8YQv6z85

## Share your project 🗣️

If you're building or planning to build a project using our SDKs or services, **we'd love to hear from you!**

**Reach out** by emailing [hello@ltbl.io](mailto:hello@ltbl.io) with a brief description of your project, the SDKs or services you are utilizing, and, if possible, any links to your project's website, repository, or any relevant materials. Sharing your project with us can open up several opportunities.

## Feedback and Contributions ✨

We believe in building collaboratively and welcome contributions from the community. If you have feedback, suggestions, or want to contribute to our projects, do not hesitate to open a pull request, create an issue or discuss on our Discord Server.
