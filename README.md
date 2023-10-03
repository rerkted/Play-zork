# Zork Packer Adventure: AWS Edition 🌌✨

##Welcome to a mystical journey through the realms of AWS, where we harness the ancient powers of Terraform and Packer to summon the legendary game of Zork right into the cloud. Step into a world where code and fiction intertwine, and every terraform apply beckons you closer to the Great Underground Empire.

Overview 📜

Before you begin your journey, provisioning your AWS environment; VPC, and subnet activated is a must!

This repository contains all the magical incantations you need to:

Craft a golden AMI with Packer, imbibed with the essence of Zork.
Bring forth an EC2 instance to immerse yourself in the game of infinite adventures.
## Getting started


The realms of AWS await your exploration, and the magic of Zork is just a packer build away.
(ensure you're in the correct directory when applying packer below: 
``` 
cd ~/play/
packer validate .\packer.json
packer build .\packer.json

```

## Run Game Script (if your journey doesn't bootstrap...)

Once the machine is turned on, run zork-run.sh file

```
./zork-run.sh
```


