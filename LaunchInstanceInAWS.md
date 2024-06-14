<!--
  Author: omteja04
  Created on: 14-06-2024 11:43:45
  Description: LaunchInstanceInAWS
-->

# Process Of Launching Instance

- Login to [AWS Academy](https://awsacademy.instructure.com/login/canvas)
- Go to Course &rarr; Modules &rarr; Sandbox Environment &rarr; Start Lab &rarr; AWS
- Search EC2 (virtual servers in the cloud)in SearchBar and click it

&emsp; &emsp; &emsp; &emsp; &darr;

- Click Launch Instance

&emsp; &emsp; &emsp; &emsp; &darr;

- Enter A Name

&emsp; &emsp; &emsp; &emsp; &darr;

- Use Default AWS Linux

&emsp; &emsp; &emsp; &emsp; &darr;

- In key pair login select create a new pair and enter a key pair. (a .pem file will be downloaded)

&emsp; &emsp; &emsp; &emsp; &darr;

- Go to instances

&emsp; &emsp; &emsp; &emsp; &darr;

- Select the created instance and copy the public ipv4 address

&emsp; &emsp; &emsp; &emsp; &darr;

- Go to [MobaXterm](https://mobaxterm.mobatek.net/download-home-edition.html)

&emsp; &emsp; &emsp; &emsp; &darr;

- Click Session &rarr; SSH

&emsp; &emsp; &emsp; &emsp; &darr;

- Paste the copied ipv4 address at hostname

&emsp; &emsp; &emsp; &emsp; &darr;

- check the box specify username &rarr; enter username

&emsp; &emsp; &emsp; &emsp; &darr;

- To enter username click `connect` in aws instances page and then click `SSH Client` by default it will be `ec2-user`

&emsp; &emsp; &emsp; &emsp; &darr;

- click advanced SSH setting &rarr; check `use private key` &rarr; select the `.pem` file downloaded and click OK &rarr; Accept

&emsp; &emsp; &emsp; &emsp; &darr;

`Congratulations You Were Connected to the Server`
