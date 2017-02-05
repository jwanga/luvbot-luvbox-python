# Luvbot Luvbox

The Luvbot Luvbox is a device that sends an SMS alert to a specified number when
activated. The response to that SMS is printed on a thermal printer. It's a
simple way to stay connected, or deeply annoy, a loved one.

This repo is a python twilio client for the Arduino Yun onboard linux computer.
It's responsible for sending and receiving SMS messages and interfacing with the
Arduino sketch containing the thermal printer, button and led code.

## Installation

Clone this project to your computer, create a "configuration.py" file containing
the following:

```python
twilio_account_sid = xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
twilio_auth_token = xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
twilio_phone_number = xxxxxxxxxxxx
target_phone_number = xxxxxxxxxxxx
phone
```

Then copy "configuration.py" and "luvbot.py" to your Arduino Yun.


## Usage

From your Arduino Yun, run the following:

```sh
python luvbot.py
```

## Support

Please [open an issue](https://github.com/jwanga/luvbot-luvbox-python/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/jwanga/luvbot-luvbox-python/compare/).
