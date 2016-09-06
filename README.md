# ansible-growl

Install Growl via the Mac App Store. (Note that no non-MAS option is provided because other available downloads are a major version behind.)

## Dependencies

* [icopp.mas-cli](https://github.com/icopp/ansible-mas-cli)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.growl
```

## License

MIT
