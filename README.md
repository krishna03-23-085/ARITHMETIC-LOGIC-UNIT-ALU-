# ARITHMETIC-LOGIC-UNIT-ALU-

*COMPANY*: CODTECH IT SOLUTIONS  

*NAME*: KRISHNA SINGH  

*INTERN ID*: CT04DR278 

*DOMAIN*: VLSI 

*DURATION*: 4 WEEKS  

*MENTOR*: NEELA SANTOSH  

##Description of Tools, Platforms, and Technologies Used

For completing the design and simulation of the Arithmetic Logic Unit (ALU), I used a combination of online simulation platforms and digital design tools that support Verilog HDL (Hardware Description Language). The main tool utilized was EDA Playground, an online web-based simulator, along with the Icarus Verilog simulation engine. These tools allowed me to design, test, and verify the ALU operations without requiring complex local installations. Below is a detailed explanation of each component and how it was used in the project.

EDA Playground is a powerful, browser-based integrated development environment (IDE) specifically designed for electronic design automation (EDA) tasks. It allows users to write, compile, and simulate Verilog, SystemVerilog, and VHDL code directly in the web browser. The platform supports multiple simulation engines such as Icarus Verilog, Aldec Riviera-PRO, Siemens Questa, Synopsys VCS, and more. One of the main advantages of EDA Playground is that it eliminates the need to install heavy simulation software locally. The entire workflow—coding, compiling, running simulations, and viewing waveforms—can be performed online in a very interactive and easy-to-use interface.

During my task, I selected Verilog as the primary language in EDA Playground and chose Icarus Verilog 12.0 as the simulation tool. Icarus Verilog is a widely used open-source Verilog simulation and synthesis tool that supports all standard Verilog constructs. It is known for its simplicity, fast performance, and compatibility with waveform visualization tools like EPWave or GTKWave. In EDA Playground, after choosing Icarus Verilog, I pasted my ALU design code in the “Design” section and the testbench code in the “Testbench” section. The testbench was written to apply various input combinations and ALU control signals to verify all the arithmetic and logic operations of the ALU module, including addition, subtraction, AND, OR, and NOT.

Once the code was entered, I clicked the “Run” button to compile and execute the simulation. EDA Playground uses Icarus Verilog on its backend to compile the design and produce output data. The results of the simulation appear in the console window, showing the monitored output values for each operation. Additionally, EDA Playground provides an EPWave waveform viewer, which graphically represents how signals change over time. This waveform display is critical in hardware design, as it allows verification of the timing and logical behavior of signals in response to different operations.

Apart from EDA Playground, I also reviewed ModelSim and Quartus Prime tools, which are professional-grade software used for FPGA and ASIC simulation. These are desktop-based environments that support Verilog and VHDL projects. While ModelSim provides advanced debugging features and accurate timing analysis, I chose EDA Playground for this task due to its speed, simplicity, and accessibility from any device with an internet connection. The online approach is especially useful for academic projects, small digital design tasks, and verification assignments like this ALU simulation.

The ALU was tested with 8-bit input operands (A and B) and a 3-bit control input (ALU_Sel) to select different operations. The results were observed both in textual form and as waveform outputs. This process helped in understanding how logical and arithmetic functions are implemented in hardware at a structural level using Verilog.

In summary, the primary tools used—EDA Playground and Icarus Verilog—provided a seamless, efficient, and beginner-friendly environment to design and simulate the ALU circuit. These tools offered all necessary functionalities to write Verilog code, execute simulations, view timing diagrams, and verify results without any software installation. This approach made the project execution faster, more accessible, and ideal for demonstrating fundamental digital design concepts in a practical and visual way.

#Output

<img width="1226" height="762" alt="Image" src="https://github.com/user-attachments/assets/1cb82d65-c86c-4abc-9e98-721819c128cc" />
