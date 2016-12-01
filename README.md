# frame_playbook
`frame_playbook` is a great ansible playbook.

# Setup
Before you run this script, you need to run the powershell script at the link below to enable WinRM:
`https://github.com/ansible/ansible/blob/devel/examples/scripts/ConfigureRemotingForAnsible.ps1`

# Usage
This Playbook does the following:
1. Create the User `frame` and add them to a group
2. Sets up `./project_folder` for this repo
3. Adds the psm1 template to the project folder
4. Creates and adds the screensaver module to the users profile
5. Sets the screensaver timeout to 45 seconds
