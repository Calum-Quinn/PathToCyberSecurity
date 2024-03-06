# Bash - System 1

The goal of this exercise is to connect to a server using SSH and retrieve the root password without having administrative privileges.

The main thing the articles talk about is the usage of environment variables to alter the way a program works. The attacker can change certain variables used by the program to make it misbehave to their advantage.
The attacker can also change which secondary programs are invoked so that it uses their versions.

The articles warn us to avoid using anything that invokes a `shell` as that is an "easy" entrypoint.
