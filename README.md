# 区别
  
  虽然 DOS 命令和 Linux 命令都是用于在命令行环境下执行操作的命令，但它们并不是通用的。这是因为 DOS 和 Linux 是两个不同的操作系统，它们的设计和架构不同，所以它们的   命令也不同。
  例如，DOS 使用不同的文件路径分隔符（反斜杠 \）和命令行选项前缀（斜杠 /），而 Linux 使用正斜杠 / 作为路径分隔符和短横线 - 作为命令行选项前缀。此外，DOS 命令和     Linux 命令的语法和参数也有所不同。
  因此，如果你在 Linux 系统上使用 DOS 命令，或者在 DOS 系统上使用 Linux 命令，很可能会遇到错误或无法识别的命令。

## DOS
  
  dir：列出当前目录中的文件和子目录。

  cd：更改当前目录。例如，cd C:\Windows 将当前目录更改为 C:\Windows。

  md：创建一个新目录。例如，md MyFolder 将在当前目录中创建一个名为 MyFolder 的新目录。

  del：删除一个文件。例如，del MyFile.txt 将删除当前目录中名为 MyFile.txt 的文件。

  copy：复制一个或多个文件。例如，copy MyFile.txt C:\Backup 将在 C:\Backup 中创建一个名为 MyFile.txt 的副本。

  xcopy：复制一个目录及其所有子目录和文件。例如，xcopy C:\MyFolder D:\Backup /s /e 将在 D:\Backup 中创建一个名为 MyFolder 的副本，包括所有子目录和文件。

  ren：重命名一个文件或目录。例如，ren MyFile.txt YourFile.txt 将名为 MyFile.txt 的文件重命名为 YourFile.txt。

  type：显示一个文件的内容。例如，type MyFile.txt 将在屏幕上显示名为 MyFile.txt 的文件的内容。

  cls：清除屏幕上的所有文本。

  exit：退出命令提示符窗口。
  
  
## Linux

  ls：列出当前目录中的文件和子目录。

  cd：更改当前目录。例如，cd /usr/local/bin 将当前目录更改为 /usr/local/bin。

  mkdir：创建一个新目录。例如，mkdir MyFolder 将在当前目录中创建一个名为 MyFolder 的新目录。

  rm：删除一个文件或目录。例如，rm MyFile.txt 将删除当前目录中名为 MyFile.txt 的文件，rm -r MyFolder 将删除当前目录中名为 MyFolder 的目录及其所有子目录和文件。rm -rf 删除不为空的文件夹。

  cp：复制一个或多个文件。例如，cp MyFile.txt /backup 将在 /backup 中创建一个名为 MyFile.txt 的副本。

  mv：移动或重命名一个文件或目录。例如，mv MyFile.txt YourFile.txt 将名为 MyFile.txt 的文件重命名为 YourFile.txt，mv MyFile.txt /backup 将 MyFile.txt 移动到 /backup 目录中。

  cat：显示一个文件的内容。例如，cat MyFile.txt 将在屏幕上显示名为 MyFile.txt 的文件的内容。

  clear：清除屏幕上的所有文本。

  exit：退出当前终端窗口。
