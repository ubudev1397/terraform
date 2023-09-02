</b></details>

### install terraform on mac

<details>
<summary>Command to install terraform via homebrew
```
brew tap hashicorp/tap
```
<details>
```
brew install hashicorp/tap/terraform
```
```
brew update
```
```
brew upgrade hashicorp/tap/terraform
```
brew upgrade hashicorp/tap/terraform



</b></details>

### SSH key set up from aws cli

<details>
<summary>Command to create and download a key called "MyKeyPair"

```
aws ec2 create-key-pair --key-name MyKeyPair --query 'KeyMaterial' --output text > ~/.ssh/MyKeyPair.pem
chmod 400  ~/.ssh/MyKeyPair.pem
```


</b></details>

### test 1

<details>
<summary>test summary 1

```
test 1
```