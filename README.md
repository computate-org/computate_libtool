
# Install the prerequisite applications, powertools and libmodplug

- https://github.com/computate-org/computate_powertools
- https://github.com/computate-org/computate_libmodplug

# Install the libtool ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_libtool

# Clone the libtool ansible role. 
git clone git@github.com:computate-org/computate_libtool.git ~/.ansible/roles/computate.computate_libtool

# Change into the libtool ansible role directory. 
cd ~/.ansible/roles/computate.computate_libtool
```

# Run the libtool ansible playbook to install libtool locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
