# Ansible Role: Nexcess DataDog

This role encapsulates the DataDog.datadog role and injects:

- Basic project defaults
- Project keys/tags
- Datadog API key (if set by the root playbook)

## Role Variables

Essentially any of the Datadog.data/defaults/mail.yml vars are valid.  We don't add in any extra

## Dependencies

- Datadog.datadog

## License

Proprietary
