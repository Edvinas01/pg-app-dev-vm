# What is it?
A Vagrant configuration that starts up a PostgreSQL database and SonarQube in a virtual machine.

## Installation
First install [Vagrant] and [Virtual Box].

Then checkout the project and navigate to root project dir. Afterwards run the following command to 
create a new VM:
```bash
vagrant up
```

After it finishes, open up your browser and enter the following URL: http://localhost:9000

## Notes
If you want to stop the VM:
```bash
vagrant suspend
```

If you want to destroy any files created by this Vagrant configuration:
```bash
vagrant destroy
```

For more info on how to configure and use SonarQube see [SonarQube Docs].

[Virtual Box]: https://www.virtualbox.org/
[SonarQube Docs]: https://docs.sonarqube.org/display/SONAR
[Vagrant]: https://www.vagrantup.com/