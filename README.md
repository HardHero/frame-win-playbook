# frame_playbook
`frame_playbook` is a great ansible playbook.

# Setup
Before you run this script, you need to run the powershell script at the link below to enable WinRM:
`https://github.com/ansible/ansible/blob/devel/examples/scripts/ConfigureRemotingForAnsible.ps1`

# Usage
## Development (if you used `--vagrant` flag: `vagrant up`
When you make changes, run `vagrant provision` to update your vms.
## Production
`ansible-playbook -i production site.yml`
