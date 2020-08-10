# Sample and Hold Block
This repository will maintain simulation files and other relevant files on the Sample and Hold Circuitry worked on in the VSD Online Internship 2020
## BLOCK DIAGRAM OF SAMPLE AND HOLD CIRCUIT
<p align="center">
  <img width="800" height="500" src="/pre-layout/block.png">
</p>

## CIRCUIT DIAGRAM OF SAMLE AND HOLD
<p align="center">
  <img width="800" height="500" src="/pre-layout/circuit.png">
</p>


## About Ngspice 
Ngspice is an open source mixed-signal circuit simulator.

### Installing Ngspice

#### For Ubuntu

Open your terminal and type the following to install Ngspice
```
$  sudo apt-get install -y ngspice
```

## Running the Simulation


To enter the Ngspice Shell, open the terminal & type:
```
$ ngspice
```
To simulate a netlist, type:
```
ngspice 1 ->  source <filename>.cir
```

You can exit from the Ngspice Shell by typing:
```
ngspice 1 ->  exit
```
 <p align="center"> or </p>
 
```
ngspice 1 ->  quit
```
### Pre-Layout Simulation

To clone the Repository and download the Netlist files for Simulation, enter the following commands in your terminal.

```
$  sudo apt install -y git
$  git clone https://github.com/uday2012/sample_hold
$  cd sample_hold/pre-layout
```
Run the netlist file using the following command.
```
$  ngspice sample_hold.cir
```


<p align="center">
 <img width="800" height="500" src="/pre-layout/clock.png">
</p>
<p align="center">
<img width="800" height="500" src="/pre-layout/sample.png">
</p>

## Acknowledgments
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.
- Philipp Gühring, Software Architect, LibreSilicon Assocation


## Contact Information

- Uday Vempalli, Undergraduate Student,Siddhartha Institute Of Technology,udayvempalli99@gmail.com
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com
- Philipp Gühring, Software Architect, LibreSilicon Assocation pg@futureware.at
