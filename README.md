Use these templates for debugging STM32 with ccortex-debug and CubeIDE extensions, all within VSCode.

1. To get started, install the necessary extensions (STM32 CubeIDE for VSCode and cortex-debug) and CMake.
2. Generate the project in CubeMX with the toolchain as CMake.
3. Open the folder n VSCode and go to STM32 tab and click setup STM32 project while the st-link and MCU are connected (make sure you have drivers installed)
4. CLick finish with the correct MCU selected.
5. Write the code and paste the template files in the vscode folder or just copy ad paste the vscode folder into there if there  isn't one already
6. Edit the files as per requirements (just tell copilot to do it)
7. Go to run and debug tab and click the Debug (Cortex-Debug)
8. You can now debug with accurate register control and access in VSCode and many more features. see cortex-debug docs for more info.
\n
Next time, just paste these files and debug peacefully! (actually, debugging is not very peaceful)
