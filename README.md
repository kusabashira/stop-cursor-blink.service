stop-cursor-blink.service
=========================

Stop cursor blink on virtual console.

Installation
------------

```sh
sudo wget https://raw.github.com/kusabashira/stop-cursor-blink.service/master/stop-cursor-blink.service -O /systemd/system/stop-cursor-blink.service
sudo systemctl start stop-cursor-blink
sudo systemctl enable stop-cursor-blink
```

License
-------

MIT License

Author
------

kusabashira <kusabashira227@gmail.com>
