# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  # All Vagrant configuration is done here. The most common configuration
  # options are documented and commented below. For a complete reference,
  # please see the online documentation at vagrantup.com.
  config.vm.define "kirjastokaista.fi.test" do |kirjastokaista_fi|
  kirjastokaista_fi.vm.hostname = "kirjastokaista.fi.test"
  kirjastokaista_fi.vm.network "private_network", ip: "192.168.33.3"
    end
  config.vm.define "makupalat.fi.test" do |makupalat_fi|
  makupalat_fi.vm.hostname = "makupalat.fi.test"
  makupalat_fi.vm.network "private_network", ip: "192.168.33.4"
    end
  config.vm.define "okariino.fi.test" do |okariino_fi|
  okariino_fi.vm.hostname = "okariino.fi.test"
  okariino_fi.vm.network "private_network", ip: "192.168.33.5"
    okariino_fi.vm.box = "puppetlabs/debian-6.0.9-64-nocm"
    end
  config.vm.define "oldsaha.test" do |oldsaha|
  oldsaha.vm.hostname = "oldsaha.test"
  oldsaha.vm.network "private_network", ip: "192.168.33.6"
    end
  config.vm.define "kirjasampo.fi.test" do |kirjasampo_fi|
  kirjasampo_fi.vm.hostname = "kirjasampo.fi.test"
  kirjasampo_fi.vm.network "private_network", ip: "192.168.33.7"
    end
  config.vm.define "api.kirjasampo.fi.test" do |api_kirjasampo_fi|
  api_kirjasampo_fi.vm.hostname = "api.kirjasampo.fi.test"
  api_kirjasampo_fi.vm.network "private_network", ip: "192.168.33.8"
    end
  config.vm.define "shell1.sigmatic.fi.test" do |shell1_sigmatic_fi|
  shell1_sigmatic_fi.vm.hostname = "shell1.sigmatic.fi.test"
  shell1_sigmatic_fi.vm.network "private_network", ip: "192.168.33.9"
    end
  config.vm.define "digi.kirjastot.fi.test" do |digi_kirjastot_fi|
  digi_kirjastot_fi.vm.hostname = "digi.kirjastot.fi.test"
  digi_kirjastot_fi.vm.network "private_network", ip: "192.168.33.10"
    end
  config.vm.define "testi.kirjastot.fi.test" do |testi_kirjastot_fi|
  testi_kirjastot_fi.vm.hostname = "testi.kirjastot.fi.test"
  testi_kirjastot_fi.vm.network "private_network", ip: "192.168.33.11"
    end
  config.vm.define "kifi1.kirjastot.fi.test" do |kifi1_kirjastot_fi|
  kifi1_kirjastot_fi.vm.hostname = "kifi1.kirjastot.fi.test"
  kifi1_kirjastot_fi.vm.network "private_network", ip: "192.168.33.12"
    end
  config.vm.define "saha.kirjastot.fi.test" do |saha_kirjastot_fi|
  saha_kirjastot_fi.vm.hostname = "saha.kirjastot.fi.test"
  saha_kirjastot_fi.vm.network "private_network", ip: "192.168.33.13"
    end
  config.vm.define "webkake.kirjastot.fi.test" do |webkake_kirjastot_fi|
  webkake_kirjastot_fi.vm.hostname = "webkake.kirjastot.fi.test"
  webkake_kirjastot_fi.vm.network "private_network", ip: "192.168.33.14"
    end
  config.vm.define "mail2.kirjastot.fi.test" do |mail2_kirjastot_fi|
  mail2_kirjastot_fi.vm.hostname = "mail2.kirjastot.fi.test"
  mail2_kirjastot_fi.vm.network "private_network", ip: "192.168.33.15"
    end
  config.vm.define "ekirjasto.kirjastot.fi.test" do |ekirjasto_kirjastot_fi|
  ekirjasto_kirjastot_fi.vm.hostname = "ekirjasto.kirjastot.fi.test"
  ekirjasto_kirjastot_fi.vm.network "private_network", ip: "192.168.33.16"
    end

  config.vm.define "mail2.kirjastot.fi.test" do |mail2_kirjastot_fi|
  mail2_kirjastot_fi.vm.hostname = "mail2.kirjastot.fi.test"
  mail2_kirjastot_fi.vm.network "private_network", ip: "192.168.34.2"
    end
  config.vm.define "mail.test" do |mail|
  mail.vm.hostname = "mail.test"
  mail.vm.network "private_network", ip: "192.168.34.3"
    end
  config.vm.define "d8dev.test" do |d8dev|
  d8dev.vm.hostname = "d8dev.test"
  d8dev.vm.network "private_network", ip: "192.168.34.4"
    end


  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "chef/debian-7.4"
  # config.vm.box = "puppetlabs/debian-6.0.9-64-nocm"
  # Disable automatic box update checking. If you disable this, then
  # boxes will only be checked for updates when the user runs
  # `vagrant box outdated`. This is not recommended.
  # config.vm.box_check_update = false

  # Create a forwarded port mapping which allows access to a specific port
  # within the machine from a port on the host machine. In the example below,
  # accessing "localhost:8080" will access port 80 on the guest machine.
  # config.vm.network "forwarded_port", guest: 80, host: 8080

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  # Create a public network, which generally matched to bridged network.
  # Bridged networks make the machine appear as another physical device on
  # your network.
  # config.vm.network "public_network"

  # If true, then any SSH connections made will enable agent forwarding.
  # Default value: false
  # config.ssh.forward_agent = true

  # Share an additional folder to the guest VM. The first argument is
  # the path on the host to the actual folder. The second argument is
  # the path on the guest to mount the folder. And the optional third
  # argument is a set of non-required options.
  # config.vm.synced_folder "../data", "/vagrant_data"

  # Provider-specific configuration so you can fine-tune various
  # backing providers for Vagrant. These expose provider-specific options.
  # Example for VirtualBox:
  #
  # config.vm.provider "virtualbox" do |vb|
  #   # Don't boot with headless mode
  #   vb.gui = true
  #
  #   # Use VBoxManage to customize the VM. For example to change memory:
  #   vb.customize ["modifyvm", :id, "--memory", "1024"]
  # end
  #
  # View the documentation for the provider you're using for more
  # information on available options.

  # Enable provisioning with CFEngine. CFEngine Community packages are
  # automatically installed. For example, configure the host as a
  # policy server and optionally a policy file to run:
  #
  # config.vm.provision "cfengine" do |cf|
  #   cf.am_policy_hub = true
  #   # cf.run_file = "motd.cf"
  # end
  #
  # You can also configure and bootstrap a client to an existing
  # policy server:
  #
  # config.vm.provision "cfengine" do |cf|
  #   cf.policy_server_address = "10.0.2.15"
  # end

  # Enable provisioning with Puppet stand alone.  Puppet manifests
  # are contained in a directory path relative to this Vagrantfile.
  # You will need to create the manifests directory and a manifest in
  # the file default.pp in the manifests_path directory.
  #
  # config.vm.provision "puppet" do |puppet|
  #   puppet.manifests_path = "manifests"
  #   puppet.manifest_file  = "site.pp"
  # end

  # Enable provisioning with chef solo, specifying a cookbooks path, roles
  # path, and data_bags path (all relative to this Vagrantfile), and adding
  # some recipes and/or roles.
  #
  # config.vm.provision "chef_solo" do |chef|
  #   chef.cookbooks_path = "../my-recipes/cookbooks"
  #   chef.roles_path = "../my-recipes/roles"
  #   chef.data_bags_path = "../my-recipes/data_bags"
  #   chef.add_recipe "mysql"
  #   chef.add_role "web"
  #
  #   # You may also specify custom JSON attributes:
  #   chef.json = { :mysql_password => "foo" }
  # end

  # Enable provisioning with chef server, specifying the chef server URL,
  # and the path to the validation key (relative to this Vagrantfile).
  #
  # The Opscode Platform uses HTTPS. Substitute your organization for
  # ORGNAME in the URL and validation key.
  #
  # If you have your own Chef Server, use the appropriate URL, which may be
  # HTTP instead of HTTPS depending on your configuration. Also change the
  # validation key to validation.pem.
  #
  # config.vm.provision "chef_client" do |chef|
  #   chef.chef_server_url = "https://api.opscode.com/organizations/ORGNAME"
  #   chef.validation_key_path = "ORGNAME-validator.pem"
  # end
  #
  # If you're using the Opscode platform, your validator client is
  # ORGNAME-validator, replacing ORGNAME with your organization name.
  #
  # If you have your own Chef Server, the default validation client name is
  # chef-validator, unless you changed the configuration.
  #
  #   chef.validation_client_name = "ORGNAME-validator"

config.vm.provision "ansible" do |ansible|
    ansible.playbook = "/home/anttis/projektit/ansible/kifi-playbooks/site.yml"
    # ansible.verbose = 'vvvv'
    ansible.inventory_path = 'inventory'
    ansible.ask_vault_pass = true
    ansible.sudo = true
    ansible.raw_arguments = ['--timeout=30']
  end

end
