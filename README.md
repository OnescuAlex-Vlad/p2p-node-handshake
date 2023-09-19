# Ethereum P2P Node Handshake

This is an implementation of a P2P network Handshake.

# Description

RLPx protocol - is a TCP-based transport protocol used for communication among Ethereum nodes. The protocol carries encrypted messages belonging to one or more 'capabilities' which are negotiated during connection establishment. 

# In order to execute the Handshake between 2 nodes

cargo run [node_id] [node_ip] [port]

Example: cargo run 00e6f58d28f907f0ffdce7666289107f7cdfacf55611feb8f208639e9deddee90408b5357d82fe3be328a323c4bd129b85b33cd7a494afbedd6a2e87ca8a56a1 65.21.224.171 30303


# Acknowledgments 

https://github.com/ethereum/devp2p/blob/master/rlpx.md