# tix-time-stress-test
This repository contains the stuff needed for the stress-test for the tix-time-service

## How to make it work (so far)

1. Download Apache JMeter v3.2
2. Compile the `tix-time-client` using the comand `./gradlew jfxRun` and cut the execution
3. Copy the files from the `tix-time-client` directory under the path `build/jfx/app` to the path `lib/` in the Apache JMeter directory. This will enable to use the `tix-time-client` classes.
4. Load in Apache JMeter the test description in this repository.
5. ????
6. PROFIT!

