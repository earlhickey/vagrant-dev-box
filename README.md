# vagrant-dev-box

## pre install

1. Install VirtualBox (https://www.virtualbox.org/wiki/Downloads)
2. Install Vagrant (http://www.vagrantup.com/downloads)

## install

1. Clone project

    ```bash
    git clone git@github.com:earlhickey/vagrant-dev-box.git
    ```

2. Copy config file

    ```bash
    cp ansible/vars/all.yml ansible/vars/all.local.yml
    ```

3. Edit config file

4. Copy vhosts file

    ```bash
    cp ansible/roles/apache/templates/001_vhosts.conf.dist ansible/roles/apache/templates/001_vhosts.conf
    ```

5. Edit vhosts file

## usage

1. Start

    ```bash
    vagrant up
    ```

2. Update

    ```bash
    vagrant provision
   ```

3. Login

    ```bash
    vagrant ssh
    ```
