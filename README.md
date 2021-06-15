This is a minimum complete verifiable example for a molecule bug.

In order to test it:

1. Clone this repository
2. Cd into its directory
3. Run it with `molecule --debug converge`
4. See that no output is generated (because the verbosity flag is not being passed to Ansible).
5. Forcefuly add verbosity to see the difference: `molecule --debug converge -- -vvv`

