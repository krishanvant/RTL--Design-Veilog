![120019036-93aead80-c005-11eb-8d90-11b52d5f81e1](https://user-images.githubusercontent.com/86395960/123552040-faa0bd00-d791-11eb-927d-f6c79c09c8c9.png)
# RTL-Design-Veilog

5 days workshop on RTL Design using Open_lane_sky130

**-   Day1 Introduction to verilog RTL Design and Synthesis**

Lab Insight
* Create a directory lets say vlsi in workspace
* Clone all the files from  https://github.com/kunalg123?tab=repositories
*  Once we are done with the cloning
*  In the vlsi directory we will get sky130RTLDesignAndSynthesisWorkshop folder

  ![Screenshot (5)](https://user-images.githubusercontent.com/86395960/123552676-c7abf880-d794-11eb-90f1-ff5566829609.png)

* with the help of "ls" command we can see there will be two folders and yosys setup

  ![Screenshot (7)](https://user-images.githubusercontent.com/86395960/123552845-c3cca600-d795-11eb-91c4-14400d478436.png)

* Now the **-iverilog based simulation flow is as followed**

   ![Screenshot (8)](https://user-images.githubusercontent.com/86395960/123552924-3473c280-d796-11eb-9709-6a97750b858a.png)

* Now we will move to the **verilog_files** which contain all the design files and the test bench 

   ![Screenshot (9)](https://user-images.githubusercontent.com/86395960/123553254-c92af000-d797-11eb-9bcc-0d04c3a7c48f.png)

* now we invoke iverilog and give .v file and test bench as an input using command **iverilog good_mux.v tb_good_mux.v**
* a.out file is created we will execute it using command **./a.out**
* now the vcd file is dumped
* now we will invoke gtkwave by giving vcd file as an input **gtkwave tb_good_mux.vcd**

   ![Screenshot (10)](https://user-images.githubusercontent.com/86395960/123553653-22941e80-d79a-11eb-9c54-73244be9b7df.png)

* we can open the code vim editor using command **tb_good_mux.v -o good_mux.v**

![Screenshot (12)](https://user-images.githubusercontent.com/86395960/123553878-2f654200-d79b-11eb-97c3-52a69a601f78.png)






