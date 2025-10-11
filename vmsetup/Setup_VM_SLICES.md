1. Go to https://doc.slices-ri.eu/SupportingServices/getanaccount.html and follow the instructions to get a SLICES-RI account
2. After loggin in, join the project oai-rfsim-training here https://portal.slices-ri.eu/invite/oai-rfsim-training?key=zcYD9sm19clpH6vJ
3. Install the SLICES Command Line Interface (CLI) following these instructions: https://doc.slices-ri.eu/SupportingServices/slicescli.html
4. Make sure that you have uploaded your public ssh key and that you joined the project oai-rfsim-training
5. Create your virtual machine
```
export SLICES_BI_SITE_ID=be-gent1-bi-vm1
export SLICES_EXPERIMENT=debug4
slices bi create oai-vm --duration 2h --image "Ubuntu 24.04.1" --flavor medium
```
6. Login to your virtual machine
```
slices bi ssh florian-vm
```
