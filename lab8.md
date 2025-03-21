**Experiment**
Write shell scripts to print system information. Write shell script to perform basic mathematical calculation. Use redirection operators to store the output of commands.

command to be used

#!/bin/bash

    echo "System Information Report"
    
    echo "========================="
    
    echo "Hostname: $(hostname)"
    
    echo "Operating System: $(uname -o)"
    
    echo "Kernel Version: $(uname -r)"
    
    echo "Uptime: $(uptime -p)"


    #!/bin/bash
    
echo "Enter first number: "

read num1

echo "Enter second number: "

read num2

    echo "Mathematical Operations"
    
    echo "======================="
    
    echo "Addition: $((num1 + num2))"
    
    echo "Subtraction: $((num1 - num2))"
    
    echo "Multiplication: $((num1 * num2))"
    
    echo "Division: $(echo "scale=2; $num1 / $num2" | bc)"


    nano redirection.sh
    
    touch file.txt
    
    bash redirection.sh
    
    bash file.txt
  






![Screenshot_from_2025-03-18_14-40-28 1](https://github.com/user-attachments/assets/c3085336-2b0b-46ac-b3b7-3d116585ba90)

![Screenshot_from_2025-03-18_14-39-25 1](https://github.com/user-attachments/assets/aa0ef275-ea23-49b1-b20a-02b9efc1bb03)

![Screenshot_from_2025-03-18_14-50-37 1](https://github.com/user-attachments/assets/c45513de-f880-48cf-b5e7-c44f04f23f5d)

![Screenshot_from_2025-03-18_15-14-50 1](https://github.com/user-attachments/assets/949dd837-3568-481a-a96a-e0aa3c2f7168)


