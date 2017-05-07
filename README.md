## Docker SSH Authorized Keys

### Usage

- one-touch run

        docker run -v /root:/user -e AUTHORIZED_KEYS="`cat ~/.ssh/id_ed25519.pub`" oguya/docker-authorized-keys
