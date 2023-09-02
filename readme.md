</b></details>

### SSH key set up from aws cli

<details>
<summary>Command to create and download a key called "MyKeyPair"

```
aws ec2 create-key-pair --key-name MyKeyPair --query 'KeyMaterial' --output text > ~/.ssh/MyKeyPair.pem
chmod 400  ~/.ssh/MyKeyPair.pem
```


</b></details>

###1

<details>
<summary>install the HashiCorp tap, a repository of all our Homebrew packages.

```
brew tap hashicorp/tap
```
</b></details>

###2

<details>
<summary>install Terraform with hashicorp/tap/terraform

```
brew install hashicorp/tap/terraform
```

</b></details>

###3

<details>
<summary>To update to the latest version of Terraform, first update Homebrew.

```
brew update
```

###4

<details>
<summary>run the upgrade command to download and use the latest Terraform version.

```
brew upgrade hashicorp/tap/terraform
```