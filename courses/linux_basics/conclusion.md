# 小結

我們描述了有關 Linux 作業系統以及其上的一些基礎以及管理用的指令。

希望這個課程可以讓讀者之後在操作命令列的時候，感覺可以更輕鬆。

## SRE 角色的各種面向
1. 作為一位 SRE，你會被要求在 Linux 伺服器上執行許多日常作業，也會需要利用命令列來偵錯以及解決問題。
1. As a SRE, you will be required to perform some general tasks on these linux servers. You will also be using the command line when you are troubleshooting issues.
2. 在檔案系統之間移動檔案會需要用到指令 ls, pwd 以及 cd。
2. Moving from one location to another in the filesystem will require the help of ls, pwd and cd commands
3. 你將會需要在紀錄檔中找尋特定的資訊，指令 grep 在此時會相當有用。輸出入重定向在你需要儲存輸出到檔案，或是將它作為另一格指令的粗入時，是個很方便的功能。
3. You may need to search some specific information in the log files. Grep command would be very useful here. I/O redirection will become handy if you want to store the output in a file or pass it as an input to another command.
4. 指令 tail 在觀察檔案的最新紀錄時相當有用。
4. Tail command is very useful to view the latest data in the log file.
5. 不同的使用者會基於他們的角色，而有不同的權限。基於安全性，我們不會希望在公司的每個人都可以存取伺服器的所有檔案，可以使用指令 chown, chmod 以及 chgrp 來限制使用者的權限。
5. Different users will have different permissions depending on their roles. We will also not want everyone in the company to access our servers for security reasons. Users permissions can be restricted with chown, chmod and chgrp commands.
6. SRE 最常使用到的指令莫過於 ssh 了，登入伺服器以執行故障排除動作，以及執行基本管理任務，這些都要在可以登入主機的前提才得以執行。
6. SSH is one of the most frequently used commands for a SRE. Logging into servers and troubleshooting along with performing basic administration tasks will only be possible if we are able to login into the server.
7. 想要跑 apache 或是 nginx 伺服器？這些伺服器需要使用套件管理程式來安裝，套件管理的指令這時候就很重要了。
7. What if we want to run an apache server or nginx on a server ? We will first install it using the package manager. Package management commands become important here.
8. 管理伺服器上的服務是 SRE 的另一個重要工作，跟系統有關的指令可以協助你做故障排除，當服務有問題的時候，可以利用 systemctl 指令來啟動，或是在不需要服務的時候停止它。
8. Managing services on servers is another critical responsibility of a SRE. Systemd related commands can help in troubleshooting issues. If a service goes down, we can start it using systemctl start command. We can also stop a service in case it is not needed.
9. 監控是 SRE 另一個重要的職務，CPU 跟記憶體是兩個需要監控的重要系統指標，指令 top 或是 free 對監控這兩個指標很有幫助。
9. Monitoring is another core responsibility of a SRE. Memory and CPU are two important system level metrics which should be monitored. Commands like top and free are quite helpful here.
10. 如果服務拋出了錯誤，要如何才能找到問題的根源？必須檢查紀錄檔，看裡面是否有紀下為何會出錯的過程，紀錄檔也會有這個錯誤總共出現幾次的詳細資料。
10. If a service is throwing an error, how do we find out the root cause of the error ? We will certainly need to check logs to find out the whole stack trace of the error. The log file will also tell us the number of times the error has occurred along with time when it started.

## 有用的課程或是教學連結

* [Edx basic linux commands course](https://courses.edx.org/courses/course-v1:LinuxFoundationX+LFS101x+1T2020/course/)
* [Edx Red Hat Enterprise Linux Course](https://courses.edx.org/courses/course-v1:RedHat+RH066x+2T2017/course/)
* [https://linuxcommand.org/lc3_learning_the_shell.php](https://linuxcommand.org/lc3_learning_the_shell.php)
