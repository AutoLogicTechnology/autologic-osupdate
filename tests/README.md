# Tests
The testing folder is used for launching a VM via Vagrant/VirtualBox and provisioning it using the current role. This allows for rapid testing to be done, with ease, against a local VM, as and when changes are made to the Role.

## Requirements
- Vagrant
- VirtualBox

You can use another provider other than VirtualBox should you wish, but you'll have to configure the ```Vagrantfile``` your self.

## Usage
Open up a terminal and execute ```vagrant up```. This will give you an initial VM to test with and also provision it using this Role. Any errors will become quite clear to the reader. After your initial ```up```, you can use ```vagrant provision``` after Role changes or ```vagrant reload``` to start with a fresh VM.
