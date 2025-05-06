# CubeMX
Tools to work with STM32CubeMX

## Running STM32CubeMX in command-line mode
- https://www.st.com/resource/en/user_manual/um1718-stm32cubemx-for-stm32-configuration-and-initialization-c-code-generation-stmicroelectronics.pdf

To run STM32CubeMX in interactive command-line mode, use the following command line:
```bash
"%STM32CubeMX_PATH%\jre\bin\java" -jar "%STM32CubeMX_PATH%\STM32CubeMX.exe" -i
```

To run STM32CubeMX in command-line mode, getting commands from a script, use the following command line:
```bash
"%STM32CubeMX_PATH%\jre\bin\java" -jar "%STM32CubeMX_PATH%\STM32CubeMX.exe" -s ScriptToLoad.txt
```

To run STM32CubeMX in command-line mode getting commands from a script and without UI, use the following command line:
```bash
"%STM32CubeMX_PATH%\jre\bin\java" -jar "%STM32CubeMX_PATH%\STM32CubeMX.exe" -q ScriptToLoad.txt
```

To generate a script
```bash
export script ScriptToLoad.txt
```

### Open STM32CubeMX
```bash
OpenMX
```

```bash
OpenMX STM32F411CEUx
```

### Load STM32CubeMX Script
Load default values
```bash
LoadMX
```
Load with Project Name
```bash
LoadMX ProjectName
```
Load with Project Name and Script Name
```bash
LoadMX ProjectName ScriptName.txt
```
Load with Project Name, Script Name and generate code
```bash
LoadMX ProjectName ScriptName.txt Y
``` 
