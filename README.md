# snapshotalyzer-30000

Demo project to manage AWS EC2 instance snapshots

##About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration filed created bythe AWS cli. e.g.

'aws configure --profile shotty'

## Running

'pipenv run shotty/shotty.py <command> <subcomman> <--project=PROJECT>'

*command* is instances, volumes, or snapshots
*subcommand* depends on command
*project* is optional
