**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/e473a140-1f6c-4557-9e16-221725b2e603)

****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/2c164370-9e47-4a86-b416-ede54deab4c7)

**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**
![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/6da12fd0-c238-4806-901c-24e3bd2a02ad)


**Step 5: Check the output by using the command**

**./a.out**
![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/549b3775-7638-47c7-a135-d36e8dd5a3d1)

**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/b30af5cd-ea1f-4667-84b6-57f71d44d483)


**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
!![Screenshot from 2024-02-27 17-22-15](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/5726bbc4-625e-473a-b9ec-a4c12e8bf8b2)

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![Screenshot from 2024-02-27 18-14-26 - 5 (1)](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/cb1c80db-57c7-4fff-b488-e6bf50d8bd03)



![Screenshot from 2024-02-27 17-11-10](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/5ebfc26f-e9a0-46df-869b-ae924515d52c)

**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![WhatsApp Image 2024-02-27 at 5 14 45 PM (1)](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/3f369444-adb0-43e8-a701-a83cb7bfc204)

![WhatsApp Image 2024-02-27 at 5 15 06 PM](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/0ee66ed8-9286-4a39-8b15-0ce59f350ea5)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![WhatsApp Image 2024-02-27 at 5 15 41 PM](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/8fdce908-e959-474f-9083-84301a242828)



![WhatsApp Image 2024-02-27 at 5 15 54 PM](https://github.com/IndhumathiMadival/VSDSquadron/assets/160833467/38a75985-8062-493a-b360-437cf2ab1d24)


