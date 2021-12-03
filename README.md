# Pi Site

Pi Site is a simple website used as a playground for testing Raspberry Pi as a webserver.

The backstory on this project is that I had an old Raspberry Pi Model B laying around collecting dust, and I decided to put it to some use experimenting with making it a webserver.
In its current iteration the project is a simple HTML webpage using CSS Grid for layout, and is being served over HTTPS with NGINX and Let's Encrypt.

## Tech in use

### Hardware

- [Raspberry Pi Model B Rev 2](https://www.raspberrypi.com/products/raspberry-pi-2-model-b/)

### Software

- [NGINX](https://www.nginx.com/resources/wiki/start/) used as the webserver.
- [Certbot](https://github.com/certbot/certbot) used to manage HTTPS with Let's Encrypt
