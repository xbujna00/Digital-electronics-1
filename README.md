# Digital-electronics-1
## Lab 1
### <i> De Morgan's Laws simulations <i>
#### <b> xbujna00 <b>
    

**Source code**

```VHDL
architecture dataflow of gates is
begin
    f_o  <= ((not b_i) and a_i) or ((not c_i) and (not b_i));
    fnand_o <= ((b_i nand b_i) nand (a_i)) nand ((c_i nand c_i) nand (b_i nand b_i));
    fnor_o <= not((b_i nor (a_i nor a_i)) nor (c_i nor b_i));

end architecture dataflow;

```
