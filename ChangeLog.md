Changes
--------------------------------------------------------------------------------

0.0.3 (2012/6/21)
================================================================================

- Upgraded to work with onstomp 1.0.7
- Fix unsubscribe to accept array of frames that subscribe returns

0.0.2 (2012/06/15)
================================================================================

- Add `:logger` option to log sending and receiving of messages
- Duck-type with `#to_json` for `:translate_json` option
- Clean up options parsing, pass all options through to OnStomp client config
- Clamp onstomp gem dependency version to 1.0.x

0.0.1 (2012/06/08)
================================================================================

- Initial release