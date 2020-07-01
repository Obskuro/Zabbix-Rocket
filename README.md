# Zabbix-Rocket

This guide describes how to send notifications from Zabbix 5.0 to the RocketChat by Zabbix webhook feature.

## RocketChat setup

Create a new channel in RocketChat and copy the token

## Zabbix setup

1\. In the "Administration > Media types" section, import the media_rocket.xml.  
2\. Configure the added media type:  
Copy and paste your RocketChat url into the "url" field.  
3\.To receive notifications in RocketChat channel, you need to create a Zabbix user and add Media with the Rocket type.  
In the "Send to" field enter RocketChat channel webhook.

## Links

This template and description is based on that template and description: [Telegram webhook](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse/templates/media/telegram)

## License

This project is licensed under the Beer-ware license revision 42
