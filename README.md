# T_FLIPFLOP
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/74140ea2-0b93-4ffc-b38b-527fb2ece133)
# Truth Table
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/1d4afa40-166a-4690-ab1a-179948b9b550)

# Program
module T(clk,reset,t,q);

input clk,reset,t;

output reg q;

always @(posedge clk)

begin

if(reset==1)

q=0;

else

begin

if(t==0)

q=q;

else

q=~q;

end

end

endmodule

# Output

![Screenshot 2024-04-13 013000](https://github.com/Shaiksushma123/T_FLIPFLOP/assets/159005642/86c9df12-85fa-4297-9e59-1b63af0d2a4b)
