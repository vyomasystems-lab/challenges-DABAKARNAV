# Multiplexer Design Verification
The verification environment is setup using [Vyoma's UpTickPro](https://vyomasystems.com/) provided for the hackathon.
![CTB_L1D1_I1](https://user-images.githubusercontent.com/55938415/181187758-908c5788-d2a2-4246-9988-58d2392f4f27.PNG)
## Verification Environment
The [CoCoTb](https://www.cocotb.org/) based Python test is developed as explained. The test drives inputs to the Design Under Test (multiplexer module here) which is 31:1 Multiplexer having a 5 bit select line.  
Below are Inputs and Outputs used for this test.  
input line:: inp0  
select line:: sel   
out::output line.  
The values are assigned to the input port using
    
    ``` python
    A=1
    B=3
    dut.sel.value=A
    dut.inp0.value=B
    ```
    
