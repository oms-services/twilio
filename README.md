# _Twilio_ OMG Microservice

[![Open Microservice Guide](https://img.shields.io/badge/OMG%20Enabled-👍-green.svg?)](https://microservice.guide)
[![Build Status](https://travis-ci.com/omg-services/uuid.svg?branch=master)](https://travis-ci.com/omg-services/uuid)
[![codecov](https://codecov.io/gh/omg-services/uuid/branch/master/graph/badge.svg)](https://codecov.io/gh/omg-services/uuid)

This container adds Twilio support in a microservice.

## Direct usage in [Storyscript](https://storyscript.io/):

##### SMS
```coffee
twilio sms to: '+1xxx' from: '+1xxx' body: 'Hello world!'
```

Curious to [learn more](https://docs.storyscript.io/)?

✨🍰✨

## Usage with [OMG CLI](https://www.npmjs.com/package/omg)

##### SMS
```shell
$ omg run sms -a to=<PHONE_NUMBER> -a from=<PHONE_NUMBER> -a body=<MESSAGE_BODY> -e ACCOUNT_SID=<ACCOUNT_SID> -e AUTH_TOKEN=<AUTH_TOKEN>
```

**Note**: The OMG CLI requires [Docker](https://docs.docker.com/install/) to be installed.

## License
[MIT License](https://github.com/omg-services/twilio/blob/master/LICENSE).
