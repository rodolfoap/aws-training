# HOWTO

* In order to create a running instance, just follow this sequence:

```
├── create.vpc 		1. Create the default vpc, if it still does not exist.
├── create.keypair 	2. Create a keypair, if it still does not exist.
├── fix.secgroup 	3. Add a SSH inbound rule to the security group.
├── create.ec2 		4. Create and launch the instance. It will take less than a minute, and it is not accessible the instant it was created.
├── config.ec2 		5. Configure the `~/bin/ssh.aws` script.
├── list.ec2 		6. List running instances
├── pause.ec2 		7. Pause (stop) instances
├── kill.ec2 		8. Kill (terminate) instances
├── rap_aws.pem
├── misc 		*. Just a bunch of command examples
└── README.md
```
