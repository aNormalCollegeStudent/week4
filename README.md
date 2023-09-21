# CS320 Week 4 Playbook

## Running the playbook

- Verify that `ansible` is installed on the ansible controller machine
- Start by cloning the repository with `git clone`, you may also close it to another location, but keep in mind that you will need to change the file path for the copying of sample files if you do.
- Make changes to `<repository directory>/week4/inventory` to reflect the devices that you will be running the script on, or alternatively, replace the inventory file with your own
- Replace the sample files in `<repository directory>/week4/webFiles` with your webpage files for the server
- Nagivate to `<repository directory>/week4/` if you are not already there
- Run `ansible-playbook -i inventory week4playbook.yml` to run the playbook