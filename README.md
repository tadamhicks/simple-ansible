# simple-ansible

After many requests I've decided to put together a repo of simple Ansible playbooks for folks to test with.

## usage

Quite simple.
```
git clone git@github.com:tadamhicks/simple-ansible.git

cd simple-ansible

touch hosts
```

Inside the `hosts` file is where you will put your groups.

#### Example:

```
[apache]
10.30.20.2 ansible_ssh_user=sdavis
```
where `sdavis` is the user Ansible may ssh with.  I like using keys for auth and sudo privs for users over using passwords.
