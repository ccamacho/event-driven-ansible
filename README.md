# Collection for Event-Driven Ansible

This collection contains event source plugins, event filters and example rulebooks to be used with [ansible-rulebook](https://ansible-rulebook.readthedocs.io/en/stable/).

<p style="text-align: center" align="center">
    <a href="https://github.com/ccamacho/event-driven-ansible/actions?workflow=integration-tests"><img height="20px" src="https://github.com/ccamacho/event-driven-ansible/workflows/integration-tests/badge.svg?event=schedule"/> </a>
    <a href="https://github.com/ccamacho/event-driven-ansible/actions?workflow=linters"><img height="20px" src="https://github.com/ccamacho/event-driven-ansible/workflows/linter/badge.svg?event=schedule"/> </a>
    <a href="https://github.com/ccamacho/event-driven-ansible/actions?workflow=tests"><img height="20px" src="https://github.com/ccamacho/event-driven-ansible/workflows/tests/badge.svg?event=schedule"/> </a>
</p>

## Install

Install the ansible.eda collection with the Ansible Galaxy CLI:

```
ansible-galaxy collection install ansible.eda
```

The python module dependencies are not installed by ansible-galaxy. They must be installed manually using pip:

```
pip install -r requirements.txt
```

## Contributing

Please refer to the [contributing guide](./CONTRIBUTING.md) for information about how you can contribute to the project.
