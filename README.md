# OSProject Running Containers for Application Development

Group Name: __MeowMeow__. 

Section: __6__. 

Team Mates:
1. __NUR ANNISA ZULAIKHA BINTI NOR AZMI__ and __2319070__
2. __IZYAN ILYANI BINTI RODZUAN__ and __2315464__
3. __NUR NISA HUMAIRAH BINTI ROSDI__ and __2122408__

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** __https://github.com/zulaikhaaaaa/OSProject__.
2. How many files and folders are in this repository. ***(1 mark)*** __1 folder of image and 1 file of README.md__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __The default OS used to run the virtual environment for Github Codespaces is Ubuntu Linus. Specifically, it typically uses an Ubuntu-based Docker container for the development environment__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __There's 2 options we can choose from a selction of virtual machine types which is 2 cores, 8GB RAM and 32 GB storage and 32 cores, 64 GB RAM and 128 GB storage__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __By commiting and syncing work, we can continue working on the project from any device and making sure the changes are always up-to-date and accesible__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject```__.
2. Run the command **cat /etc/passwd** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin```__.
3. Run the command **df** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10706472  20447108  35% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24859768   5422024  83% /vscode
/dev/sdc1       46127956 18672248  25080132  43% /tmp
/dev/loop4      32847680 10706472  20447108  35% /workspaces```__.
4. Run the command **du** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ du
8       ./.git/refs/heads
4       ./.git/refs/tags
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
32      ./.git/refs
68      ./.git/hooks
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
8       ./.git/objects/74
16      ./.git/objects/fa
12      ./.git/objects/af
16      ./.git/objects/83
8       ./.git/objects/96
16      ./.git/objects/c0
8       ./.git/objects/b7
8       ./.git/objects/5a
8       ./.git/objects/d3
8       ./.git/objects/93
12      ./.git/objects/17
8       ./.git/objects/24
16      ./.git/objects/1b
12      ./.git/objects/27
8       ./.git/objects/d8
8       ./.git/objects/30
12      ./.git/objects/14
12      ./.git/objects/70
8       ./.git/objects/0b
8       ./.git/objects/2b
8       ./.git/objects/47
12      ./.git/objects/26
8       ./.git/objects/cd
12      ./.git/objects/44
16      ./.git/objects/72
8       ./.git/objects/e9
8       ./.git/objects/71
12      ./.git/objects/64
16      ./.git/objects/fb
8       ./.git/objects/a3
8       ./.git/objects/0d
8       ./.git/objects/c3
8       ./.git/objects/f9
12      ./.git/objects/2e
8       ./.git/objects/7b
8       ./.git/objects/04
8       ./.git/objects/91
12      ./.git/objects/62
12      ./.git/objects/3d
12      ./.git/objects/1c
8       ./.git/objects/f6
8       ./.git/objects/b6
12      ./.git/objects/4f
8       ./.git/objects/fe
8       ./.git/objects/59
4       ./.git/objects/info
8       ./.git/objects/eb
8       ./.git/objects/41
12      ./.git/objects/29
8       ./.git/objects/e7
8       ./.git/objects/f7
8       ./.git/objects/fc
8       ./.git/objects/a7
8       ./.git/objects/4b
12      ./.git/objects/d7
8       ./.git/objects/b2
12      ./.git/objects/a9
8       ./.git/objects/20
8       ./.git/objects/ab
12      ./.git/objects/73
8       ./.git/objects/e0
8       ./.git/objects/52
8       ./.git/objects/c6
1828    ./.git/objects/pack
8       ./.git/objects/31
8       ./.git/objects/86
16      ./.git/objects/e5
8       ./.git/objects/58
8       ./.git/objects/f2
8       ./.git/objects/a4
12      ./.git/objects/6e
8       ./.git/objects/49
8       ./.git/objects/92
8       ./.git/objects/2d
8       ./.git/objects/fd
8       ./.git/objects/81
8       ./.git/objects/3f
8       ./.git/objects/4a
8       ./.git/objects/57
8       ./.git/objects/a6
12      ./.git/objects/bf
8       ./.git/objects/b9
8       ./.git/objects/3a
12      ./.git/objects/ff
8       ./.git/objects/98
12      ./.git/objects/b5
12      ./.git/objects/d2
8       ./.git/objects/60
8       ./.git/objects/cb
2676    ./.git/objects
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
2868    ./.git
1972    ./images
4868    .```__.
5. Run the command **ls** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ ls
README.md  images```__.
6. Run the command **ls -asl** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ ls -asl
total 40
 4 drwxrwxrwx+ 4 codespace root  4096 Jan 26 17:39 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 26 17:39 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 26 18:30 .git
24 -rw-rw-rw-  1 codespace root 23463 Jan 26 18:35 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jan 26 17:39 images```__.
7. Run the command **free -h** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.5Gi       402Mi        64Mi       5.8Gi       5.9Gi```__.
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2698.009
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:```__.
9. Run the command **top** and type **q** to quit. ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ top
top - 18:58:00 up  1:23,  0 users,  load average: 0.15, 0.24, 0.20
Tasks:  22 total,   1 running,  21 sleeping,   0 stopped,   0 zombie
%Cpu(s):  2.5 us,  2.0 sy,  0.0 ni, 95.3 id,  0.0 wa,  0.0 hi,  0.2 si,  0.0 st```__.
10. Run the command **uname -a**. ***(1 mark)*** __```@izyanilyani ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-0ffdff 6.5.0-1025-azure #26~22.04.1-Ubuntu SMP Thu Jul 11 22:33:04 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux```__.
11. What is the available free memory in the system. ***(1 mark)*** __```free memory : 402 Mi```__.
12. What is the available disk space mounted on /workspace. ***(1 mark)*** __```Available disk space: 20447108```__.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __```Version: Ubuntu 0ffdff 6.5.0-1025-azure 
Architecture: x86_64```__.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __```ls: Lists files and directories in the current directory.
ls -asl: Provides a detailed listing including file size, permissions, ownership, and file type```__.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __```TLB size        : 2560 4K pages```__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __```cpu MHz         : 2698.009```__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __```top process : 6.5% CPU```__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __No, files in the container are not persistent because containers are ephemeral and the file systems are erased when the container is removed__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Yes, we can run multiple instances of Debian Linux__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __By default, files created in the myroot directory from the container will be owned by the root user and group on the host machine__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Answer__.***
```bash
@zulaikhaaaaa ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/OSProject/myroot
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)*** __Port 80 in the container__.
3. What port is open for http protocol on the host machine? ***(1 mark)*** __Port 8080__.

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __BusyBox is a lightweight software suite that provides a collection of Unix utilities in a single executable for resource-constrained environments and for the command switch --name, it is used to assign a name to an entity, like a container or process, depending on the specific command being used__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
```bash
NETWORK ID     NAME      DRIVER    SCOPE
41db5ce607c8   bluenet   bridge    local
b7d1c33719b3   bridge    bridge    local
d4d4dd00f2fa   host      host      local
b9708d88f1b8   none      null      local
d2c00fcb981d   rednet    bridge    local
```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** __Gateway of bluenet: 172.18.0.1 and Gateway of rednet: 172.19.0.1__.

4. What is the network address for the running container c1 and c2? ***(1 mark)*** __Network address c1: 172.18.0.2 and Network address c2: 172.19.0.2__.
5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __No, the ping fails__.
```bash
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** __Yes, I am able to ping__.
```bash
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=4.896 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.263 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.191 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.153 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.182 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.195 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.154 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.123 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.156 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.153 ms
64 bytes from 172.20.0.3: seq=10 ttl=64 time=0.148 ms
64 bytes from 172.20.0.3: seq=11 ttl=64 time=0.151 ms
64 bytes from 172.20.0.3: seq=12 ttl=64 time=0.146 ms
64 bytes from 172.20.0.3: seq=13 ttl=64 time=0.153 ms
64 bytes from 172.20.0.3: seq=14 ttl=64 time=0.154 ms
64 bytes from 172.20.0.3: seq=15 ttl=64 time=0.172 ms
```
2. What is different from the previous ping in the section above? ***(1 mark)*** __Bridgenet can ping because it's on the same network, allowing communication between containers, while Bluenet and Rednet are separate networks, which is why the ping fails.__.

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** __Fill answer here__.
2. Show the instruction needed to make this work. ***(1 mark)*** __Fill answer here__.



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
