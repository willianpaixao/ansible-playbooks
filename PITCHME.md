= Ansible playbooks
This repository collect my most ordinary and used
[Ansible](https://www.ansible.com/) playbooks.Nothing special, but very handy
for new Linux instalations and could be used for begginers on Ansible and
configuration management tools.

---

== Packaging modules

=== apt

``` yaml
- name: Ensure that the cache is updated.
  apt: update_cache=yes cache_valid_time=3600
  tags: apt
```

---

``` yaml
- name: Ensure that the packages are upgraded.
  apt: upgrade=dist
  tags: apt
```
