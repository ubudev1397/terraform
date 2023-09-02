
</b></details>

### SSH key set up from aws cli

<details>
<summary>Command to create and download a key called "MyKeyPair"

```
aws ec2 create-key-pair --key-name MyKeyPair --query 'KeyMaterial' --output text > ~/.ssh/MyKeyPair.pem
chmod 400  ~/.ssh/MyKeyPair.pem
```