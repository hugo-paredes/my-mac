# Mac Provisioning Using Ansible

## Install pre-requisites

1. Install XCode command line tools:

```shell
xcode-select --install
```

2. Install [brew](https://brew.sh):

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible):

```shell
# 1. Upgrade pip
python3 -m pip install --upgrade pip

# 2. Install ansible
python3 -m pip install ansible --user
```

## Usage

1. Open a terminal
2. Clone the repository
3. Run the command:

```shell
ansible-playbook playbooks/main.yml
```
