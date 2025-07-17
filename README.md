# harvester-overcommit-update-script
A simple Bash script for updating all the VMs in a Harvester cluster with the current overcommit settings.

## Setup
1. Edit the `update_overcommit.sh` file and replace the following line with the path to your KUBECONFIG file.
```
export KUBECONFIG=<path_to_kubeconfig>
```

2. Make the script executable
```
chmod +x ./update_overcommit.sh
```

3. Run the script
```
sh ./update_overcommit.sh
```


