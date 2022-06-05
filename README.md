# Wheatleaf

### The in-browser wayland compositor

- Website: https://theawesome98-real.github.io/wheatleaf/

Wheatleaf is a [Wayland compositor](https://en.wikipedia.org/wiki/Wayland_%28display_server_protocol%29) written in JavaScript and uses WebGL to show the windows in your browser. Unlike [Greenfield](https://github.com/udevbe/greenfield), Wheatleaf does not use WebSockets. Instead, it runs programs in the browser and sends the window stack to Wheatleaf to render onto the canvas.

Wheatleaf uses [Westfield](https://github.com/udevbe/westfield) instead of wayland-protocols, and [Browsix](https://browsix.org/) to provide a Unix environment to processes.
