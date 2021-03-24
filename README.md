
run 

packer.exe build netinstalldebian10.json


for creating hyper-v virtual machine


for debug 

set PACKER_LOG=10
set PACKER_LOG_PATH=d:\packer-hyper-v-debian10-builder\packer.log
packer.exe build -debug netinstalldebian10.json