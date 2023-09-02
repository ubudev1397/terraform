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
<summary>install the HashiCorp tap, a repository of all our Homebrew packages.

```
brew tap hashicorp/tap
```
</b></details>

### test 2

<details>
<summary>install Terraform with hashicorp/tap/terraform

```
brew install hashicorp/tap/terraform
```

</b></details>

### test 3

<details>
<summary>To update to the latest version of Terraform, first update Homebrew.

```
brew update
```

### test 4

<details>
<summary>run the upgrade command to download and use the latest Terraform version.

```
brew upgrade hashicorp/tap/terraform
```