# MyScriptOS
MyScript OS for the Raspberry Pi - with everything you need!

## Build instuctions
1. Download the current Raspberry Pi OS (the `.zip` file) from [here](http://downloads.raspberrypi.org/raspios_lite_armhf/images)
1. Copy it to `MyScriptOS/src/image`
1. Start the docker container with `docker-compose up -d`
1. Build the image using `docker-compose exec custompios build`

## Help
> I get weird errors that commands are not found

Make sure that all the files have `LF` line endings and not `CRLF`