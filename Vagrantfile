# Vagrantfile configuration for VMware Fusion (vmware_desktop)
Vagrant.configure("2") do |config|

  # Define the base box you want to use
  config.vm.box = "bento/ubuntu-20.04-arm64"  # Replace with your desired box
  config.vm.hostname = "jumpbox"

  # Set the provider to VMware Desktop (Fusion or Workstation)
  config.vm.provider "vmware_fusion" do |v|
    v.memory = 2048           # Set the memory for the VM
    v.cpus = 2                # Set the number of CPUs for the VM
    v.gui = true              # Set to true if you want to start the VM with a GUI
    # v.linked_clone = true    # Uncomment to use linked clones if supported
  end

end
