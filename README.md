# ansible-sensu

This is my first try at a series of Ansible roles for deploying a Sensu server and a client with some auto discovered features.

The project currently has the following downsides:
- No encryption for the RabbitMQ backend
- Autodiscovery is based on open ports on the system and nothing else
- Check set isn't very broad and nothing has been finetuned
