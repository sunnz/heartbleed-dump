heartbleed-dump
===============

Extended fork of Jared Stafford's ssltest.py that sets payload length to 65535 bytes and optionally saves the result to a file.

~~~
Usage: heartbleed-dump.py server [options]

Test for SSL heartbeat vulnerability (CVE-2014-0160)

Options:
  -h, --help            show this help message and exit
  -p PORT, --port=PORT  TCP port to test (default: 443)
  -f FILE, --file=FILE  Write result to FILE
~~~
