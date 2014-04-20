# liyi‘ personal resume #

## Personal Information ##

* name:             liyi
* job intension:    linux system software engineer, linux driver software engineer
* gender:           male
* CET:              4
* phone number:     18612363082
* birthday:         1989.12.2
* blog:             http://cfylee.me
* github:           https://github.com/codemonkeydriver
* E-mail:           codemonkeydriver@gmail.com

## Education ##

* 2008.9 - 2012-7 anhui university of science and technology information security (bachelor)

## Work Skills ##

0.  familiar MIPS architecture
1.  proficient in C program language
2.  proficient in vxWorks meida lib windml
3.  proficient in linux, including command, configuration
4.  skilled in using shell script to finish repeat work automatically
5.  familiar linux kernel, virtual filesystem(VFS), process scheduling, IPC
6.  familiar linux dirver model
7.  skilled in version control system git
8.  understand C++ program language, know essential iteration, viraual function, template .etc
9.  understand object-oriented design, understand essential design pattern
10. skilled in reading and writing document
11. good code style, a love of code, try my best
12. solve problem in work without supervising

## Tools ##

* openSUSE linux
* vim
* git
* tmux
* yEd graphic edit
* oh-my-zsh
* markdwon
* evernote

## Work Experience ##

### 2012.3 - 2012.6 yunnan linux technology suppert center ###

* I was responsible for package the linux operation system,builded batching compiled
  server koji for building package from source code to RPM, maintain software yum repo
  for updating, using shell script to analysis CD configuration file, picked up a list
  of essential pakcage we need, uploaded to yum repo, compiled linux kernel.

### 2012.9 - now loongson technology ###

#### 2012.9 - 2012.12 loongson 1A linux network performance optimize ####

> I added a softirq to networking card driver, using softirq handle process to deal
> the RX/TX data, decreased the interrupt of CPU, increased the efficiency of OS.

#### 2012.12 - 2013.1 loongson 2H development board #####

> I debuged the lvds LCD screen, and I ported some assembly code to verify the ACPI
> under pmon(bios), suspend to S3 state,and wakeup OK.

#### 2013.1 - 2013.7 loongson 3A vxWorks6.8 2D acceleration ####

> I ported the DRM module frme freeBSD kernel to vxWorks,it achieved the hardware 2D
> acceleration， I finshed some function that GPU can copyed data from system memory
> to framebuffer(S2F),copyed data from framebuffer to system(F2S), copyed data form
> framebuffer to framebuffer(F2F),rectangle solid, region solid, updated the R600 GPU
> driver to fit the DRM module.

#### 2013.8 - 2013.10 loongson 3A vxWorks6.8 3D lib intergration ####

> I integrated the 3D lib that Windriver provided to us, but whitout hardware acceleration
> work slowly, 3D hardware acceleration is now developing.

#### 2013.11 - 2013.12 loongson 3A/2F vxWorks performance contrast test ####

> I wrote and proted some test programs, calculateing test, storage test, filesystem
> test, graphic test, networking test, OS performance test.

#### 2014.1 - 2014.3 loongson dual-display ####

> fixuped xserver in vxWorks, wrote some function to add dual-head options GPU, and
> intergrated in vxWorks development environment, it can be configured before build.

#### 2014.3 -2014.4 solved loongson 3A vxWorks, windml error under SMP ####

> fixup the errors in BSP with workmate, windml worked well on SMP system.

## after-hours project ##

### libylea ###

>I imiated STL that famours in C++ lib, I finished some function, such as list, queue,
>stack , vector, I practiced data struct with C++.

### arduino_pi ###

>1. pi_send_data_to_uno, raspberry PI,a famous card PC, can contorl the UNO, a famous
>  open source single chip micyoco, using GPIO, written with python and C.
>
>2. uno_say_hi_to_pi, UNO send message to raspberry to PI.

### linux_config ###

>one key restore tools under linux, just support openSUSE, it can restore my work
>environment, include softwate below, vim, tmux, zsh, git.

### wine for mips ###

>I read the source code fo wine that a software can run windows application under linux
>ported wine to MIPS architecture that besed on my workmate.(just reading some code now)

## Personal Hobby ##

* bicycle
* cooking
* hacking
* trival
