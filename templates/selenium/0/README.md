# Selenium Grid

## Info

This template creates a Selenium Grid with two nodes connected : a Firefox and a Chrome.

## Usage

Choose the Selenium's port you want to expose (in order to connect from remote locations) and the domain used by [Traefik](traefik.github.io).

Console will be accessible at [selenium.${DOMAIN}/grid/console](selenium.localhost/grid/console)

Hub will be accessible at [docker_host_ip_or_domain:${SELENIUM_PORT}/wd/hub](docker_host_ip_or_domain:${SELENIUM_PORT}/wd/hub)
