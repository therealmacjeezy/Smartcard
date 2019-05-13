# Smartcard Scripts

## Contents
- Smartcard_lockpam.sh
 - Configures the pam module to only allow Smartcard authentication
- Smartcard_pivssh.sh
 - Creates an alias in the bash_profile (or zch profile) to set the PKCS11Provider
- Smartcard_unlockpam.sh
 - Configures the pam module to allow password authentication (removes the changes made for lockpam)