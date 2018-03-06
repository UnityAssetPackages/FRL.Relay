# FRLRelay
The Holojam Relay and Vive Device Emitter supported by FRL.

# Run the relay
```bash
node Relay/relay.js

flags:
   --tracked-ips-only: Only send to ip mapped rigidbodies which are actively tracked.
   --target-data-only: If a rigidbody is ip mapped, only send it's information to it (significantly reduce data transfer amount).
```

# Run the Vive Device Emitter
```bash
python3 ViveDeviceEmitter/vivedeviceemitter.py
```
