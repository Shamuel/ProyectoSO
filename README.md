# ProyectoSO

Instrucciones para iniciar proyecto

```
git clone https://github.com/Shamuel/ProyectoSO/
sudo -s
apt install python3-mpi4py
echo 'btl_base_warn_component_unused = 0' > /etc/openmpi/openmpi-mca-params.conf 
exit
cd ProyectoSO
mpirun -n 20 python3 mpi4.py
```
