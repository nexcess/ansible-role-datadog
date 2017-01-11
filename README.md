# Ansible Role: Nexcess DataDog

This role encapsulates the DataDog.datadog role and injects:

- Basic project defaults
- Project keys/tags
- Datadog API key (if set by the root playbook)

## Role Variables

Essentially any of the Datadog.data/defaults/mail.yml vars are valid *EXCEPT* datadog_checks.  To define checks in your project use the datadog_role_checks dict.  It will get combined with the default set of base checks (defined in datadog_base_checks in defaults/main.yml) to make the complete set of datadog_checks.

Again, don't set datadog_checks :)

## Dependencies

- Datadog.datadog

## License

MIT
