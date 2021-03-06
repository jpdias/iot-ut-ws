## Requirements installation

### Base Requirement: 

- [Mingw](https://mingw-w64.org/doku.php). [Install instructions](http://win-builds.org/doku.php). You must at least have G++ or GCC in the path.
- [Git](https://git-scm.com/)

1. Download [Visual Studio Code](https://code.visualstudio.com/) 
2. Install the PlatformIO extension
    - [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide)
3. Create a PlatformIO user account.
    - Allows Remote Serial Port Monitor (10 per month), Remote Firmware Updates (50 per month), Remote Unit Testing (5 per month)
    - A 30-Day trial of PlatformIO Plus is given that allows:
      - Local Unit Testing
      - Local Debugging
4. Ready to go!

## Tutorial

Inspired on [How to test PlatformIO based project - Calculator example](https://github.com/platformio/platformio-examples/tree/develop/unit-testing/calculator).

```bash
# Clone repository
> git clone https://github.com/jpdias/iot-ut-ws.git

# Change directory to example
> cd iot-ut-ws

# Open VS Code
> code .

# Test project
> platformio test

# Test specific environment
> platformio test -e uno

# Process test on native desktop machine
> platformio test -e native
```