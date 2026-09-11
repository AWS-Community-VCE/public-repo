# public-repo


## SSH URI
```sh
ssh -i "demo.pem" workshop@ec2-204-236-198-113.compute-1.amazonaws.com
```


## Meetup link:
```sh
https://www.meetup.com/aws-sbg-at-vasavi-college-of-engineering/events/316499654/?utm_medium=referral&utm_campaign=share-btn_savedevents_share_modal&utm_source=link&utm_version=v2&member_id=480811527
```

## Fix pem file restrictions

```sh
icacls demo.pem /inheritance:r /grant:r "%USERNAME%:R" /remove "Users" "Authenticated Users" "Everyone"
```

