# TASK_6-VSD-TAPEOUT
# Inception of open-source EDA, OpenLANE and Sky130 PDK



```bash
cd~/Desktop/work/tools/openlane_working_dir/openlane
```
 **Building PDKs from Source**

```bash
export PDK_ROOT=/home/vsduser/Desktop/work/tools/openlane_working_dir/pdks
cd ~/Desktop/work/tools/openlane_working_dir/openlane
alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'
docker
./flow.tcl -interactive
```

<img width="914" height="584" alt="image" src="https://github.com/user-attachments/assets/88e4f398-1922-4685-b916-1d235cc70b47" />


```bash
package require openlane 0.9
```

```bash
prep -design picorv32a
```
<img width="1217" height="568" alt="Screenshot 2025-10-31 155819" src="https://github.com/user-attachments/assets/def0457b-fce4-42e0-bc0a-d746e7db9e37" />

```bash
run_synthesis
```

<img width="914" height="579" alt="image" src="https://github.com/user-attachments/assets/6154cf91-4549-4a56-9e45-274bff110ea1" />




