# alfred-ssh-key-copy
Alfred workflow to copy public (or private) SSH key


![Copy SSH Key](docs/sshkeycopy.png?raw=true "SSHCopy")

## Requirements

- jq (https://stedolan.github.io/jq/) 
  - `brew install jq`

## Usage

- Download and Run `ssh-key-copy.alfredworkflow`
- Open Alfred and type `sshkey` and select your key
  - ⏎ to copy the public key
  - ⌘ + ⏎ to copy the private key
  - ⌥ + ⏎ to reveal the key in finder
