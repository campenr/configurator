# Configurator

Declarative machine configuration.

## Requirements

- python3
- brew (MacOS)
- pipx
- Ansible

## Setup

1. Install pipx

    ```
    # Linux
    python3 -m pip install pipx
    python3 -m pipx ensurepath
    ```

    ```
    # MacOS
    brew install pipx
    pipx ensurepath
    ```

2. Install Ansible with pipx

    ```
    pipx install --include-deps ansible
    ```

## Instructions

Run provisioning with:

 ```
 ansible-playbook base.yml --connection=local -v -K
 ```
