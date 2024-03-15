# README

This repository contains an Ansible playbook for managing my macOS systems.

## Requirements

Before running these playbooks, make sure you have the following installed:

- Ansible (preferably version 2.9 or higher)
- Python 3.6 or higher

## Getting Started

To use these playbooks, follow these steps:

1. Clone this repository to your local machine using Git.
2. Install the necessary dependencies by running `ansible-galaxy install -r requirements.yaml` in the top level directory of the repository.
3. Run the playbooks using the following command:
   - `ansible-playbook -K playbook.yaml`
4. The playbooks will run and configure your macOS system accordingly.
5. Install [dotfiles](https://github.com/eliseomartelli/dotfiles) with GNU Stow.

## License

These playbooks are licensed under the MIT License. See the [LICENSE](./license) file for more information.
