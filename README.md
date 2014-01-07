# p2p-networkmanager

This application enables control of security groups and permanent IP address to virtual compute instances.

## Build

This project depends upon `p2p-build` being setup with `ant` and `ant-contrib`. [See instructions](http://barnyard.github.io/p2p-build)

### Dependencies

The following projects should be siblings to this project and had 'publish' targets run on them.

- [p2p-app](http://barnyard.github.io/p2p-app)

### Compiling

Add a properties file with your configuration you'd like in the `properties` directory.

    ant

