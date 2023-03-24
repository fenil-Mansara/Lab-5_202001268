# Lab-5_202001268
### Name - **Fenil Manara**<br>
### ID : **202001268**<br>
### Date - **24-03-2023**<br><br>

### Static Analysis:<br>
Static analysis is a method of examining the source code of a software program without
executing it. Static analysis can help detect errors, bugs, vulnerabilities, and other quality issues
in the code. Static analysis tools can perform various tasks such as checking syntax, style,
logic, data flow, control flow, and security. Static analysis can improve the reliability,
performance, and maintainability of software by identifying and correcting defects early in the
development process.<br><br>
### Static Analysis Tools:<br>
Static analysis tools are software tools that analyze the source code of a program without
executing it. They can help developers find and fix errors, bugs, vulnerabilities, code smells, and
other quality issues in their code. Static analysis tools can also measure various metrics of the
code, such as complexity, readability, maintainability, test coverage, and documentation. Static
analysis tools can be integrated into the development process as part of the code editor, the
version control system, or the continuous integration pipeline.
<br><br>
### For this lab we used Static Analysis Tools : **Mypy**<br>
 **[1]** First we installed Mypy in our system : <br>

![image](https://user-images.githubusercontent.com/84991028/227472132-71ddc530-776b-4f58-90d8-21eabbd4ba0b.png)
<br>

**[2]** We can get repo analysis by Mypy command : **"-m mypy `<path-of-repo-or-file>`"**<br>
### Github repo link : `github.com/geekcomputers/Python`
![image](https://user-images.githubusercontent.com/84991028/227472022-595608c0-209d-4b8b-a465-e085cf9e0d94.png)<br>
**Error** : [Import] **Library stub not installed is error** for not installing required python libraries which is vary for all systems whereas it is installed or not.<br>
**Error** : [Import] **Skipped analyzing "lib_name"** due to library for that part is not installed.<br>
![image](https://user-images.githubusercontent.com/84991028/227476818-1ff899f5-022a-4c3b-8edc-67a041fab046.png)
**Error** : [Valid-Type] **Function "Func_name" is not as valid type** is would be due to wrong return type.<br>
**Error** : [Operator] **Unsupported operand type for unary - (np.array?)"** is due to wrong use of operators.<br>
![image](https://user-images.githubusercontent.com/84991028/227472246-32647a60-17f4-42ff-9ea0-1e189737d040.png)<br>
**Error** :  **Duplicate module named "main"** (also at "Python_master_3\Python-master\Extract-Table-from-pdf-txt-docx\main.py") is due to duplicate main modules.<br>

**[3]** Mypy can only analysis errors for Python language, other languages are not supported for this tools.<br><br>
![image](https://user-images.githubusercontent.com/84991028/227472943-db44415f-cc2c-43bb-bd47-0799f0429056.png)<br>


