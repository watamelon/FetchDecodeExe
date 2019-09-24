# FetchDecodeExe
A program written in python through Jupyter Notebook file to simulate the Fetch-Decode-Execute cycle (Sequentially).
![alt text](https://user-images.githubusercontent.com/46073670/65453008-4fbadc80-de10-11e9-828e-0fef81200bfc.jpg)

The program contains two main classes:

ALU (Arithematic Logical Unit):
  ALU holds a dictionary that contains the opcodes:
  >self.operations = { <br/>
            "01" : lambda a, b: self.add(a,b),          #opcode is 01 then it is addition <br/>
            "10" : lambda a, b: self.subtract(a,b)      #opcode is 10 then it is subtraction <br/>
       }
       
  The add and subtract functions are dedicated to calculate in binary.
  Subtract function utilizes the two complement system for negative number.
  
  
  
  
