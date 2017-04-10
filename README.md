# ansible-playbooks
[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/willianpaixao/ansible-playbooks/master?grs=github&t=white)

> Note: For now I only pushed my most used playbooks.

### Run

Quite simple, just run:

``` bash
$ ansible-playbook -K main.yml
```
### Test

Next thing I need to do is clean my tasks and make it comply with the best
practices of DevOps Culture. I've found those two packages, although haven't
refactored yet.

``` bash
$ pip install ansible-lint ansible-review
$ ansible-review ansible/main.yml
```
