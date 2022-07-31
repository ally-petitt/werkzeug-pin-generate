## Python script to generate valid pin to access Werkzeug debug console

The following pieces of information are needed:


* `username` is the user who started this Flask
* `modname` is flask.app
* `getattr(app, '__name__', getattr (app .__ class__, '__name__'))` is Flask
* `getattr(mod, '__file__', None)` is the absolute path of an app.py in the flask directory
* `uuid.getnode()` is the MAC address of the current computer, str (uuid.getnode ()) is the decimal expression of the mac address
* `get_machine_id()` read the value in /etc/machine-id or /proc/sys/kernel/random/boot_i and return directly if there is

To get the MAC Address and Machine ID, some form of local file inclusion (LFI) is usually required.

Instructions on the full exploit is here https://www.daehee.com/werkzeug-console-pin-exploit/
Make sure to replace the hard-coded values in the script.
