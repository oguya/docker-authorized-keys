## Docker SSH Authorized Keys

### Usage

- one-touch run

        docker run -v /tmp/:/user -e AUTHORIZED_KEYS="`cat ~/.ssh/id_ed25519.pub`" oguya/authorized-keys
