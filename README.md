# tdlib-php

## Project Status

Work in progress, not ready for use.

License: BSD3

## Notes

For best results, a patched tdlib at https://github.com/telegram-gate/tdlib should be used instead of the official https://github.com/tdlib/td .

## HTTP API Reference

 * http://127.0.0.1:12222/?request=set_log_verbosity_level&level=3 — level is an int, it can be either 0 for quiet, or 3 for verbose.

 * http://127.0.0.1:12222/?request=poll — works; to also be accompanied with callbacks from tdlib to php cli executable with user-specified php script; to be done.

 * http://127.0.0.1:12222/?request=send&request_json={%22@extra%22:5,%22@type%22:%22sendMessage%22}
