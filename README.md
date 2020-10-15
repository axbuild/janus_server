# janus_server

must have ssl

STEP 1: Create a Sudo User on Ubuntu
  1.1 Use the adduser command to add a new user to your system.
  $ adduser username
  1.2 Use the usermod command to add the user to the sudo group.
  $ usermod -aG sudo username
  1.3 Use the su command to switch to the new user account.
  $ su - username
