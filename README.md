# CubeMX
Tools to work with STM32CubeMX

## Running STM32CubeMX in command-line mode
- https://www.st.com/resource/en/user_manual/um1718-stm32cubemx-for-stm32-configuration-and-initialization-c-code-generation-stmicroelectronics.pdf
  
```bash
"%STM32CubeMX_PATH%\jre\bin\java" -jar "%STM32CubeMX_PATH%\STM32CubeMX.exe" -i
```
### Open STM32CubeMX
```bash
OpenMx
```

```bash
OpenMx STM32F411CEUx
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

### MX export 
```bash
export script ScriptToLoad.txt
```