
# Log4j Payloads

A collection of log4j payloads spotted in the wild.

I had to redact some values but did my best to make it clear in the payloads via the following flags:

1. !!IP_ADDRESS!!: A redacted IP address of the honeypot.
2. !!BASE64_VALUE!!: A base64 encoded value which contained the IP address of the honeypot.
    - I added the decoded payload with the IP address of the honeypot redacted.

Used the following honeypot: [log4j_catcher](https://github.com/entropyQueen/log4j_catcher)

# Credits

[entropyQueen](https://github.com/entropyQueen): developer of the honeypot.
