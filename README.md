# RSA-HARDWARE-ACCELERATOR

* RSA/doc - contains documentation describing the work done
* RSA/high_level_model/src - contains source code for high level model developed for this project
* RSA/RSA_Accelerator/Pynq-Z1-integration-kit/Bitfiles - contains bitfiles obtained by synthesizing the design for Pynq Z1 FPGA board
* RSA/RSA_Accelerator/Pynq-Z1-integration-kit/Exponentiation  - contains VHDL source code for module that implements modular exponentiaiton
* RSA/RSA_Accelerator/Pynq-Z1-integration-kit/RSA_accelerator - contains VHDL source code for module that implements RSA by instantiating modular exponentiaiton 
* RSA/RSA_Accelerator/Pynq-Z1-integration-kit/RSA_soc - contains VHDL source code for modules that connects the accelerator to ARM processor running on Pynq Z1 FPGA
* RSA/RSA_Accelerator/Pynq-Z1-integration-kit/Reports - contains information about timing and resource utilizaton
