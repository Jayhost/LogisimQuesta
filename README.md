This is essential a drive link to a condensed ModelSim setup for using with Logisim Evolution for simulating VHDL

With modelsim_ase on windows you want to point Logisim Evolution in Preferences to 

Software -> Questa Advanced Simulator Path -> /modelsim_ase/win32aloem (or on linux /linuxaloem)

On Linux Logisim requires libncurses.5.so 32 bit. On my Fedora `dnf provides */libncurses.so.5` shows 
`dnf install ncurses-compat-libs.i686` is what provides this. Should be similar on other systems.

![image](https://github.com/user-attachments/assets/fb4ad5d4-c277-4dce-9815-7a4288b07078)


![image](https://github.com/user-attachments/assets/e055cab3-538b-42b2-9551-e54ad9105fac)

