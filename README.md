## aws-commands
Some most important aws-commands

### Switch a profile
#### in window
```
setx AWS_PROFILE user1
```
#### in mac/linux
```
export AWS_PROFILE=user1
```
### Add a new profile
```
aws configure --profile <profile-name>
```
### List all aws profiles

```
aws configure list-profiles
```
### Show current profile
```
aws configure list
```
### Update existing profile value
```
aws configure --profile <profile-name>
```
### List users of current profile
```
aws iam list-users
```
