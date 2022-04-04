# cs4843-assignment02

## Requirements

* create an auto scalling yaml file
* update files to utilize my personal AWS account
* document my learning and findings

## Included

### files

* servers.yml
* start.sh

### documentation

While in class we learned about the importance of protecting our servers and whom might attempt to access our information. This important factor lead to learning about gateways and VPCs that controlled the access to our server's important information. This included creating access points that we created either through IAMs or through available ports. 

The next step in learning was figuring out YAML files. These YAML files allowed for a developer to create *and destroy* Cloud resources. CloudFormation templates could be used to create, in our case, auto scalling servers that would spin up and spin down servers as the load needed them. All while taking into account of the previous paragraphs needs for security. 

Utilizing my knowledge about security and my new knowledge of how to create CloudFormation templates, I could create ***and destroy*** resources on the fly. This allowed for testing new possible configurations including creating networks, creating points to access these instances and learning to review what was created so nothing gets left behind and charging me, ha! I also utilized several available templates throughout AWS's website to test out more than just auto scalling! 

All in all, while this took some time for me to compelte and learn, this assignment was filled with **a lot** of learning and trial-and-error!
