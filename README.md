"# mynotebook" 
### **3. 权限管理**

这是 Linux 安全的核心，我们学习了如何查看和修改文件权限。

- **查看权限**：`ls -l`

  - `ls -l my_file.txt`：查看文件的详细权限，输出如 `-rw-r--r--`。
- **修改权限**：`chmod`

  - `chmod u+x my_script.sh`：用符号模式给所有者增加执行权限。
  - `chmod 755 my_script.sh`：用数字模式给所有者读写执行、组和其他人读和执行的权限。
- **修改所有者和组**：`chown`

  - `chown mondy:team_a my_project/`：改变目录的所有者和组。
  - `chown -R mondy:team_a my_project/`：用 `-R` 参数递归地改变目录下所有文件和子目录的所有者和组。

---
