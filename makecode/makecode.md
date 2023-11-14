#  MakeCode Tutorial

![](media/12389c6ba84efec3a57074623e35662e.jpeg)


## How to Code and Programming

We take Windows system as example to show you.

Get started with Micro:bit: <Https://microbit.org/guide/quick/>

Step 1: Connect Micro：bit Board

Link micro:bit board to computer with USB cable.（Guide to mobile
apps：https://microbit.org/get-started/user-guide/mobile/）

Macs ,PCs, Chromebooks and Linux system（including Raspberry Pi）support
micro：bit.

![](media/f00f946e1f194811b1c84725e0eb5d16.png)
![](media/75609e6fca09a9da41efc8bab9ef9c81.png)

The board is powered when the LED on the back of the board turns red.

There will be a MICROBIT driver in your computer, as shown below:

![](media/a2b53f93f4c24b81fc5cdb5986fd100d.png)

Step 2: Programming

View the link https://makecode.microbit.org/ in your browser;

Click ‘New Project’;

The dialog box‘Create a Project’ appears, fill it with ‘heartbeat’ and click
‘Create √’to edit.

(If you are running Windows 10 system, it is also viable to edit on the APP
MakeCode for micro:bit , which is exactly like editing in the website. And the
link to the APP is
https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1&activetab=pivot:overviewtab
)

![](media/397bd09e4c2baf3c933857f3d0d1b83f.png)

![](media/5427d2c4fbb30ffdbce2fe9315244245.png)

Write a set of micro:bit code. You can drag some modules in the Blocks to the
editing area and then run your program in Simulator of MakeCode editor as shown
in the picture below.There is a video to show you how to
finish“heartbeat”pattern.

Link for the video
[microbit-heartbeat.mp4](Makecode%20Code/8.1：Heartbeat/microbit-heartbeat.mp4.mp4)

Next, we will introduce Makecode.

![](media/a6aa8681158ce5b64ffba50c1238f8c8.png)

Click”JS JavaScript”, you will find the corresponding programming languages.

![](media/fee96f8308779a8a6f8648139b0b117b.png)

Click the little triangle”of JS JavaScript”to choose “Python”, you will find the
corresponding Python programming languages.

![](media/12c11bc57b36eb82853784c645b9830a.png)

Step 3: Download Code

If your computer is Windows 10 and you have downloaded the APP MakeCode for
micro:bit to write program, what you will have to do to download the program to
your Micro: Bit main board V2 is merely clicking the ‘Download’ button, then all
is done.

If you are writing programs through the website, following these steps:

Click the ‘Download’ in the editor to download a "hex" file, which is a compact
program format that the Micro: Bit main board can read.Once the hexadecimal file
is downloaded, copy it to your board V2 just like the process that you copy the
file to the USB drive. If you are running Windows system, you can also
right-click and select ‘Send to → Microbit (E) ‘to copy the hex file to the
Micro: Bit main board V2

![](media/a81d4430eb152346d13bf67b2233b9db.png)

You can also directly drag the "hex" file onto the MICROBIT (E) disk.

![](media/fe0f2de72ba0b38f00403f1aaef7f514.png)

![](media/b4f3602c0e192646f77b150e2acaf947.png)

During the process of copying the downloaded hex file to the Micro: Bit main
board V2, the yellow signal light on the back side of the board flashes. When
the copy is completed, the yellow signal light will stop flashing and remain on.

Step 4: Run program

Upload code on micro:bit board and plug in power with USB cable.

LED dot matrix will display heartbeat pattern.

![](media/672bfb4d87b938fc586a849bff0229fe.png)
![](media/d61a26d2f2367f0378974832f679efe1.png)

Power via micro USB & via external power supply

Programming each time, MICROBIT drive will automatically eject and return.
Micro:bit only receives hex files rather than save any file.

This chapter only shows you how to get started with micro:bit board. Python and
JavaScript also support micro:bit board with the exception of Makecode.

<https://microbit.org/code/>

<https://microbit.org/projects/>

### 7.1 Makecode

Browse <https://makecode.microbit.org/> and enter Makecode online editor.

![](media/306e32b77a5dae6927b5dd0f6cf6f4f4.png)

Click“New Project”, and input“heartbeat”，then enter Makecode editor, as shown
below:

![](media/c5d52e632549cae8e23944f8febe5a03.png)

There are blocks“on start”and“forever”in the code editing area.

After power on or reset, “on start”means that the code in the block executes
once while“forever”implies that the code runs cyclically.

### 7.2 Quick Download

As mentioned before, if your computer is Windows 10 and you have downloaded the
APP MakeCode for micro:bit to write programs, the program written can be quickly
downloaded to the Micro: Bit main board V2 by selecting ‘Download’.

While it is a little more trickier if you are using a browser to enter makecode.
However, if you use Google Chrome, suitable for Linux，macOS and Windows 10, the
process can be quicker too.

We use the webUSB function of Chrome to allow the internet page to access the
hardware device connected USB.

You could refer to the following steps to connect and pair devices.

Device pairing

Interface micro:bit with computer using USB cable.

Click“...”beside“Download”and tap“Pair device”.

![](media/af4301f8510ed382b2e6bedec5cabbb1.png)

Continue to tap“Pair device”

![](media/d8aa6fb0531b6c37d626a17dfb5c32ef.png)

Then select the device you want to connect and tap“connect”in the window popping
up.

If there is no device in the window, please refer to the following link:

[https://makecode.microbit.org/device/usb/webusb/troubleshoot](https://makecode.microbit.org/device/usb/webusb/troubleshoot%20)

We also provide ![](media/1f67788540402b562ce1758202b50553.png)in the resource
link <https://fs.keyestudio.com/KS4014>

What’s more, if you don’t know how to update the firmware of micro:bit, refer to
the link:
[https://microbit.org/guide/firmware/](https://microbit.org/guide/firmware/%20)
or browse folder![](media/39366626a3bf59525948fe62c311e768.png)we provide.

![](media/026bc74a8c622516a0ecf375705c03b8.png)

After connecting successfully, press buttons and download code to micro:bit.

![](media/ee0261d79d374fdb18efaff9a4398f3e.png)

### 7.3 How to Import Extension Library on Makecode

Next, we need to import turtle-bit extension library for further lessons.

Add a Kit-bit extension library

Enter Makecode editor and click
![](media/d55ed7f8c4d691d71a6e56edb264a0d6.png)icon and tap
![](media/d2a9b25f7eb67c6bc389fc79e252d6ea.png)

![](media/c34174c17046360452a25d036815a987.png)

Copy
[https://github.com/mworkfun/pxt-turtle-bit.git](https://github.com/mworkfun/pxt-k-bit.git)
in the searching box and search turtle-bit extension library.

![](media/fee2d1bcda1f89f5d93b2b3dcc575860.png)

![](media/044891e61f3ac8e4f1c269f77fc8c015.png)

After the installation,“turtle-bit”extension library will appear in the page

![](media/82ff5ea0030ef91b2d244a0b8643508a.png)

![](media/3e71673d128b169d4f6b211285322651.png)

**Note: the extension library added is only valid to one project. Therefore, it
won’t appear in other projects.**

**You need to add the turtle-bit extension library again when creating new
projects.**

Update or Delete Turtle-bit Extension Library

Refer to the following instruction please, if you intend to update or delete
turtle-bit extension library.

Click "Js JavaScript" button to switch into text code

![](media/f7c035d1e75a5f35b4148f19bbffdb3c.png)

Click“Explorer”to get extension library .

![](media/b2fa8d7bf47042cd908ec4364fc5da65.png)

Click“![](media/ba4968271653f5f45f56008e830a7485.png)”to delete turtle-bit
extension program(TurtleBit IrRemote and Neopixel), next to
tap“![](media/0831eb76654a6b39fc6d698ee7c872b9.png)”to update turtle-bit
extension program.

![](media/fdf8d6faaecab5f567778edbf7dd582a.png)

### 7.4 Resources and Code

Download resources and code of tool package: <https://fs.keyestudio.com/KS4014>
.

After the tool package is downloaded and unzipped, a file named KS4014 Micro Bit
Mini Smart Turtle Car will be generated. It can be placed everywhere.

### 7.5 Import Code

We provide every program with hex file. You could import it directly or program
in Makecode blocks area, therefore, the extension library must be added.[(How to
add extension?)](##M11)

Next, we will take“heartbeat”as example to introduce how to import code

Open Makecode online editor on your computer

![](media/ebc8f179f28ab520bc63944361d64d64.png)

Click“Import”and“Import files”

![](media/3358909f898dd9898923f72945613851.png)

![](media/ff66d0d78d170913676e361a62078faf.png)

Choose file“../Test Code/7.1：heartbeat/microbit-heartbeat.hex”, then tap“Go
ahead”

![](media/914edffa77bd3ab6f8fc44420164c847.png)

![](media/6b007215fff6434a30c628537f574f9f.png)

In addition to the above method of importing code , you can also directly drag
cod into the Makecode compiler, as shown in the figure below:

![](media/73930634da71321517a3d6345bab3f2c.png)

The program is imported successfully after seconds

![](media/7ba7cb9509e4ce2d5674eea793e28671.png)

### 7.6 Install CoolTerm

If your computer system is Windows7/8 rather than Windows 10, the device can’t
be paired in Google Chrome, as a result, the digital/analog signals can’t be
read.

Here, we need CoolTerm software to read data.

For the whole projects, we will use CoolTerm software.

Let’s install it firstly.

CoolTerm program is used to read the serial communication.

Download CoolTerm program:

<https://freeware.the-meiers.org/>

1.  After the download, we need to install CoolTerm program file, the Window
    system is taken as an example.

2.  Choose“win”

3.  Unzip file and open it. (also suitable for Mac and Linux system)

![](media/97f831d38df9ee01dcfedac244bfe281.png)

![](media/e77548d01727e523e9e8c900d2fa962d.png)

1.  Double-click ![](media/5f29eed25fc16602cfc0716f047c2da1.png)

Note: you have to install the driver of micro:bit and connect micro:bit to
computer

![](media/74fd81c83f0c0a26b4e299b93ce4ede4.png)

The functions of each button on the toolbar are listed below:
<http://wiki.keyestudio.com/index.php/File:IDE.png>

![](media/70bebd79d7cd20336ae394c916500a28.png)

| ![](media/2b728375ed2b8cd288c884e553418001.png)        | Opens up a new Terminal                           |
|--------------------------------------------------------|---------------------------------------------------|
| ![](media/5f972f2eac5050ca0107416b2be067c2.png)        | Opens a saved Connection                          |
| ![](media/be6f8b560e0afc447f9c32b4474f633f.png)        |  Saves the current Connection to disk             |
| ![](media/52257d028694a313fc4eea4d9c2469d7.png) | Opens the Serial Connection                       |
| ![](media/6ad366842b18084553a142ab82a613cf.png) | Closes the Serial Connection                      |
| ![](media/8fa3ac342549d33b6c9aa5a9e4688bea.png) | Clears the Received Data                          |
| ![](media/c8d1dd8c3356b4938e143de1022e5842.png) | Opens the Connection Options Dialog               |
| ![](media/36e13c266fd4b9723d9db40fe30cd203.png) | Displays the Terminal Data in Hexadecimal Format  |
| ![](media/b505c71c3344036730b1d67f0c62a354.png)        | Displays the Help Window                          |

## Projects

(Note: project 1 to 12 will be conducted with the built-in sensors and LED dot
matrix of the Micro:bit main board V2)

### 1：Heartbeat

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Description：**

Prepare a Micro:bit board and USB cable. Next we will conduct a basic experiment
that a heartbeat pattern flashes on micro:bit board.

1.  **Experimental Preparation：**

2.  Connect micro:bit to computer with USB cable

3.  Open online Makecode editor

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)

**Or click“New Project”and drag blocks step by step**

![](media/b14ace883d757d0dffb2adae9a035aaa.png)

1.  **Test Code：**

| Type     | Route                                          | File Name               |
|----------|------------------------------------------------|-------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.1：Heart beat | microbit-Heart beat.hex |

Or you could edit code step by step in the editing area.

1.  Go to“Basic”→“show icon”.

Copy it again and place into“forever”block.

Click“❤”to select“![](media/04fdfc9060943954e7938bb1a741d626.png)”.

![](media/7b7e9577c6993f443060015e141f9189.png)

Complete Program：

| ![](media/04fdfc9060943954e7938bb1a741d626.png)”    |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                                                                                                                                    |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/00e2115f7e171c91af90f27889395dde.png)

**4. Test Results:**

Download code to micro:bit and keep USB cable connected. The LED dot matrix will
display ![](media/14472c7e1c80818889bb47bfc709f053.png) and
![](media/04fdfc9060943954e7938bb1a741d626.png) ceaselessly

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

If download unsuccessfully, disconnect micro:bit and reboot it

### 2：Light Up A Single LED

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Description：**

Micro:bit motherboard consists of 25 light-emitting diodes, 5 pcs in a group.
They correspond to x and y axis. Then the 5\*5 matrix is formed. Moreover, every
diode locates at the point of x and y axis.

Virtually, we could control an LED by setting coordinate points. For instance,
set coordinate point（0，0）to turn on the LED at row 1 and column 1; light up
LED at the row 1 and column 3, we could set （2，0) and so on.

![](media/41c834c1592b4ecbec3066082c25f10b.png)

1.  **Experimental Preparation：**

(1) Connect micro:bit to computer with USB cable.

(2) Open online Makecode editor.

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)

**Or click “New Project”and drag blocks step by step**

**3. Test Code：**

Import hex file:

| Type     | Route                                                    | File Name                          |
|----------|----------------------------------------------------------|------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.2 Light Up A Single LED | microbit-Light Up A Single LED.hex |

Or you could edit code step by step in the editing area.

1.  A. Click“Led”→“more”→“led enable false”

B. Put it into the“on start”block, and click the drop-down triangle button to
select“true”.![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*
(2) A. Enter“Led”→“toggle x 0 y 0”block;

B. Combine it with“forever”，alter“x 0”into“x 1”.

![](media/70e6ac6cc25d9f0f313c670383c718dd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(3) A. Enter“Basic”→“pause (ms) 100”from“

B. Then move it below the“toggle x1 y0”block, and set to
500ms.![](media/b3cf902a00a442590d9e81b3d963b856.png)

(4) Duplicate code string![](media/a19713fcfe99bbdc3b7d2448e42d3b47.png)once and
place it into“forever”block.![](media/6fa24a7c1348d775f70f3c3e65294091.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Enter“Led”→“plot x 0 y 0”

B. Keep it beneath block“pause(ms)500”, then set to“plot x 3 y
4”.![](media/2d573bedbe650cae075dea31bfd509a4.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Replicate“pause (ms) 500”once and keep it below the block“plot x3y4”

![](media/14aa140cf450499f11035dc8313bd83c.png)

1.  

2.  Click“Led”→“unplot x 0 y 0”and set to“unplot x3 y 4”;

3.  Lay down it beneath“pause (ms) 500”block

4.  Copy“pause (ms) 500”block once, and keep it below the“unplot x3 y
    4”block.![](media/523b04d16b1e2755b488b05a82c6da71.png)

Complete Program：

| ![](media/f19c365efafd84e76d058e97f7a6c50f.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript”to switch into corresponding JavaScript code:

![](media/472b93b10b3d00bef040ae15892f9c5d.png)

**4. Test Results：**

Upload program and plug in micro:bit via USB port, the LED at coordinate point
(1,0) flashes for 0.5s, then the LED at (3,4）blinks for 0.5s, alternately.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 3：5 x 5 LED Dot Matrix

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Description：**

Dot matrices are very commonplace in daily life. They have found wide
applications in LED advertisement screens, elevator floor display, bus stop
announcement and so on.

The LED dot matrix of Micro: Bit main board V2 contains 25 LEDs in a grid.
Previously, we have succeeded in controlling a certain LED to light by
integrating its position value into the test code. Supported by the same theory,
we can turn on many LEDs at the same time to showcase patterns, digits and
characters.

What’s more, we can also click”show icon“ to choose the pattern we like to
display. Last but not the least, we can our design patterns by ourselves.

1.  **Experimental Preparation：**

2.  Connect micro:bit to computer with USB cable

3.  Open online Makecode editor

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step.**

1.  **Test Code：**

**Code 1：**

| Type     | Route                                                           | File Name           |
|----------|-----------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.3：5 x 5 LED Dot Matrix/Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  A. Enter“Led”→“more”→“led enable false”

2.  Click the drop-down triangle button to select“true”
    ![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

3.  Combine it with“on start”block

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Led”to move“plot x 0 y 0”into“forever”, then replicate“plot x 0 y
    0”for 8 times, respectively set to“x 2”y 0”,“x 2”y 1”,“x 2”y 2”,“x 2”y 3”,“x
    2”y 4”,“x 1”y 3”“x 0”y 2”,“x 3”y 3”,“x 4”y 2”.

![](media/d44a44c5708aa9ea67a70220d3afde02.png)

Complete Program：

| ![](media/d44a44c5708aa9ea67a70220d3afde02.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript" to switch into the corresponding JavaScript code:
![](media/2456980fec90ec5086f078165471889f.png)

**Code 2：**

| Type     | Route                                                           | File Name           |
|----------|-----------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.3: 5 x 5 LED Dot Matrix/Code-2 | microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

1.  A. Enter“Basic”→“show number 0”block,

2.  Duplicate it for 4 times, then separately set to“show number 1”,“show number
    2”,“show number 3”,“show number 4”,“show number 5”.

![](media/5b8bc5bbc3f5e84aeb19d4dc7d7d2ffd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Basic”→“show leds”, then put it into“forever”block，tick blue boxes to
    light LED and generate“↓”pattern.

    ![](media/9c1ecc0a6db98f37533c9deec935b717.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Move out the block“show string”from“Basic”block, and leave it beneath
    the“show leds”block

    ![](media/3f638ac0f3f088a2adefa1ad17cea38a.png)

Choose“show icon”from“Basic”block, and leave it beneath the block“show
string“Hello!”block

![](media/e989a69cc6fea0a3faa6c1f491b40e69.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Enter“Basic”→“show arrow North”;

B. Leave it into“forever”block，replicate“show arrow North”for 3
times，respectively set to“North East”, “South East”, “South West”,“North West”.

![](media/008c4281fabc99c159c52fcf4ab28bf2.png)

1.  Click“Basic”to get block“clear screen”then remain it below the block “show
    arrow North West”

![](media/94182fcc1ee9e1998ef16b2925ea082b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Drag“pause (ms) 100”block from“Basic”block and set to 500ms, then leave it
    below“clear screen”block.

![](media/e782704754471e5db06937017e5022d0.png)

Complete Program:

| ![](media/20fed03d66e92ef565333d6f060b1267.png)  |
|--------------------------------------------------|
|                                                  |

Click“JavaScript" to check the corresponding JavaScript code:

![](media/4c537c2e073066441fb23219619ecf09.png)

1.  **Test Results：**

Upload code 1 and plug in micro:bit via USB cable , we will see the icon
![](media/d4e278da768e447ed344d581e671f57a.png).

Upload code 2 and plug in micro:bit via USB cable. Micro: bit starts showing
number 1, 2, 3, 4, and 5, then cyclically displays patterns
![](media/d4e278da768e447ed344d581e671f57a.png),“Hello!”,
![](media/66b31365d42274ef94ce9a3fcea1cd6c.png),
![](media/39fe4029acb5fb675d875c58e382d148.png),
![](media/45fcde65eb80a942d3903e400a346587.png),
![](media/9e34fdb19d72918bde242994a3c94c1f.png) and
![](media/2a45fca9d836ce38674c347c70c81e02.png).

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 4：Programmable Buttons

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Description：**

The button can control the on and off of the circuit. The button is attached to
the circuit. The circuit is disconnected when the button is not pressed. The
circuit is connected as soon as it is pressed, but it is disconnected after
being released.

Both ends of button are like two mountains. There is a river in between.

The internal metal piece connect the two sides to let the current pass, just
like building a bridge to connect the two mountains.

Micro:bit board has three buttons, the reset button on the back and two
programmable buttons on the front. By pressing these buttons, the corresponding
characters will be displayed on dot matrix.

1.  **Experimental Preparation：**

2.  Connect micro:bit to computer with USB cable

3.  Open online Makecode editor

**Import Hex profile**[**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step.**

1.  **Test Code：**

**Code 1：**

Press buttons on micro:bit, micro:bit will display character strings.

| Type     | Route                                                           | File Name           |
|----------|-----------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.4：Programmable Buttons/Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

You could edit code step by step in the editing area.

1.  A. Click“Basic”→“show string”;

B. Then place it into“on button A pressed”block,
change“Hello!”into“A”.![](media/aebeefcca33e544db91944881f0a9a68.png)

1.  Copy code string![](media/aebeefcca33e544db91944881f0a9a68.png)once, tap the
    drop-down button“A”to select“B”and modify
    character“A”into“B”.![](media/6c6bcb6bbeaf8ed55b985e44fc734d61.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Copy![](media/aebeefcca33e544db91944881f0a9a68.png)once，and set to“on
    button A+B pressed”and“show string“AB”

![](media/3e8bde170db9e02e9cee36b3ede184b7.png)

Complete Code:

| ![](media/1ad59546b238e9644160019cdb102ee4.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/50c59105d5a2409eea809e6ce73cf740.png)

**Code 2：**

| Type      | Route                                                           | File Name            |
|-----------|-----------------------------------------------------------------|----------------------|
|  Hex file | ../Makecode Tutorial/Test Code/8.4：Programmable Buttons/Code-2 |  microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

You could edit code step by step in the editing area.

1.  A. Click“Led”→“more”→“led enable false”,

B. Put it into the block“on start”，click drop-down triangle button to
select“true” ![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png).

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Tap“Variables”→“Make a Variable...”→“New variable name：”

B. Enter“item”in the dialog box and click“OK”，then variable“item”is produced.
And move“set item to 0”into“on start”block

![](media/a4d4a625424427a8f2d628db1f9417ae.png)

1.  A. Click“Input”→“on button A pressed”.

B. Go to“Variables”→“ change item by 1 ”

C. Place it into“on button A pressed”and 1 is modified into
5.![](media/81ec128a3a4bb86fed7d2f78bab20447.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Duplicate![](media/81ec128a3a4bb86fed7d2f78bab20447.png)code string
    once，click the drop-down button to select“B”，then set“change item by
    \-5”.![](media/a53f0e6deb299ba15c494547dec19259.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Enter“Led”→“plot bar graph of 0 up to 0”

B. Keep it into“forever”block

C. Go to“Variables”to move“item”into 0 box，change 0 into 25.

![](media/3232608700bf086dd0474de156a9116d.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Go to“Logic”to move out “if...true...then...”and “=”blocks，

B. Keep“=”into“true”box and set to “\>”

C. Select“item”in the“Variables”and lay it down at left box of “\>”，change 0
into 25；

D. Enter“Variables”to drag“set item to 0”block into“if...true..then...”, alter 0
into 25.

![](media/75a22c2c7eaf03a6d0ffaadf1d9f2fe9.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(7) A. Replicate code string![](media/e0de4c7488b48605b292df5d3dd798dc.png)once

B.“\>”is modified into“\<”and 25 is changed into 0,

C. Leave it beneath ![](media/e0de4c7488b48605b292df5d3dd798dc.png)code string.

![](media/678059d480a41d372a6b70175b5a3225.png)

Complete Program：

| ![](media/e2d7143ce59218e14780e9370d973c51.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript" to switch into JavaScript code:

![](media/21704f7ef37d6ed440545c28dbd93211.png)

1.  **Test Results：**

Upload code 1 and plug in micro:bit via USB cable, 5×5 LED dot matrix will
show“A”if button A is pressed, in case that button B is pressed,“B”will appear.
So will micro:bit show“AB”if you press A and B buttons simultaneously.

Upload code 2 and plug in board via USB cable. A row of luminous LEDs are added
if button A is pressed, when B pressed, a row of luminous LEDs are deducted.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 5：Temperature Measurement

1.  **Description：**

Micro:bit main board doesn’t come with temperature sensor actually, but detect
temperature through built-in temperature of NFR51822 chip. Thereby, the detected
temperature is more close to chip’s temperature.

**Note: the temperature sensor of Micro:bit main board is shown below:**

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

1.  **Experimental Preparation：**

2.  Connect micro:bit to computer with USB cable

3.  Open online Makecode editor.

**Import Hex profile**[**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step**

1.  **Test Code：**

**Code 1：**

Micro:bit detects temperature

| Type     | Route                                                               | File Name           |
|----------|---------------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.5：Temperature Measurement /Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  Go to“Advanced” →“Serial” →“serial redirect to USB”

Place it into “on start”

![](media/07637ee0425802f6a59eb6f6dd62ea5c.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Serial”to drag out“serial write value x=0”

Move it into“forever”block

![](media/0e709be8f6acc9521f1f76a0fc32c792.png)

1.  Go to“Input” →“temperature(℃)”

Place it into 0 box

Change x into Temperature

![](media/2143a993b073f763a2e770a7eea628d6.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Move“pause (ms) 100”from“Basic”block and place it under block“serial
    write.....temperature(℃)”

![](media/0c03bc986e186751ac33b92e5052b26f.png)

Complete Program：

| ![](media/e1e316ab2c9727c9b5a36dd82a7ab11a.png)   |
|---------------------------------------------------|
|                                                   |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/0cb83e9f83fa0fd0344685f38913cb43.png)

( [How to quick download?](##_7.3.快速下载))

Download code 1 to micro:bit board and keep USB cable connected, then tap button
![](media/e0580d7886af95d2a4ea7cd9d40759ff.png):

( [How to quick download?](##_7.3.快速下载))

![](media/0d3198e0cb5460c9820bc2f016c0d7c1.png)

Temperature data is shown below:

![](media/6177222069a9583f2d8314d592fdb916.png)

Through the test, the room temperature is 35℃when touching the NFR51822 chip of
micro:bit; however, the temperature rises to 37℃ when it touches water cup.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of Micro:bit is 115200 through
the test). Click“OK”and“Connect”.

The serial monitor shows the current ambient temperature value, as shown below:

![](media/b3a18bca1b2a7b5337470735e5a0c5aa.png)

![](media/f78128c148de3862a3fe10d86f063e22.png)

![](media/13238e98c31d620f4ffd7742dd71c78d.png)

![](media/9c88bb875124738a55e5e0fd5bf957ca.png)

**Code 2：**

**Micro:bit display different pictures by temperature(the temperature value in
the code could be adjusted)**

| Type     | Route                                                              | File Name           |
|----------|--------------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.5：Temperature Measurement/Code-2 | microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

You could set temperature based on real situation.

1.  Click“Led”→“more”→“led enable false”into“on start”，click drop-down triangle
    button to select“true” ![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Go to“Logic”→“if..true...then...else”and “=” block;

B. Move“if..true...then...else” into“forever”block，then place“=”into“true”box.

![](media/28c4cf38fbacb05ca0e457146767757d.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Change“=”into“≥”

B. Go to“Input”→“temperature(℃)”and move it into left 0 box;

C. Change 0 into 35.

![](media/2b0e3775540415849bf36f7d118a8599.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Tap“Basic”→“show icon”，copy it once and lay down them under the“if ...then”
    and else blocks, then click the drop-down triangle button to
    select“![](media/9fa58029eb504582ee5a915f591ea583.png)”.
    ![](media/fee3bbacccaebb856bbf2cbbe95a82bf.png)

Complete Program：

| ![](media/9fa58029eb504582ee5a915f591ea583.png)” |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                                                                                                                                                                                                                                          |

Click“JavaScript", the corresponding JavaScript code is shown below:

![](media/9424f8456bb544ca25a7c5a4ea6e852c.png)

**4. Test Results：**

Upload the Code 1 and plug in power. And 5\*5LED displays the ambient
temperature. When pressing the temperature sensor, the temperature will grow on
dot matrix.

Upload the code 2 plug in micro:bit via USB cable, when the ambient temperature
is less than 35℃, 5\*5LED will
show![](media/4b1765e12b413dc5d562f2a16d32392f.png). When the temperature is
equivalent to or greater than 35℃, the
pattern![](media/f2705fbc4886efcfaac96589ca255f66.png) will appear.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 6：Micro:bit’s Compass

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

**1. Description：**

This project mainly introduces the use of the Micro:bit’s compass. In addition
to detecting the strength of the magnetic field, it can also be used to
determine the direction, an important part of the heading and attitude reference
system (AHRS) as well.  
It uses FreescaleMAG3110 three-axis magnetometer. Its I2C interface communicates
with the outside, the range is ±1000µT, the maximum data update rate is 80Hz.
Combined with accelerometer, it can calculate the position. Additionally, it is
applied to magnetic detection and compass blocks.

Then we could read the value detected by it to determine the location. We need
to calibrate the Micro:bit board when magnetic sensor works.

The correct calibration method is to rotate the Micro:bit board.

In addition, the objects nearby may affect the accuracy of readings and
calibration.

**2. Experimental Preparation：**

1.  Connect micro:bit to computer with USB cable

2.  Open online Makecode editor

**Import Hex profile**[**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step**

**3. Test Code：**

**Code 1：**

Press A on micro:bit, the value of compass is shown.

| Type     | Route                                                          | File Name            |
|----------|----------------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.6：Micro:bit’s Compass/Code-1 |  microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  A. Click“Input”→“more”→“calibrate compass”

B. Lay down it into block“on start”.

![](media/f0973c3116eb4faf2d4ca138bd057d45.png)

1.  A. Go to“Input”→“on button A pressed”.

B. Enter“Basic”→“show number”, put it into“on button A pressed”block;

C. Tap“Input”→“compass heading(℃)”， and place it into“show number”

![](media/0d9b5a65740d9406848d9a360635982b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

![](media/3dac0d4c18fe1334cb76de8a87bf150c.png)Complete Program：

| ![](media/3dac0d4c18fe1334cb76de8a87bf150c.png) |
|------------------------------------------------------|
|                                                      |

![](media/3dac0d4c18fe1334cb76de8a87bf150c.png)Click“JavaScript",
and view the corresponding JavaScript code:

![](media/a3fa9018b3e83be04515297b5fd94b42.png)

**Code Description：**

Upload the code 1, plug in micro:bit via USB cable.

As the button A is pressed, LED dot matrix indicates that“TILT TO FILL
SCREEN”then enter the calibration interface. The calibration method: rotate the
micro:bit to make LED dot matrix draw a square (25 LEDs are on), as shown in the
following figure:

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

![](media/acf3b8c0dee027d9e555fc708831f874.jpeg)

The calibration will be finished until you view the smile
pattern![](media/a4faf86fb027b2f4c3dacaeee5d47d2b.png)appear.

The serial monitor will show 0°, 90°, 180° and 270° when pressing A.

**Code 2：**

Make micro: bit board point to the north, south, east and west horizontally ,
LED dot matrix displays the corresponding direction patterns

| Type     | Route                                                          | File Name            |
|----------|----------------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.6：Micro:bit’s Compass/Code-2 |  microbit-Code-2.hex |

![](media/66c4482e3bcd71e712a54f4d73044104.png)  
This code string complies that we read the value detected incessantly and
determine the direction by the value range. The direction is toward North at
this time.

Or you could edit code step by step in the editing area.

1.  

2.  Enter“Input”→ “more”→“calibrate compass”

3.  Move“calibrate compass”into“on start”

![](media/f0973c3116eb4faf2d4ca138bd057d45.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Click “Variables”→“Make a Variable...”→“New variable name：”

B. Input“x”in the blank box and click“OK”, and the variable“x”is generated.

C. Drag out“set x to”into“forever”block

![](media/0ecd067449d3d52ce3ba751632129b54.png)

1.  Go to“Input”→“compass heading(℃)”, and keep it into “0” box

![](media/a97f7ff675fc62533a9053b6c415652b.png)

Tap“Logic”→“if...then...else”, leave it below block“sex x to compass
heading”，then click![](media/bf972b006ad6d05686352c4785e54994.png)icon for 6
times.

1.  A. Place“and”into “true” block

B. Then move“=”block to the left box of “and”

C. Click“Variables”to drag“x”to the left“0”box, change 0 into 293 and set to“≥”;

D. Then copy“x≥293”once and leave it to the right“0”box and set to“x\<338”

![](media/cf2d8d1d74b5f485abd4843f92b52672.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Go to“Basic”→“show leds”

B. Lay it down beneath ![](media/6dbd99f5a6e4abe8ffd450d19b8a857b.png)block,
then click“show leds”and the pattern
![](media/eab025b80ef24f1d5351bd3e06221bad.png)appears.

![](media/fe40fd39ae6abce0721d19cf86ef136d.png)

1.  A. Duplicate ![](media/6dbd99f5a6e4abe8ffd450d19b8a857b.png)for 6 times.

B. Separately leave them into the blank boxes behind“else if”.

C. Set to“x≥23 and x\<68 ”,“x≥68 and x\<113 ”,“x≥113 and x\<158 ”,“x≥158 and
x\<203 ”,“x≥203 and x\<248 ”,“x≥248 and x\<293 ”respectively.

D. Then copy“show leds”for 7 times and keep them below the “else if.......then”
block respectively.

E. Click the blue boxes to form the
pattern“![](media/4c73992fa4dfc6a2735b49ea8f000ed6.png)”,
“![](media/0771b8fd797a3e945a01ec1525ba4a9d.png)”,
“![](media/41eb716a282d52483e8467704613d034.png)”,
“![](media/2cae18294b329c10ecdefd768d6954e0.png)”,
“![](media/14b893d1a7157d72209b975d0df8d890.png)”,
“![](media/c362406f55115926523a0f60e16828b6.png)”and
“![](media/3977e13fdec2bfbc7fc55f5dce4969a9.png)”.

Complete Program：

| ![](media/41eb716a282d52483e8467704613d034.png)pattern appears       |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](media/c362406f55115926523a0f60e16828b6.png) When x is not among the above rang, the next program will be executed under else block                                                                                                                                                                                                                                                                         |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/7140a86db633ec1bb6ec7e07a109a0dc.png)

![](media/1d4fdac44bf4e1629145fac97f627c24.png)

1.  **Test Results：**

Download code 2 to micro:bit and keep USB cable connected.

After calibration, tilt Micro:bit board, micro:bit displays the direction signs.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 7：Accelerometer

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

**1. Description：**

The micro:bit board has a built-in Freescale MMA8653FC three-axis acceleration
sensor (accelerometer). Its I2C interface works on external communication, the
range can be set to ±2g, ±4g, and ±8g, and the maximum data update rate can
reach 800Hz.  
When the Micro:bit is stationary or moving at a constant speed, the
accelerometer only detects the gravitational acceleration; when the Micro:bit is
slightly shaken, the acceleration detected is much smaller than the
gravitational acceleration and can be ignored. Therefore, in the process of
using Micro:bit, the main purpose is to detect the changes of the gravitational
acceleration on the x, y, and z axes when the attitude changes.  
For this project, we will introduce the detection of several special postures by
the accelerometer.

**2. Experimental Preparation：**

1.  Connect micro:bit to computer with USB cable

2.  Open online Makecode editor

**Import Hex profile**[**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step**

**3. Test Code：**

**Code 1：**

| Type     | Route                                                    | File Name           |
|----------|----------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.7: Accelerometer/Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

(1) A. Enter“Input”→“on shake”，

B. Click“Basic”→“show number”, place it into“on shake”block, then change 0 into
1.![](media/b86b68744e64e4e9907ccb1fa0cb2af7.png)

(2) A. Copy code string ![](media/b86b68744e64e4e9907ccb1fa0cb2af7.png)for 7
times;

1.  separately click the triangle button to select“logo up”,“logo down”,“screen
    up”,“screen down”,“tilt left”,“tilt right”and“free fall”, then respectively
    change 1 into 2, 3, 4, 5, 6, 7, 8.

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

| ![](media/75e625fbae54fd3d76cf6c4967d87415.png) |
|--------------------------------------------------------|
|                                                        |

| ![](media/3fc45754cb7a060d660212c5cb8c268f.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript", you will view the corresponding JavaScript code:

![](media/ffd55d004aee7f100e1a2608c90f1c7c.png)

**Code 2：**

Detect the value of acceleration speed at x, y and z axis

| Type     | Route                                                    | File Name           |
|----------|----------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.7：Accelerometer/Code-2 | microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

1.  A. Go to“Advanced”→“Serial”→“serial redirect to USB”

B. Drag it into“on start”

![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Enter“Serial”→“serial write value x =0”

B. Leave it into“forever”block

![](media/1dcff6f8c61c0c7ac220ded584bcf988.png)

1.  \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*A.
    Click“Input”→“acceleration(mg) x”；

B. Keep it into“0”box and capitalize the“x”

![](media/3f132064ad2081eabf6269eb4c0e698b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Go to“Basic”and move out“pause (ms) 100”below the
    block![](media/aa23874d61a27c3af5263746851f6fef.png), then set to 100ms.

    ![](media/98c688ae175b0c5eca6bed1d95f7b301.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Replicate code string![](media/c013533f2e3a02f26116f176ba6f975b.png)

for 3 times and keep them into“forever”block，separately set the whole code
string as follows:

![](media/e11b467aef3999050e8a3b5cd175dce9.png)

Complete Program：

![](media/57fec5e7a6bda76b8ddc6c3538b58010.png)

Click“JavaScript" to view the corresponding JavaScript code:

![](media/381a6d80fa940cb21ad6963469eef351.png)

([How to quick download?](##_7.3.快速下载))

Download code 1 to micro:bit board, keep USB cable connected and
click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?](##_7.3.快速下载))

![](media/821a64a53c3a9709ff556e71b070f4dd.png)

The coordinates of the Micro:bit accelerometer are shown in the following
figure:

![](media/6303a0ac122680207fe856d9be38d01c.png)

The decomposition value of acceleration on the X-axis, Y-axis, and Z-axis, as
well as the synthesis of acceleration (the synthesis of gravitational
acceleration and other external forces). Then flip the micro:bit board, the data
is shown below:

![](media/ded4e05f2b15d694e2061159628574dc.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of Micro:bit is 115200 through
the test). Click“OK”and“Connect”.

CoolTerm serial monitor displays the acceleration value on x, y and z axis.

![](media/b4f4201cccf6ac0dadffb952b7596895.png)

**4. Test Results：**

Download code 1 to micro:bit board and keep USB cable connected, shake the
Micro:bit board then the number 1 appears.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Place micro:bit vertically(logo up), then the number 2 is displayed:

![](media/1600323e3e61e331c248cbeda5ccdcfc.jpeg)

Place micro:bit vertically(logo down), then the number 3 is displayed:

![](media/3be80acf957e53117f695801ce19c449.jpeg)

Place micro:bit horizontally (facing up), then the number 4 is displayed:

![](media/5797dd7be9a9c2d3226123e0c29db0bd.jpeg)

On the contrary, place micro:bit horizontally (facing down), then the number 5
is displayed:

When Micro:bit board is tilt to the left, number 6 is shown.

![](media/326095934bcff0a925b4f9a09d6cf7d2.jpeg)

When Micro:bit board is inclined to the right, number 7 is displayed.

![](media/185b0ac204e9b2c54dd8fa93d852568c.jpeg)

When it is free fall(accidentally making it fall), number 8 appears on dot
matrix.（Note：we don’t recommend you to make it free fall, it will make board
damage)

### 8：Detect Light Intensity by Micro:bit

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Description：**

This project will introduce how Micro:bit detects the external light intensity.
Since Micro:bit doesn’t come with a photosensitive sensor, the detection of
light intensity is completed through the LED matrix. When the light irradiates
the LED matrix, the voltage change will be produced. Therefore, we could
determine the light intensity by voltage change.

1.  **Experimental Preparation：**

2.  Connect micro:bit to computer with USB cable

3.  Open online Makecode editor

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step.**

**3. Test Code：**

| Type     | Route                                                                   | File Name                                         |
|----------|-------------------------------------------------------------------------|---------------------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.8：Detect Light Intensity by Micro:bit | microbit-Detect Light Intensity by Micro:bit .hex |

Or you could edit code step by step in the editing area.

(1)A. Enter“Advanced”→“Serial”→“serial redirect to USB”;

B. Drag it into“on start”block.![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(2) A. Go to“Serial”→“serial write value x =0”;

B. Move it into“forever”![](media/1dcff6f8c61c0c7ac220ded584bcf988.png)

1.  A. Click“Input”→“acceleration(mg) x”

B. Put“acceleration(mg) x”in the“0”box and change “x”into“Light intensity”.

![](media/38447eae9d3e190496b9a24baea6cbe7.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  A. Click“Basic”→“pause (ms) 100”;

B. Lay it down into“forever”and set to 100ms.

![](media/9ba8558c0d520cc80b01080e437ddff5.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Complete Program：

| ![](media/1ae769b6a1d9f6c6a393351c69b10d32.png)   |
|---------------------------------------------------|
|                                                   |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/7739b4e9b0603e04cdeb1c7051b9d2f8.png)

**5. Test Results：**

Download code to micro:bit board don’t plug off USB cable and
click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?](##_7.3.快速下载))

![](media/04b472326485cf676cdb4dd61ca6ef1a.png)

The intensity value is 0 when covering LED dot matrix. And the value varies with
the light intensity. When placing micro:bit under the sunlight, the stronger the
light is, the larger the intensity value is. As shown below:

![](media/d7f1751ea1e6f251376dee5390ed21fa.png)

Open“CoolTerm”, click“Options”to select “SerialPort”, and set “COM” port and
115200 baud rate(the baud rate of USB serial communication of micro:bit is
115200 through the test).

Then click“OK”and“Connect”.

The light intensity value is shown below:

![](media/77a6de8ab9b171353693610a09f3a83c.png)

### 9: Speaker

![](media/ac515b9ae8891dc32f368a29f194a2fb.png)

**1. Description:**

The Micro: Bit main board V2 has an built-in speaker, which makes adding sound
to the programs easier. We can program the speaker to air all kinds of tones
,such as playing the song, "Ode to Joy" .

**2.Experimental Preparation：**

Connect micro:bit to computer with USB cable

Open online Makecode editor

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step.**

**3. Test Code：**

| Type     | Route                                                    | File Name                          |
|----------|----------------------------------------------------------|------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.9：Speaker by Micro:bit | microbit-Speaker by Micro:bit .hex |

Or you could edit code step by step in the editing area.

1.  Enter“Basic”module to find “show icon”and drag it into“on start”block;

Click the little triangle to find
“![](media/7f7aa904c35f83b61c7c560ad1e40d2a.png)”

![](media/fed4c4f6e66e6d53fa2d8e10f01268fd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(2) Enter“Music”module to find and drug“play sound giggle until done” into
“forever”block;

Enter“Basic”module to find and drug“pause(ms) 100” into “forever” block ;

Change 100 into 1000;

![](media/2a264656778216144131c75fabbbabf2.png)

( 3 ) Copy ![](media/39f8b940e6a1a3e8dbfa8eae70aa10c3.png) three times and place
it into “forever” block ;

Click the little triangle to select “happy”,”hello”,”yawn”;

![](media/a8cee1c98866343f817d29e2ed97c584.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![](media/ebd84db5c527208b9fa4c7bfd91c50a5.png)

Select “JavaScript" and “Python” to switch into JavaScript and Python language
code:

![](media/984405217312d495104129a784ef76de.png)

![](media/99449615712dcb5903fe116a8255204b.png)

**4.Test Results:**

After uploading the test code to micro:bit main board V2 and powering the board
via the USB cable, the speaker utters sound and the LED dot matrix shows the
logo of music.

### 10: Touch-sensitive Logo

![](media/644695850097c5ade080bb4848b4b481.png)

**1. Description:**

The Micro: Bit main board V2 is equipped with a golden touch-sensitive logo,
which can act as an input component and function like an extra button.

It contains a capacitive touch sensor that senses small changes in the electric
field when pressed (or touched), just like your phone or tablet screen do.When
you press it , you can activate the program.

**2.Experimental Preparation：**

Connect micro:bit to computer with USB cable

Open online Makecode editor

**Import Hex profile** [**(How to import?)** ](##_7.6.导入代码)**, or click“New
Project”and drag blocks step by step.**

**3. Test Code：**

| Type     | Route                                                                  | File Name                                       |
|----------|------------------------------------------------------------------------|-------------------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.10：Touch-sensitive logo by Micro:bit | microbit-Touch-sensitive logo by Micro:bit .hex |

Or you could edit code step by step in the editing area.

( 1 ) Delete block“on start”and“forever”;

( 2 )Enter“Input”module to find and drag“on logo pressed” ;

Click the little triangle to find“touched”;

![](media/b228ddd2c400e6cc11be3a87636c27be.png)

( 3 ) Enter module“Variables”→choose“Make a Variable”→input“start”→click“OK”

The variable“start”is established;

Enter“Variables”module to find and drag “set start to 0” into “on logo
touched”block;

![](media/f425f9f9545f2d8300fbb0c8946b9ea3.png)

( 4 )Enter“Input”module →click “more”→ find and drag“running time(ms)”into
the“0”of“set start to 0”block;

![](media/7af1f7fa05580ed5d588daf80351182c.png)

( 5 )Enter“Basic”module to find and drag“show
icon![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)” into “on logo
touched”block;

![](media/931663a2485eca2baa411b43484e5cc3.png)

( 6 )Enter“Input”module to find and drag“on logo pressed”→choose “released”→
establish variable “time”;

Enter“Variables”module to find and drag “set time to 0”into “on logo
pressed”block;

Enter“Math”module to find and drag “0-0”into the “0”of“set start to 0”block;

![](media/f2b9c02043be64c98da2e0ded2181082.png)

( 7 )Enter“Input”module→ “more” → find and drag “running time(ms)” into “0”on
the left side of “0-0”;

Enter“Variables”module to find and drag“start” into “0”on the right side of
“0-0”;

![](media/09e205a5774658821e5a988b63b39203.png)

( 8 )Enter“Basic”module to find and drag“show number” into “on logo
released”block;

Enter“Math”module to find and drag“square root 0” into“0”; Click the little
triangle to find”integer÷”;

![](media/5056fe4add2914acf570df6706ce0bb7.png)

( 9 ) Enter“Variables”module to find and drag“time”into“0”on the left side
of“0-0”and change the“0”on the right side to”1000”;
![](media/a2247b14f9957f856485a927cfa7186e.png)

Complete Program：

![](media/bb847ad951cd721972d24fe0b90631a1.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language
code:

![](media/15d6364778e29d2a05442c6cf01cc88d.png)

![](media/f63f0917317e2f8542961a88a5e6827f.png)

**4.Test Results:**

After uploading the test code to micro:bit main board V2 and powering the board
via the USB cable, the LED dot matrix exhibits the heart pattern when the
touch-sensitive logo is pressed or touched and displays digit when the logo is
released.

### 11: Microphone

![](media/7f0741158e734ff8449d5b87d5ba85f4.png)

**1.Description:**

The Micro: Bit main board V2 is built with a microphone which can test the
volume of ambient environment. When you clap, the microphone LED indicator will
turn on. Since it can measure the intensity of sound, you can make a noise scale
or disco lighting changing with music. The microphone is placed on the opposite
side of the microphone LED indicator and in proximity with holes that lets sound
pass.When the board detects sound, the LED indicator lights up.

**2.Experimental Preparation：**

Connect micro:bit to computer with USB cable

Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码) , or click“New Project”and
drag blocks step by step.

3\. Test Code：

| Type     | Route                                                        | File Name                                  |
|----------|--------------------------------------------------------------|--------------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.11：Microphone by Micro:bit | microbit-Microphone logo by Micro:bit .hex |

Or you could edit code step by step in the editing area.

(1 ) Delete block“on start”and“forever”;

( 2 ) Enter“Input”module to find and drag“on loud sound”;

Enter“Basic”module to find and drag “show number”into “on loud sound”block ;

![](media/4fc47e876fa715d7e18b42f81aaf2f75.png)

( 3 )Copy ![](media/c7e2c46845a453f1de63b5e6f16af7fc.png) once;

Click the little triangle of “lond” to choose”quiet”;

Click the little triangle of “![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)”
to choose”![](media/9a40d2f51ed0a372a82e559cdb2ca0dd.png)”;

![](media/2aa3293670d895afc772871026303399.png)

Complete Program：

![](media/b48689241988a3fda8de4e26ebd9a4ed.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language
code:

![](media/e366483e9d5c574f3ec520f30e31e5cd.png)

![](media/fcba6eada2f29e11eee49a42987ab23e.png)

4.Test Results 1:

After uploading test code to micro:bit main board V2 and powering the board via
the USB cable.

The LED light will display“![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)”when
you clap your hands and ![](media/04fdfc9060943954e7938bb1a741d626.png) will
appear when the environment is quiet

5.Test Code 2:

Link computer with micro:bit board by micro USB cable, and program in MakeCode
editor,

( 1 )Enter“Advanced”module→ choose“Serial”to find and drag“serial redirect to
USB”into “on start”block ;

![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

( 2 )Enter“Variables”module→ choose“Make a Variable”→ input “maxSound”→click
“OK”,variable ”maxSound”is established;

Enter“Variables”module to find and drag“set maxSound to 0”into “on start”block ;

![](media/39347e31badf7d15710fc12f581ce7e1.png)

( 3 )Enter“Logic”module to find and drag“if true then...else”into “forever”
block ;

Enter“Input”module to find and dragbutton A is pressed”into “then” ;

![](media/643d739679dd8891a240feda70868302.png)

( 4 )Enter“Basic”module to find and drag“show number”into“then” ;

Enter“Variables”module to find and drag“maxSound”into“0” ;

![](media/eff0b22497be40e1826bccef95ceb0a4.png)

1.  Establish variable“soundLevel”;

Enter“Variables”module to find and drag“set soundLevel to 0”into “else”;

Enter“Input”module to find and drag“sound level” into “0”;

![](media/c84fcdd7bfc4b545e420fa2d6a975bfe.png)

( 6 )Enter“Led”module to find and drag“plot bar graph of 0 up to 0” into “else”;

Enter“Variables”module to find and drag“soundLevel”into the“0”behind “of”;

Change the “0”behind “up” to“255”;

![](media/adc684949503c334c505157743fdbc7b.png)

( 7 )Enter“Logic”module to find and drag“if true then”into “else”block ;

Enter“Logic”module to find and drag“0 \> 0”into “then” ;

Enter“Variables”module to find and drag“soundLevel”into“0”on the left side of
“0-0” ;

Enter“Variables”module to find and drag“maxSound”into“0”on the right side;

![](media/928f828756c965def348b56ef5299749.png)

( 8 )Enter“Variables”module to find and drag“set maxSound to 0”into the second
“then” ;

Enter“Variables”module to find and drag“soundLevel”into the “0” ;

![](media/d62369e61dcc9dba69b80c93b1c7c7e8.png)

Complete Program：

![](media/c42455108c20d4ae51546957ab4198bb.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language
code:

![](media/4e327f5f9ed716e6cf27cccba674f1c3.png)

![](media/e4adb50417583440e2620c1bb50528e1.png)

1.  **Test Results 2:**

Upload test code to micro:bit main board V2, power the board via the USB cable
and click Show console Device”as shown below.

![](media/e22507af4953df977269bbdb2463d69e.png)

When the sound is louder around, the sound value shows in the serial port is
bigger as shown below.

![](media/50b81518d9f7925b0c20476ab1f64185.png)

What’s more, when pressing the button A, the LED dot matrix displays the value
of the biggest volume( please note that the biggest volume can be reset via the
Reset button on the other side of the board ) while when clapping, the LED dot
matrix shows the pattern of the sound.

### 12: Bluetooth Wireless Communication

![](media/55b2424d88ba1ba8a711c49418ca8dc6.png)

**1.Project Description:**

The Micro: Bit main board V2 comes with a nRF52833 processor (with built-in
Bluetooth 5.1 BLE(Bluetooth Low Energy) device) and a 2.4GHz antenna for
Bluetooth wireless communication and 2.4GHz wireless communication. With the
help of them, the board is able to communicate with a variety of Bluetooth
devices, including smart phones and tablets.

In this project, we mainly concentrate on the Bluetooth wireless communication
function of this main board. Linked with Bluetooth, it can transmit code or
signals. To this end, we should connect an Apple device (a phone or an iPad) to
the board.

Since setting up Android phones to achieve wireless transmission is similar to
that of Apple devices, no need to illustrate again.

**2. Preparation**

\*Attach the Micro:bit main board V2 to your computer via the Micro USB cable.

\*An Apple device (a phone or an iPad) or an Android device;

**3. Procedures:**

For Apple devices, enter this link:

<https://www.microbit.org/get-started/user-guide/ble-ios/> with your computer
first, and then click “Download pairing HEX file”to download the Micro: Bit
firmware to a folder or desk, and upload the downloaded firmware to the Micro:
Bit main board V2.

![](media/cfaf7f8ae83cbe2636c39162a78adc7f.png)

![](media/6c1cef08d31fe3c4876b90ecc11554ff.jpeg)

![](media/63f1faf124af4949b31d7a84cee19a92.png)

Search“micro bit”in your App Store to download the APP micro:bit.

![](media/66d1f34d8d4c52e2b7c0ce10e602a063.png)

Connect your Apple device with Micro: Bit main board V2:

Firstly, turn on the Bluetooth of your Apple device and open the APP micro:bit
to select item “Choose micro:bit”to start pairing Bluetooth.

Please make sure that the Micro: Bit main board V2 and your computer are still
linked via the USB cable.

![](media/34f5fbb1c0c371970d1aec6c59c5cbb5.png)

Secondly, click“Pair a new micro:bit”;

![](media/e20270a0ade9c00b61198b26fc2fd83b.png)

Following the instructions to press button A and B at the same time(do not
release them until you are told to) and press Reset & Power button for a few
seconds.

Release the Reset & Power button, you will see a password pattern shows on the
LED dot matrix. Now , release buttons A and B and click Next.

![](media/c00520400ecd1f20f958c1c6d1a3c907.png)

![](media/cabc60d7f8a030f5c9d86ac7de6c7bd7.png)

Set the password pattern on your Apple device as the same pattern showed on the
matrix and click Next.

![](media/9411a5280e6f3b0d45306a31f80c1b38.png)

Still click Next and a dialog box props up as shown below. Then click "Pair". A
few seconds later, the match is done and the LED dot matrix displays the "√"
pattern.

![](media/f72e83dc6276d520e82c349659106e1a.png)

After the match with Bluetooth, write and upload code with the App.

Click“Create Code”to enter the programming page and write code.

Click ![](media/f3e9cc7884f7bba807fa4633c429422b.png) and the box
![](media/e081360be7c91b7a156b01a787e4a58c.png) appears, and then select“Create
√”.

![](media/d54bf2d1c01cd3c18544009b1f9dc5a0.png)

![](media/4e7a5d06a5f9a5a209ef5fbc005e9f62.png)

![](media/5bd84e8d293bf8c0c999c7f4e756cf30.png)

![](media/bd19bb4c97ad2a5bc300412b8eb93ede.png)

Name the code as“1”and click ![](media/a32c2d832ab38d19eb623108143c744e.png) to
save it.

![](media/25cf76f891c5eac7381b8095363a2748.png)

Click the third item“Flash”to enter the uploading page. The default code program
for uploading is the one saved just now and named "1" and then click the other
"Flash" to upload the code program "1".

![](media/c1661720ea2eaa521ff31a778501eb23.png)

![](media/350abcbb09d431d40427f34c3764f2eb.png)

![](media/4863bf826f119805a6a9bf9c12d5ec81.png)

If the code is uploaded successfully a few seconds later, the App will emerge as
below and the LED dot matrix of the Micro: Bit main board V2 will exhibit a
heart pattern.

![](media/ebfd31347a0553de0be4e01636652a15.png)

Projects above all conduct with the built-in sensors and the LED dot matrix of
the main board while the following ones will carry out with the help of external
sensors of this turtle car.

**（Attention：to avoid burning the the Micro:bit main board V2, please remove
the USB cable and the external power from the board before fix it with the
shield of the car; likewise, the USB cable and the external power should be cut
from the main board before disconnect the shield from the board.)**

### 13: Passive Buzzer

![](media/74060fac6c085d68066db94d1ada3a99.png)

1.  **Description：**

We can use Micro:bit board to make many interactive works of which the most
commonly used is acoustic-optic display. The previous lessons are related to
LED. However, we will elaborate the Sound in this lesson.

Buzzer is inclusive of active buzzer and passive buzzer.

The passive buzzer doesn’t carry with vibrator inside, so it need external sine
or square wave to drive. It can produce slight sound when connecting directly to
power supply. It features controlling sound frequency and producing the sound
of“do re mi fa so la si”.

A diode should be connected in reverse when driving by the square wave signal
source, which will hinder the high-voltage generated to damage other components
or service life when the power breaks down.

Frequency is made of a series of pitch names in English letters and Numbers. You
can choose different frequencies, that is, tone. The frequency of sound is
called pitch.

It involves music knowledge. In music lesson, our teacher taught“1（Do）,
2（Re）, 3(Mi), 4(Fa) , 5(Sol), 6(La), 7(Si)”

| 1（Do） | 2（Re） | 3(Mi) | 4(Fa) | 5(Sol) | 6(La) | 7(Si) |
|---------|---------|-------|-------|--------|-------|-------|
| C       | D       | E     | F     | G      | A     | B     |

The number depends on high or low tone. The larger the number, the higher the
tone. When the number is the same, the frequency (tone) is getting higher and
higher from C to \_B.

Beats are the time delay for each note. The larger the number, the longer the
delay time. A note without a line in the spectrum is a beat, with a delay of
1000 milliseconds. while a beat with an underline is 1/2 of a beat without a
line, and a beat with two underlines is 1/4 of a beat without a line.

（![](media/a57464c004160236cb89f0deb31f185d.png)）

Here is the notation of Ode to Joy.

![](media/4a79470cc28f087a3834d168bc0c343f.jpeg)

**2. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial POWER switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

Import Hex profile [**(How to import?)** ](##_7.6.导入代码) , or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

1.  **Test Code：**

| Type     | Route                                               | File Name                   |
|----------|-----------------------------------------------------|-----------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.13：Passive Buzzer | microbit-Passive Buzzer.hex |

Or you could edit code step by step in the editing area.

1.  Click “Led”→”more”→“led enable false”, combine it with“on
    start”.![](media/d380f77697920f174fb819fce502f651.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Enter“Music”→“play tone Middle C for 1 beat”， leave it
    into“forever”block，then tap “Middle C”, then
    appear![](media/8288263b500e25e1c888301fc51c7b48.png)code.

Choose“High E”and set to“1 beat”.

![](media/e0ded479a939718548ed9a9879456387.png).

![](media/8eb86db29abd1058de4547b2835f7051.png)

1.  According to the above music score. Copy“play tone High E for 1 beat”124
    times，separately change “High E”of“play tone High E for 1 beat”into“High
    E”,“High F”,“High G”,“High G”,“High F”,“High E”,“High D”,“High C”,“High
    C”,“High D”,“High E”,“High E”,“High D”,“High D”,“High E”,“High E”,“High
    F”,“High G”,“High G”,“High F”,“High E”,“High D”,“High C”,“High C”,“High
    D”,“High E”,“High D”,“High C”,“High C”,“High D”,“High D”,“High E”,“High
    C”,“High D”,“High E”,“High F”,“High E”,“High C”,“High D”,“High E”,“High
    F”,“High E”,“High D”,“High C”,“High D”,“Middle G ”,“High E”,“High E”,“High
    E”,“High F”,“High G”,“High G”,“High F”,“High E”,“High D”,“High C”,“High
    C”,“High D”,“High E”,“High D”,“High C”,“High C”,“High D”,“High D”,“High
    E”,“High C”,“High D”,“High E”,“High F”,“High E”,“High C”,“High D”,“High
    E”,“High F”,“High E”,“High D”,“High C”,“High D”,“Middle G”,“High E”,“High
    E”,“High E”,“High F”,“High G”,“High G”,“High F”,“High E”,“High C”,“High
    C”,“High C”,“High D”,“High E”,“High D”,“High C”,“High C”,“High D”,“High
    C”,“High C”,“High G”,“High F”,“High E”,“High E”,“High C”,“High B”,“High
    A”,“High A”,“High F”,“High D”,“High C”,“Middle B”,“High D”,“Middle
    B”,“Middle A”,“Middle G”,“Middle A”,“Middle B”,“High C”,“High E”,“High
    D”,“Middle B”,“High C”,“High C”,“High C”,“High C”.

Then set beat
to“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1/2”,“1”,“1”,“1”,“1/2”,“1/2”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1/2”,“1”,“1”,“1”,“1/2”,“1/2”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1”,“1/2”,“1”,“1”,“1/2”,“1”,“1”,“1”,“1/2”,“1”,“1”,“1”,“1/2”,“1”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1/2”,“1”,“1/2”,“1/4”,“1”.

Complete Program：

| ![](media/92a9ebb890e32033434669765286d176.png) |
|------------------------------------------------------------------------------------------------|
|                                                                                                |

| ![](media/bfb63d87ff6b10a71dc5aaec192e2029.png) |
|------------------------------------------------------------------------------------------------|
|                                                                                                |

| ![](media/79acaee4559fadfc7c1278d03dbef0d8.png) |
|------------------------------------------------------------------------------------------------|
|                                                                                                |

| ![](media/20a0a38a3b4bf3aa73e58a97061c541d.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript", you will view the corresponding JavaScript code:

![](media/97d220b732aa630a4dfc3d7891469af5.png)

![](media/cc1aa8edafe1e32897fac847385d2d39.png)

![](media/9c20144ddf8d1b3c788768b480dbb07f.png)

**4 .Test Results：**

Download code to micro:bit board and dial POWER switch to ON end. The“Ode to
Joy” is played by passive buzzer

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 14: RGB Experiments

![](media/671b9bd2f40e6c6509399f93794fbda5.png)

1.  **Description：**

The RGB color mode is a color standard in the industry. It obtains various
colors by changing the three color channels of red (R), green (G), and blue (B)
and integrating them. RGB denotes the three colors of red, green and blue.  
The monitors mostly adopt the RGB color standard, and all the colors on the
computer screen are composed of the three colors of red, green and blue mixed in
different proportions. A group of red, green and blue is the smallest display
unit. Any color on the screen can be recorded and expressed by a set of RGB
values.

Each of the three color channels of red, green, and blue is divided into 256
levels of brightness. At 0, the "light" is the weakest-it is turned off, and at
255, the "light" is the brightest. When the three-color gray values are the
same, the gray tones with different gray values are produced, that is, when the
three-color gray is 0, the darkest black is generated; when the three-color gray
is 255, it is the brightest white tone .

| Color                                     | RGB value（R,G,B） | Color code | Color    | RGB value（R,G,B） | Color code |
|-------------------------------------------|--------------------|------------|----------|--------------------|------------|
| Black                                     | 0,0,0              | \##000000   | Red      | 255,0,0            | \##FF0000   |
| Green                                     | 0,255,0            | \##00FF00   | Blue     | 0,0,255            | \##0000FF   |
| indigo                                    | 0,255,255          | \##00FFFF   | Dark red | 255,0,255          | \##FF00FF   |
| Yellow                                    | 255,255,0          | \##FFFF00   | White    | 255,255,255        | \##FFFFFF   |
| ......                                    | .......            | ......     | ......   | ......             | ......     |
| Adjust the numbers to get gradient colors |                    |            |          |                    |            |

RGB colors are called additive colors since the adding of R, G, and B together
(that is, all light reflect back to the eye) produces white color. Additive
colors are used for lighting, television and computer displays. For example,
displays produce color by emitting red, green, and blue rays. Most visible
spectra can be expressed as a mixture of red, green and blue (RGB) light in
different proportions and intensities. If these colors overlap, they produce
cyan, magenta and yellow.

We will make two experiments, one is that two RGB LEDs light up red, green,
blue, indigo, dark red, yellow and white color, another one is that RGB lights
display color in gradient way.

**2. Experimental Preparation：**

(1) Insert micro:bit board into slot of V2 shield.

(2) Place batteries into battery holder.

(3) Dial power switch to ON end

(4) Connect micro:bit to computer by USB cable and open online Makecode editor.

Import Hex profile [**(How to import?)** ](##_7.6.导入代码) , or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3. Test Code：**

**Code 1**

RGB lights show seven colors

| Type     | Route                                                       | File Name           |
|----------|-------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.14：RGB Experiments/Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  Click“TurtleBit”to drag“LED brightness 0”into“on start”block

The larger the number you set, the brighter the RGB gets

Here, we set to 70

![](media/9676fe53d37c492b3e901bb000eaf01d.png)

1.  Click“TurtleBit”to drag“set RGBled left_side R：0 G：0 B：0”block
    into“forever”

Set R:255 G:0 B:0

![](media/ce5ecd39c540e84bd4260f0ced4d0799.png)

(3)Click“TurtleBit”to move“set RGBled left_side R：0 G：0 B：0”
into“forever”block.

Tap left_side to choose right_side, change R:0 into R:255

![](media/5ddb79e8ff2c9b817c3054072b9cec1e.png)

(4) Click“Basic”to drag“pause (ms) 100”block into“forever”

Delay in 1000ms

![](media/82a3c8d2c7527bc6de2eede1786f0e92.png)

(5) Copy code string![](media/aaefe99121025923fa70df52ed5abc9e.png)for six times
and separately place them into“forever”block.

Respectively set to“R：0 G：255 B：0”,“ R：0 G：0 B：255”,“ R：0 G：255
B：255”,“ R：255 G：0 B：255”,“ R：255 G：255 B：0” and “ R：255 G：0 B：255”.

![](media/036dfedb514fdeb04129976957e1a048.png)
![](media/3f38aad265f76920892461d79f8d4226.png)
![](media/f0f41147d30e8b1e0d38a450fce75ce2.png)

Complete Code

| ![](media/f2a1d33c4557567a85ae04026b22d9d2.png)       |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                     |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/1574595b9922866ee9b38afbb0e92668.png)

![](media/2967654276eee586a76b518c71bd89c4.png)

![](media/7a6ac740b8f4f42110519bdba53d1440.png)

**Code 2：**

| Type     | Route                                                       | File Name           |
|----------|-------------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.14：RGB Experiments/Code-2 | microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

1.  Go to“TurtleBit”to move block“LED brightness 0”into“on start”

Change 0 into 200

![](media/fb0b8de118d8df3f4679e4f7a6fe16a9.png)

1.  Go to“Variables” →“Make a Variable...”→“New variable name：” dialog box，

2.  Input“led-r”and click“OK”to produce variable“led-r”，

Then set variable“led-g”and“led-b”in same way.

Move block“set led-b to 0”into“on start”

Copy“set led-b to 0”block twice and set to led-r, led_g and led_b

![](media/f90fc89be465de7b8f3bb5b7e2581045.png)

1.  Go to“Loops”to drag block“repeat 4 times do”into“forever”

![](media/0b59ea27321aeb7681aeba8b581d0305.png)

1.  Tap“TurtleBit”to drag block“set RGBled left_side R：0 G：0 B：0”into “repeat
    4 times do”block.

Copy it once, and change blocks as follows:

![](media/75f2cb5f1981041a7c9f395f8c8583e6.png)

1.  Move block“pause (ms) 100”from“Basic”and place it into“repeat 4 times do”.

![](media/73fa01818b5b7d8ef162ae4fa1c76229.png)

1.  Enter“Variables”to move block“change led-b by 1”under block“pause (ms) 100”.

Click triangle to change led-b into led-r.

The R value is in the range of 0-255, and we make variable“led-r”increases by 5
every time. Therefore, 51 times in total.

Set“repeat 51 times”and“by 5”.

![](media/a7ffc37f761d486305ff43ad49429997.png)

1.  Copy code string ![](media/a7ffc37f761d486305ff43ad49429997.png)once and
    leave it into“forever”.

To make RGB get darker gradually, we set“led-r by -5”, 51 times in total

So we change 5 into -5.

![](media/63f48c6226067758b774f499aeba369c.png)

1.  Replicate ![](media/63f48c6226067758b774f499aeba369c.png)once and keep them
    into“forever”block. Set R:0 and G: led-g, as shown below:

![](media/f3b69e1955bc1d5ead6716de06cf846a.png)

1.  Copy![](media/63f48c6226067758b774f499aeba369c.png)again, and set code
    string as follows:

    ![](media/d029b97ff52089727a04f60a835c2d92.png)

Complete Code

| ![](media/aa1d9e32c7717aae7adc1cbb1781b9ea.png) |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                  |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/567b081bdfe79e8f29885f74ad55472f.png)

![](media/7bb098127c5f4236a62ac09a96ca3f9e.png)

![](media/b7d31c9613724ff3fa5b756881d84f1a.png)

**4.Test Results：**

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Download code 1 to micro:bit board and dial POWER switch to ON end, 2 RGB lights
of smart car emit red, green, blue, indigo, dark red, yellow and white color
cyclically.

Download code 2 to micro:bit board, 2 RGB lights show different color
cyclically.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 15: WS2812 RGB

![](media/b6f9010d508b3d2dadb50ae5175bd4ea.png)

**1.Description：**

The driver shield cooperates 4 pcs WS2812 RGB LEDs, compatible with micro:bit
board and controlled by P8. In this lesson, we will make RGB LEDs display
different colors by P8

**2. Experimental Preparation：**

(1) Insert micro:bit board into slot of V2 shield.

(2) Place batteries into battery holder.

(3) Dial power switch to ON end

(4) Connect micro:bit to computer by USB cable and open online Makecode editor.

Import Hex profile [**(How to import?)** ](##_7.6.导入代码) , or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3. Test Code：**

**Code 1：**

| Type     | Route                                                  | File Name           |
|----------|--------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.15：WS2812 RGB/Code-1 | microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB
    (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to
P8.

d. Smart car has 4 pcs WS2812 RGB lights, so set to 4 leads

![](media/253b37d2d45744f944fc3521af50855c.png)

1.  Click“Neopixel”to move block“strip clear”into“on start”block.

    ![](media/9287db5ccffb51dd82e5d2a15d2fd2fc.png)

2.  Enter“Neopixel”to move block“strip show color red” into “forever” block

    ![](media/88de3d44c971c2369711430a893d7821.png)

3.  Click“Basic”to move“pause (ms) 100”block into“forever”block

Then set to 1000ms

![](media/ba93a1de285dc713513a788b420e3ce6.png)

1.  Copy code string ![](media/e553a68f56eba016892b29528e711907.png)for eight
    times, and click red to respectively set to orange, yellow, green, blue,
    indigo, violet, purple and white.

1.  Tap the triangle icon to select orange, yellow, green, blue, indigo, violet,
    purple and white.

![](media/156cd64dce0b25f741f7d2f9a08f8e5d.png)

Complete Code

| ![](media/b2cdf8ccae177a77965bb692e7f0bff1.png)     |
|-----------------------------------------------------|
|                                                     |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/b6d38140d551a1c946e82f1da11edb1c.png)

**Code 2：**

| Type     | Route                                                  | File Name           |
|----------|--------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.15：WS2812 RGB/Code-2 | microbit-Code-2.hex |

1.  a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB
    (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to
P8.

d. Smart car has 4 pcs WS2812 RGB lights, so set to 4 leads

![](media/1b10418150f245ba56a4208755729094.png)

1.  Click“Loops”to drag“for index from 0 to 4...do”into“forever”block

Change 4 into 3

![](media/9c42b551fc532d473414871e64c8a5ee.png)

1.  Click“Neopixel”to move block“strip clear”into block“for index from 0 to
    3...do”

![](media/aa478b7456e1860d1665cab16014fc13.png)

1.  Tap“Neopixel”→“more”→“strip set pixel color at 0 to red”

Place it into“for index from 0 to 3...do”block

Click“Variables”to move“index”into 0 box

![](media/360081c03f2f475441c442a601334ce2.png)

(5) Click“Neopixel”to move“strip show”into“for index from 0 to 3...do” block

![](media/51d0ac03e131f1c42b67f4fd2631a7a0.png)

(6) Tap“Basic”to move “pause (ms) 100”block into“index from 0 to 3...do”

![](media/eda2a23160cf34a76c1f4ab73118151d.png)

1.  Replicate code string![](media/b8590766809462fa433eb907d60e8908.png)for
    eight times and place them into“forever”block

Click red to respectively choose orange, yellow, green, blue, indigo, violet,
purple and white

Complete Code：

| ![](media/f06b9905088a3d39373f78c947e64be3.png)  |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                      |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/e504dfc47f7d7bdd5f55e8d191e10ed2.png)

![](media/7ef1503e633be63a18bb5128f0784a6e.png)

**Code 3：**

| Type     | Route                                                  | File Name           |
|----------|--------------------------------------------------------|---------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.15：WS2812 RGB/Code-3 | microbit-Code-3.hex |

Or you could edit code step by step in the editing area.

1.  a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB
    (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to
P8.

d. Smart car has 4 pcs WS2812 RGB lights, set to 4 leads

![](media/1b10418150f245ba56a4208755729094.png)

1.  Click“Variables”→“Make a Variable...”

Input R to build up variable R

We create variable“G”and“B”in same way

Drag“set B to 0”into“on start”block

Copy“set B to 0”twice and click triangle button to choose G and B

![](media/0e2475d942586c2733a8fced49c3b26b.png)

1.  Click“Loops”to get block“for index from 0 to 4...do”

Leave it into “forever”and change 4 into 3

![](media/00751ac422252c11b90e88d1dd5e5e1b.png)

1.  Move block“set B to 0”into“for index from 0 to 3...do”block,

Click B to choose R

Go to“Math”to drag block“pick random 0 to 10”into 0 box

Change 0 into 10, 10 into 255

![](media/808240f2784ec6bf5cd696813178ad51.png)

1.  Replicate block ![](media/141700e2baf4f6ec06126a7eabdd15c3.png)twice and
    place them into“for index from 0 to 3...do”block.

Click R to select G and B

![](media/18c0be6843e83bf51f99c240d0faa45c.png)

1.  Tap“Neopixel”and move“strip clear”into“for index from 0 to 3...do” block.

    ![](media/cbc6b59e73365b0038a11a465b775f18.png)

2.  Go to“Neopixel”→“more”→“strip set pixel color at 0 to red”

Leave it in the block“for index from 0 to 3...do”block

Drag block“red 255 green 255 blue 255”into“red”box

Tap“Variables”to move“index”block into 0 box

Separately drag R , G and B into 255 box, as shown below:

![](media/965b62ff435a6c5b35ef77745474b976.png)

1.  Click“Basic”to drag“pause (ms) 100” under block “strip.....B”

Set to 500ms.

![](media/ef0a30f6ea2627dbee666c6a7139c404.png)

1.  Click“Neopixel”to move“strip show”block under “pause(as) 500”

    ![](media/7d0ee3ddfa68a63b292c77709dc20e89.png)

Complete Code:

| ![](media/9004a799ddf2a0d952d4174efade0410.png)  |
|--------------------------------------------------|
|                                                  |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/a2680aaeb505419bb229de36ffc8a48d.png)

**4.Test Results：**

Download code 1 to micro：bit, and dial POWER to ON end. WS2812RGB LEDs light up
different colors cyclically.

Download code 2 to micro：bit, WS2812RGB LEDs display like flow light.

Download code 3 to micro：bit, every WS2812RGB light shows random color one by
one.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 16: Motor Driving

![](media/d2ed0e8b2d7ebe9d169a79ca22fcccf9.png)

1.  **Description：**

Keyestudio micro：bit smart car is equipped with two DC geared motors which are
added a gearbox based on regular DC motors.

Gear motor is the integration of gearmotor and motor, which is applied widely in
steel and machine industry

Micro:bit motor driver shield comes with PCA9685PW and TB6612FNG chip，to save
the IO port resource，we control the rotation direction and speed of two DC gear
motors with TB6612FNG chip.

![](media/54b5e5e52d58030a651ce560f2128c85.png)

![](media/02e6c39452ef2e16b69eae1ba34b31e3.png)

![](media/347433de52768b6d5b90bc7d016e8125.png)

**Note: please follow the direction of eight jumper caps inserted.**

**In this way, the rotation direction is as same as the set rotation orientation
in the code**

![](media/36c335fa3978a716de9f40996175be17.png)

**The picture below is wrong inserted direction of jumper caps**

![](media/a491869c9cf3c40db4a7b813c925b880.png)

**2. Experimental Preparation：**

(1) Insert micro:bit board into slot of V2 shield.

(2) Place batteries into battery holder.

(3) Dial power switch to ON end

(4) Connect micro:bit to computer by USB cable and open online Makecode editor.

Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3. Test Code：**

**Code 1：**

| Type     | Route                                                     | File Name            |
|----------|-----------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.16: Motor Driving/Code-1 |  microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  Click“Led”→“more”→ “led enable fasle”

Leave it into“on start”

Tap“false”to select“true”

![](media/6590ae2935dd6d4e9cb2b289c3b37084.png)

1.  Click“Basic”to get block“show arrow North”

Leave it into“forever”block

Click North to select South

![](media/4d1ddbeb0077fc305ecd77739436bcc5.png)

1.  Click “TurtleBit”to drag“car Run_forward speed : 0 %”block

Place it into“forever”block

Change 0 into 100.

![](media/fb12c5c2df0f403b5d57e854f71c374b.png)

1.  Tap“Basic”to move“pause (ms) 100”block into“forever”block

Delay in 100ms

![](media/e34f2cc3bd63b84366240248fc84616b.png)

1.  Replicate code string![](media/ca02286b36d12d805882c0ee057cff1a.png)once and
    leave it under “pause (ms) 100”block

Change South into North and Run_forward into Run_back

![](media/a13eef1798459121ed58d4178c332b9e.png)

1.  Copy“show arrow South”once and keep it under block“pause (ms) 100”.

2.  Change South into East.

![](media/55c7f698b52c163f5b34fd1a03c568e8.png)

1.  Click“TurtleBit”to move“LeftSide motor run Forward speed : 0 %”and copy it
    once

2.  Place them under“show arrow East”block

3.  And copy“pause (ms) 1000”block once

4.  Set the code string as follows:

![](media/b7c3e25509ea18970aea03cb09e52818.png)

1.  Duplicate code string ![](media/1a02ef2ff4393cab95ac90bc124ea0cd.png)once
    and keep it under“pause (ms) 1000”block

Change East into West, 50 into 100 and 100 into 50

![](media/896dd0ec877a1df1a049b02ab6aa873c.png)

1.  Copy code string ![](media/ca02286b36d12d805882c0ee057cff1a.png)twice,

Place them into“forever”block

Click South to select East and West

Tap Run_forward to select Turn_Left and Turn_Right

![](media/916806895e3b9ddd70244736eaf0fd6a.png)

1.  Tap“Basic”to drag block“show leds”into“forever”

Tick blue boxes to generate“❤”pattern

![](media/976086e8851de6c1f59260891821494d.png)

1.  Tap“TurtleBit”to drag“car stop”into“forever”block

Copy“pause (ms) 1000”once and leave it under“car stop” block

![](media/7905b106db75470bfadf14ff21bdc574.png)

Complete Code:

| ![](media/47b933acfcf78da0928f68e3dd3e7103.png) |
|-------------------------------------------------------------------------------------------------|
|                                                                                                 |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/429936cd5d78b4363728091faa186558.png)

**Code 2：**

| Type     | Route                                                     | File Name            |
|----------|-----------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.16：Motor Driving/Code-2 |  microbit-Code-2.hex |

Or you could edit code step by step in the editing area.

1.  Click“Led”→“more”→“led enable false”,

Put it into block“on start”，click drop-down triangle button to select“true”
![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png).

1.  Click“Variables”→“Make a Variable...”

Input “a” and click“OK”, variable “a” is built

Then create the variable “b” in same way

Drag“set b to 0”into“on start” block, change b into a

Copy“set b to 0”once and leave it under“set a to 0”

![](media/53415ea0bf2490067f8f70bd77e4c834.png)

1.  Click“Input”to drag out“on button A pressed”

Tap“Variables” to move“change b by 1”into“on button A pressed”block, and change
b into a.

![](media/39498de4dcb936e8a2b8c797cb20a925.png)

1.  Copy code string![](media/0331033b05df17207cf8687f184a2397.png)once,
    delete“change a by 1”block

Change A into B

Tap“Variables”to drag“set b to 0”into“on button B pressed”

Alter 0 into 1

![](media/91c1545a33f45f0af14ebc9edd2e6a68.png)

1.  Click“Logic” to move“if true then...”into“forever”block

Drag“=”block into“true”box

Tap“Variables”to move variable“a”to left box of “=”, and change 0 into 1.

![](media/f7e04a36746c6ad747c9b02214c7dc89.png)

1.  Click“Basic”to drag“show leds”under then block

    Tick blue box to generate “L”

    ![](media/9ead6a84f4e443fd7edbb811fd9979e6.png)

2.  Click“Logic”to get“if true then...”block

Leave it under block “if..then” block

Go to“Variables”to move block“b”to left box of “=”block

Change 0 into 1

![](media/cac9459815f822f86c09f66199150cc5.png)

1.  Click“Basic”to get block“pause (ms) 100”

Leave it into “if..then” block

Click“TurtleBit”to move“car Run_forward speed: 0 %”under block“pause (ms)
100”and change 0 into 100

Copy“pause (ms) 1000”block and leave it under “car...100%” block.

![](media/9576664d367111b275d9dd3de0854c42.png)

1.  Copy![](media/2a056c289af63a527909737b33850d9a.png)once and leave it
    under“pause (ms) 100”block

Change Run_Forward into Turn_Left, 100 into 50 and delay in 600ms

![](media/59cf38c416120a30bf9e350fa79d6bbe.png)

1.  Duplicate code string![](media/2a056c289af63a527909737b33850d9a.png)once,
    keep it under “pause (ms) 600”block

    ![](media/0b6e3f3396c513585d62bc4c6316515f.png)

1.  Tap “TurtleBit”to drag“car stop”block under block“pause (ms) 1000”

Tap“Variables”to move“set b to 0”block under “car stop” block

![](media/718bf7f479098e3235bf2a6d2a5b53ad.png)

1.  Click“Logic”to drag“if true then...”into“forever”

Move“=”block into“true”box

Click“Variables”to move“a”to left box of “=”and change 0 into 20

![](media/23611d89366f71deaaddac0918a4d995.png)

1.  Click“Basic”to drag“show leds”into the third “if..then” block

Tick blue boxes to produce“口”

![](media/06becb0f5a774bcbea61b11d95ca1504.png)

1.  Go to“Logic”to drag“if true then...”block

Keep it under“show leds 口” block

Move variable b into left box of “=” block and change 0 into 1

![](media/b86a5fb5d12a28604a0bc38239414419.png)

1.  Tap“Basic”to drag“pause (ms) 100”and copy it once

Set to 1000ms

Tap“TurtleBit”block to drag out“car Run_forward speed: 0 %”block

Change 0 into 100

Then set the code string as follows:

![](media/9b93142170e6526d94218c6cb53930ba.png)

1.  Duplicate code string ![](media/2a056c289af63a527909737b33850d9a.png)once

Change Run_Forward into Turn_Left, 100 into 50 and 1000 into 600

Place it into code sting, as shown below

![](media/4240283b1bbe2d8babee1eb99206bbd4.png)

1.  Replicate code string ![](media/c4fd84dc1edc3fe2a37e776e6beb9a56.png) twice
    and keep them in the code string as follows:

    ![](media/52a3d36584c9f3b73c5dcf7cd19c5dab.png)

（18）Copy code string![](media/7e9c2fd43e3d4abea9aee62d0f15501d.png)once, and
leave it under “ pause(as) 600” block

![](media/07ee20368dc3e6b7c96ffd2a2e07e57d.png)

1.  Copy“if a=2 then”block once and change 2 into 3

Tap “Variables”to move“set b to 0”into “if a=3 then”block

Alter b into a and 0 into 1

![](media/2c45ff59dc643f98ab658c21bd502d5e.png)

Complete Code:

| ![](media/acecf0e8be4e2606034cf604d1322d57.png) |
|-------------------------------------------------|
|                                                 |

| ![](media/5eb8509d58df4e47adb95a98ffea48cc.png) |
|--------------------------------------------------------------------------------------------------|
|                                                                                                  |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/8208c1cea5697e72db7a448a46339db5.png)

![](media/1189dfdc08605a94c2c55921c769dbe7.png)

**4.Test Results：**

Download code 1 to micro:bit board, dial POWER switch to ON end. Smart car goes
forward for 1s, backward for 1s, turns left for 1s, turns right for 1s, rotates
anticlockwise for 1s, clockwise for 1 and stops for 1s. And dot matrix displays
the corresponding patterns

Download code 2 to micro:bit board, “L”will be shown on dot matrix when A button
is pressed, then press B, the route of smart car is “L”type.

“口”will be displayed when the Button A is pressed again, then press B, the
route of smart car is “口”type.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

### 17: Line Tracking Smart Car

**8.17.1: Detect Line Tracking Sensor**

![](media/635b8724dc3e7a27f940b3953ed4536d.jpeg)

**1. Description：**

The V2 expansion board of keyestudio micro：bit mini smart robot car comes with
two line tracking sensors which adopt TCRT5000 IR tubes.

TCRT5000 IR tube has an IR emitting tube and a receiving tube.

Low level(0) is output when IR transmitting tube emits IR signals to receiving
tube; high level(1) will be output when smart car runs along black line.

When smart car drives on the white ground, TCRT5000 IR tube will emit IR signals
which will be reflected by white ground and received by receiving tube,
consequently output low level(0); on the contrary, when driving on the black
surface, the high level is output.

The left and right line tracking sensors are respectively controlled by P12 and
P13.

Put a paper under the bottom of car, adjust the potentiometers on shield to
adjust sensitivity. When D2 and D6 are on, then pull up the universal wheels for
0.5cm off the paper. The sensitivity is set well if D2 and D6 are off

**2. Experimental Preparation：**

(1) Insert micro:bit board into slot of V2 shield.

(2) Place batteries into battery holder.

(3) Dial power switch to ON end

(4) Connect micro:bit to computer by USB cable and open online Makecode editor.

(5) Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3. Test Code：**

**Code 1：**

| Type     | Route                                                                                                  | File Name            |
|----------|--------------------------------------------------------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.17: Line Tracking Smart Car/8.17.1:Detect Line Tracking Sensor/Code-1 |  microbit-Code-1.hex |

Or you could edit code step by step in the editing area.

1.  Click“Advanced”→“Serial”→“serial redirect to USB”

Place it into“on start”

![](media/73b63660eb8f378dea4930f354d04de6.png)

1.  Enter“Advanced”→“Serial”→“serial write value“x”=0”

Leave it into“forever”block.

Go to“Pins”→“digital read pin P0 ”

Move“digital read pin P0”into 0 box

The right tracking sensor is controlled by P14. Then change P0 into P14
and“x”into“digital signal”.

![](media/fe7822df66e47c1feb6b949d44e5ad95.png)

1.  Go to“Basic”→“pause (ms) 100”

Keep it into“forever”block and set to 200ms.

![](media/0b9551558282e2c296a7c101f24e5c0a.png)

Complete Program：

| ![](media/98fabe22eb5d7a05d82e442d64e74fe7.png)  |
|--------------------------------------------------|
|                                                  |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/99713bf570bdcfaefaa0982944f73da6.png)

Download code 1 to micro:bit board, don’t plug off USB cable and
click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?](##_7.3.快速下载))

![](media/830072d6e2029a76637886938d22f900.png)

Serial monitor will display low level(0) and left indicator will be on when the
left TCRT5000 IR tube detects white objects, black objects or no object are
detected by left TCRT5000 IR tube, 1(high level) will be shown on serial monitor
and indicator will be off, as shown below:

![](media/c8fb471be9d430db24ecc3cc7162850d.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate. Click“OK”and“Connect”.

The CoolTerm serial monitor displays the digital signals read by right line
tracking sensor.

![](media/e7703bb10f45bac4033ab44958dcb248.png)

**Code 2：**

| Type     | Route                                                                                                  | File Name            |
|----------|--------------------------------------------------------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.17: Line Tracking Smart Car/8.17.1:Detect Line Tracking Sensor/Code-2 |  microbit-Code-2.hex |

1.  Click“Led”→“more”→“led enable false”,

Put it into block“on start”，click drop-down triangle button to select“true”
![](media/4aa8c2a812adecff90a9d4a33d8858a5.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Go to“Variables” →“Make a Variable...”→ “New variable name：” dialog box.

Enter LL and click“OK”to create variable“LL”.

Next to produce variable“RR”in same way.

Drag block“set RR to 0”into“on start”block and copy it once. Then set code
string:![](media/b9ece15dd38d0e45c855b56784e849a6.png)

1.  Click“Variables”to drag block“set RR to 0”into block“forever”

Tap RR to select LL

Tap“Advanced”→“Pins”→“digital read pin P0”

Place“digital read pin P0”into 0 box

Copy“set LL to digital read pin P0”twice and keep them into “forever” block.

Separately change into CC and RR

The three TCRT5000 IR tubes of line tracking sensor are controlled by P14, P15
and P16, therefore we set to code string as follows:

![](media/74edd1154946c84d13d1a91db859462d.png)

1.  Click“Logic” to drag“if true then...else”block into“forever”block

Tap“![](media/7498c9151101cb7e9756a8b0a5485f90.png)”for six times and
move“and”block twice and place them into true boxes, as shown below:

![](media/b77c13729be593a8a648ef50afc3c333.png)

1.  Go to“Logic”to move block“=”into left box of the first and block

Click“Variables”to drag“LL”into left box of “=”block

Copy“LL=0”twice and respectively leave them into boxes of the second and block
and change 0 into 1, as shown below

![](media/e5886652fd64054719be00a0cd98a151.png)

1.  Click“Basic”to move block“show leds”under “if....then” block

Copy it twice and respectively leave them under the first and second “else
if....then” block

Replicate“LL=0 and CC=1 and RR=1”twice and edit code string as follows:

![](media/8fb55aedeaf202eb06bd90d0761c5828.png)

1.  Duplicate“LL=1 and CC=1 and RR=0”again and leave it into box behind the
    third else if block

Set“LL=0 and CC=0 and RR=1”

![](media/484fd7ed40fc0c7bff2340ed6803bcc2.png)

1.  Click“Basic”to move block“show icon”under the fourth“else if...then” block

Click the triangle button to
select“![](media/2460d7af23daf89d2ee7b245ff86553b.png)”

![](media/84fe8e148b9d94612cb063090e378057.png)

1.  Copy“LL=0 and CC=0 and RR=1”for three times and block“show icon” for four
    times

1.  Edit the code string as follows:

![](media/a33a4ce643daa75acd0d264223abcb8b.png)

Complete Code：

| ![](media/06f2f4c6916407a5f44c77a27d1b65cb.png)” When the above condition is not met, execute the program under else block Micro:bit shows“❤”   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/8704cc805722c33d2ec3932d21b3cdfe.png)

![](media/e3d0cb549c86e517b96bb03fec7026b5.png)

**Code 3：**

We could use block“![](media/1dc4bbb19e0ebf13c9f17cce2beba90e.png)”to simplify
code 2. The digital signal read by line tracking sensor is 0(low level) and
1(high level).

Then we transfer the digital signals from line tracking sensor into binary and
decimal system, as shown below:

|  Level of left, middle and right TCRT5000 IR Tube |  Binary   | Decimal system |     |   |
|---------------------------------------------------|-----------|----------------|-----|---|
| Low（0）                                          | Low（0）  | High（1）      | 001 | 1 |
| Low（0）                                          | High（1） | Low（0）       | 010 | 2 |
| Low（0）                                          | High（1） | High（1）      | 011 | 3 |
| High（1）                                         | Low（0）  | Low（0）       | 100 | 4 |
| High（1）                                         | Low（0）  | High（1）      | 101 | 5 |
| High（1）                                         | High（1） | Low（0）       | 110 | 6 |
| High（1）                                         | High（1） | High（1）      | 111 | 7 |
| Low（0）                                          | Low（0）  | Low（0）       | 000 | 0 |

| Type     | Route                                                                                                   | File Name            |
|----------|---------------------------------------------------------------------------------------------------------|----------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.17：Line Tracking Smart Car/8.17.1：Detect Line Tracking Sensor/Code-3 |  microbit-Code-3.hex |

Or you could edit code step by step in the editing area.

1.  Click“Advanced” →“Serial”→“serial redirect to USB”

Place it into“on start”block.

![](media/73b63660eb8f378dea4930f354d04de6.png)

(2) Click“Variables”→“Make a Variable...”→“New variable name：”dialog box;

Input val and click“OK”to generate variable“val”

Move out“set val to 0”and keep it into block“on start”

![](media/1f2fdc5429f535da4043fcd9230d3e80.png)

(3) Enter“Variables” →“set val to 0”

Keep it into “forever” block

Move“Line Tracking”from“TurtleBit”and place it into 0 box

![](media/25edba24da8569a03b56bbd92137bd09.png)

(4) Click“Advanced”→“Serial”→“serial write value“x”=0”

Put it into“forever”，and move variable “val”into 0 box.

![](media/0ff4b9133dda167863bbf73f6a765d60.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Logic”→“if true then...else”

Move it into“forever” , tap“![](media/7498c9151101cb7e9756a8b0a5485f90.png)” six
times and move out “=” block into “true” block.

![](media/b0f189b22b58f858542b6e0ea88c1695.png)

(6) Enter“Variables”to move block“val”into left box of“=”block

And change 0 into 3.

![](media/028c9513d8bff82590c8854b2765fe0b.png)

(7) Enter“Basic” → “show leds”

Place it under the first block“if..val...then”block

Tick dark blue boxes to generate“I”pattern.

![](media/2b8de2e45133c7df1c7a2578e32bdde2.png)

(8) Copy block“val=3 ”once and place it into box behind the first “else of ...
then” block and change 3 into 5

![](media/5ac4852493c84a39270943756b34653c.png)

(9) Replicate “show leds”block and leave it under the first “else of ...
then”block.

Tick blue boxes to produce“I”

![](media/3b6c38382f83c651b17a8689e1909d64.png)

1.  Duplicate block“val=5 ”and place it into the second box behind the second
    “else if...then” block, change 5 into 6

    ![](media/d7ac03f2a6cd05cc324be619f2f335d5.png)

2.  Duplicate“show leds”once and leave it into box behind the second“else
    if...then”block

Tick blue box to create“I”

![](media/72a10c836b6465b57ecd18f9e125a881.png)

1.  Copy“val=6”block once and leave it into box behind the third“else
    if...then”block

Change 6 into 1

![](media/6f9a0741966608fc10052658440015db.png)

1.  Drag out“show icon”under the third“else if...then”block

Click “❤”to set“![](media/c0ef63598e460f019fbc4d80b011a879.png)”

![](media/b1600d0d028c392d27f48f558ee7c992.png)

1.  Copy“val=1”once and leave it into box behind the the fourth “else if ..then”
    block.

Change 1 into 2.

![](media/c16f8e58dbca31471419d294ff40ce63.png)

1.  Copy block“show icon”for four times and click the triangle button to select
    “![](media/994e46bf4b57c873d3ec56043f4a6413.png)”.

Set to val=1, 2, 4 and 7

![](media/914a6f89243d5bc1b4a1fc0281ac16d3.png)

Complete Code

| ![](media/06f2f4c6916407a5f44c77a27d1b65cb.png)” When the above condition is not met, execute the program under else block Micro:bit shows“❤” |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/1bb8adae7e921dfbe419d3380796e8c4.png)

**3.Test Results：**

Download code 2 to micro:bit board,“I”will be shown at left and indicator will
be on when only left TCRT5000 IR tube on line tracking sensor detects white
objects.

“I”will be shown in the middle and indicator will be on when only middle
TCRT5000 IR tube on line tracking sensor detects white objects.

“I”will be shown at right and indicator will be on when only right TCRT5000 IR
tube on line tracking sensor detects white objects.

As only left and middle TCRT5000 IR tubes detect white objects, micro:bit
shows“![](media/29cf9222b824d836caec029221ef612b.png)”and indicators at left and
middle are on.

Micro:bit shows“![](media/d9020ea20c11e4dd92d59452e6a39481.png)”and indicators
at left and right are on when only left and right TCRT5000 IR tubes detect white
objects.

Micro:bit shows“![](media/fd3df0126ac849ed4b39d614731d9364.png)”and indicators
at right and middle are on when only middle and right TCRT5000 IR tubes detect
white objects.

Micro:bit displays“![](media/502de9d63a87351f5d18b914c8d529c4.png)”and none of
indicator is on when both of them detect black objects or no object is detected.

Both of them detect white objects, micro:bit shows“❤”and indicators are on.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Download code 3 to micro:bit, and keep micro：bit connected and
click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?](##_7.3.快速下载))

![](media/936cc70790090f6553c90be6e0d3edc2.png)

Number 3 will be displayed when only left TCRT5000 IR tube detects white
objects.

Number 5 will be displayed when only middle TCRT5000 IR tube detects white
objects.

Number 6 will be displayed when only right TCRT5000 IR tube detects white
objects.

Number 1 will be displayed when only left and middle TCRT5000 IR tubes detect
white objects.

Number 2 will be displayed when only left and right TCRT5000 IR tubes detect
white objects.

Number 4 will be displayed when only right and middle TCRT5000 IR tubes detect
white objects.

Number 7 will be displayed when all TCRT5000 IR tubes detect black objects or
not object is detected.

![](media/c0b116c7489a72ed64fe419083a12e0f.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of Micro:bit is 115200 through
the test). Click“OK”and“Connect”，

CoolTerm serial monitor display the value of decimal system.

![](media/273f73e5db384e9e6528e0d2268cfa27.jpeg)

**8.17.2: Line Tracking Smart Car**

![](media/a3f42e61efe32f336e9939d9367e24b3.jpeg)

**1.Description：**

In this lesson we will combine line tracking sensors with a motor to make a line
tracking smart car.

The micro:bit board will analyze the signals and control smart car to show line
tracking function.

| Left/Middle/Right TCRT5000  IR Tunes（Level） | binary    | Decimal system (a) | Turtle Smart Car |   |            |
|-----------------------------------------------|-----------|--------------------|------------------|---|------------|
| LOW （0）                                     | LOW （0） | HIGH（1）          | 001              | 1 | Turn Right |
| LOW （0）                                     | HIGH（1） | LOW （0）          | 010              | 2 | Go forward |
| LOW （0）                                     | HIGH（1） | HIGH（1）          | 011              | 3 | Go forward |
| HIGH（1）                                     | LOW （0） | LOW （0）          | 100              | 4 | Turn Left  |
| HIGH（1）                                     | LOW （0） | HIGH（1）          | 101              | 5 | Go forward |
| HIGH（1）                                     | HIGH（1） | LOW （0）          | 110              | 6 | Go forward |
| HIGH（1）                                     | HIGH（1） | HIGH（1）          | 111              | 7 | Go forward |
| LOW （0）                                     | LOW （0） | LOW （0）          | 000              | 0 | Stop       |

![](media/7abb567990baeeb9bb4694b578c1f670.png)

The three-channel line tracking sensor is connected to integrated pin(G,5V P14,
P15, P16) and controlled by P14, P15 and P16.

**2. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

Warning: the line tracking sensor can't work normally under strong light because
there is a mountain of invisible light including IR and ultraviolet rays.

**3. Flow Chart**

![](media/709a8231ea58a18afb6627ae2f79c449.png)

**4. Test Code：**

| Type     | Route                                                                      | File Name                            |
|----------|----------------------------------------------------------------------------|--------------------------------------|
| Hex file | ../Test Code/8.17：Line Tracking Smart Car/8.17.2：Line Tracking Smart Car | microbit-Line Tracking Smart Car.hex |

Or you could edit code step by step in the editing area.

1.  Enter“Basic”→“show icon ♥”

Combine it with“on start” block，and click triangle button to select
“![](media/b9b97ec13c745120243516b57a2f2fbc.png)”.

![](media/4e8ed8afa7457e273982b6f884567de7.png)

1.  Click “Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB (GRB
    format)”

Put it into“on start”block，P8 of 4pcs WS2812RGB lights is connected by P8 of
micro:bit.

Click the triangle button to set to P8 and set to 4 leads

![](media/aba9f94670bfd5c79641bf508a25289d.png)

1.  Enter“Neopixel”→“strip clear”

Place it into“on start”

![](media/9ddcb4020018c4889cb46ae4933a01a1.png)

1.  Go to“Variables”→“Make a Variable...”→“New variable name：”

Enter“tracking values”and click“OK”, then variable“tracking values”is set up.

Drag“set tracking values to 0”into forever block.

Tap turtle-bit to move“Line Tracking”block into 0 box.

![](media/4fe0740ac0770f2fa3ba8e7db844d1ed.png)

1.  Click“Logic”and drag“if true then...else”under the block“set...tracking”.

Tap“![](media/08875ea2865d2ebad8c6bb016f6b4531.png)”twice, move“or”block into
true box, then copy “or” block for three times and leave them into right box
of“or”block.

![](media/a452f079f2511105c5c6d89c79428a29.png)

1.  Tap“Logic”to drag out“=”and leave it at left box of“or”block

Click“Variables”to move“tracking values” into right box of“=”block.

Change 0 into 2

Copy“tracking values=2”for four times, and separately leave them into boxes as
follows:

Change 2 into 3, 5, 6 and 7

![](media/143e566e7c34dfcb1fd48009c99c5877.png)

1.  Click“TurtleBit” to drag“car Run_forward speed: 0 %”under “if....then” block

Change 0 into 60

Tap“Neopixel”to get block“strip show color red”

Change red into green

Leave“strip show color green”under “car....68%”block

![](media/78cde8e1cdbb8b9e7f629a1472ee9b2c.png)

1.  Duplicate block“tracking values=2”once and place it into box behind the
    first“else if”block, change 2 into 4.

![](media/b0ebb210b2a440b2adc5356976ae0440.png)

1.  Click“TurtleBit”to drag“LeftSide motor run Forward speed: 0 %”

Copy it once and leave them under the“else if....then”block

Then set blocks as follows:

Copy“strip show color green”once and change green into blue.

![](media/2b41a42359ba6f749bc815d6ce7cfbe6.png)

1.  Copy“tracking values=4”once and place it into box behind the second “else
    if”, change 4 into 1.

![](media/96bfc538fbd4a0281d071064e71ce35f.png)

1.  Copy ![](media/20f5fd5ad81eab07fd5e658717dee17b.png)once,and place it under
    the “second else if..then”block

Set the code string as follows:

![](media/ca007599d25dd548525dfcde6198dcd9.png)

1.  Click“TurtleBit”to move“car stop”under the else block

Copy“strip show color yellow”once and alter yellow into red.

Place blocks as follows:

![](media/b0864175d678eef69e65cc4f1d16cac8.png)

Complete Code

![](media/36f5512d772834eb373413d8bc1e9885.png)

![](media/b9b97ec13c745120243516b57a2f2fbc.png)”

Set strip to Neopixel pin 8 with 4 leads(RGB format)

Turn off all RGB on strip

The program under the block“forever”runs cyclically.

Set tracking values to the value read by line tracking sensor

When tracking values=2, 3, 5, 6 or 7, execute the program under then block

Go forward at the 60% speed

4pcs WS2812RGB display green color

When tracking values=4, execute the program under then block.

The left car wheels go back at 80% speed

The right car wheels go forward at 80% speed

4pcs WS2812RGB display blue color

When tracking values=1, execute the program under then block

The left car wheels go backward at 80% speed

The right car wheels go backward at 80% speed

4pcs WS2812RGB display yellow color

When tracking values is not met, execute the program under else block

turtle car stops

4pcs WS2812RGB display red color

“on start”: command block runs once to start program.

Micro:bit shows“![](media/b9b97ec13c745120243516b57a2f2fbc.png)”

Set strip to Neopixel pin 8 with 4 leads(RGB format)

Turn off all RGB on strip

The program under the block“forever”runs cyclically.

Set tracking values to the value read by line tracking sensor

When tracking values=2, 3, 5, 6 or 7, execute the program under then block

Go forward at the 60% speed

4pcs WS2812RGB display green color

When tracking values=4, execute the program under then block.

The left car wheels go back at 80% speed

The right car wheels go forward at 80% speed

4pcs WS2812RGB display blue color

When tracking values=1, execute the program under then block

The left car wheels go backward at 80% speed

The right car wheels go backward at 80% speed

4pcs WS2812RGB display yellow color

When tracking values is not met, execute the program under else block

turtle car stops

4pcs WS2812RGB display red color

Click“JavaScript"to view the corresponding JavaScript code:

![](media/46e4780e27d4491e9d822aaabc1b9054.png)

**6. Test Results：**

Download code to micro:bit and dial POWER to ON end, line tacking car goes
forward along black line and turn on WS2812 RGB lights

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Note: turn on the switch at the back of micro:bit car.

the width of black line should be larger than the width of line tracking sensor.

Avoid to test smart car under the strong light.

### 18: Ultrasonic Follow Smart Car

#### 18.1: Ultrasonic Ranging

**1. Description：**

The HC-SR04 ultrasonic sensor uses sonar to determine distance to an object like
bats do. It offers excellent non-contact range detection with high accuracy and
stable readings in an easy-to-use package. It comes complete with ultrasonic
transmitter and receiver modules.

The HC-SR04 or the ultrasonic sensor is being used in a wide range of
electronics projects for creating obstacle detection and distance measuring
application as well as various other applications.

![](media/ff1da08689889aae8e0bbebf8af74e35.png)

As the above picture shown, it is like two eyes. One is transmitting end, the
other is receiving end.

The ultrasonic module will emit the ultrasonic waves after trigger signal. When
the ultrasonic waves encounter the object and are reflected back, the module
outputs an echo signal, so it can determine the distance of object from the time
difference between trigger signal and echo signal.

**2.Working Principle：**

![](media/8ff02741199a0f03d8d814a4b72f27d7.png)

1.  Pull down TRIG then trigger high level signals with least 10us

2.  After triggering, the module will automatically send eight 40KHz ultrasonic
    pulses and detect whether there is a signal return.

3.  The propagation speed of sound in the air is about 343m/s, therefore,
    distance = speed \* time, because the ultrasonic wave emits and comes back,
    which is 2 times of distance, so it needs to be divided by 2, the distance
    measured by ultrasonic wave = (speed \* time)/2

**3. Specifications：**

-   Working voltage：3-5.5V（DC）

-   Power Supply :+5V DC

-   Working Current: 15mA

-   Working frequency: 40khz

-   Maximum Ranging Distance : around 3m

-   Minimum Ranging Distance: 2-3cm

-   Resolution : 0.3 cm

-   Measuring Angle: ≤15 degree

-   Trigger Input Pulse width: 10uS

-   Accuracy: up to 0.2cm

-   Output echo signal : output TTL level signal(high), which is proportion to
    range.

**4.Experimental Preparation：**

Insert micro:bit board into slot of V2 shield.

Place batteries into battery holder.

Dial power switch to ON end

Connect micro:bit to computer by USB cable and open online Makecode editor.

Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**5.Test Code：**

| Type     | Route                                                                                       | File Name                       |
|----------|---------------------------------------------------------------------------------------------|---------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.18: Ultrasonic Follow Smart Car/8.18.1: Ultrasonic Ranging | microbit-Ultrasonic Ranging.hex |

Or you could edit code step by step in the editing area.

1.  Tap“Advanced”→“Serial” →“serial redirect to USB”

Combine it with“on start”block

![](media/73b63660eb8f378dea4930f354d04de6.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Go to “Variables”→“Make a Variable...”→“New variable name：” dialog box，

Input i and click“OK”to produce variable“i”，

Move“set i to 0”from“Variables”and integrate with“on start”block

![](media/c8496884c822fc69da7e46bc4fc91886.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

![](media/72b73246674e9108049d86185db97b99.png)

1.  Tap“Advanced”→“Serial” →“serial write value x=0”

Place it under“set i to 0”block

Click“TurtleBit”to move“Ultrasonic”into 0 box of “=” block

Change X into distance

![](media/a8360b4e02933f4484130d7c283e6bcf.png)

1.  Click“Logic”to drag“if true then”block into“forever”block.

Move“=”into true box

![](media/d0e6c291314e7865e9ae347a6b081d4f.png)

1.  Click“TurtleBit”to drag“Ultrasonic”to left box of “=”

Change “=” into “\<”, 0 into 10.

![](media/5afdda8a60e793fc38af6957c36097f6.png)

1.  Tap“Loops”to get block“while true do”and place it into forever block

    Click“Logic”to move “=” block into true box

![](media/6224f4a49dde4ccf2b5e6d22965477fc.png)

1.  Click“Variables”to move variable“i”to left box of “=” block

Change“=” into “\<”and 0 into 1

![](media/30f667005e551fe3e872536865c9f237.png)

1.  Click“Music”and move“play tone Middle C for 1 beat”block into do block

Tap“Basic”to move“pause(ms)100”under “play...beat” block

Change 100 into 200

![](media/733a3ad2b53956c7d54a6c43d07b1ff8.png)

Copy ![](media/317c92123340c396e189314146ea318f.png)once and place it into do
block

![](media/3667fca618bf9e6aa218b985a717f23f.png)

Click“Variables”to drag“change i by 1”into do block

![](media/10374fbc53f9b82f81ce9306f4f0a0c2.png)

Complete Code

| ![](media/50d5c3d5a0fa4e841dbc70927a71b068.png)  |
|--------------------------------------------------|
|                                                  |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/a32f10eae810d19658fca07077b5b8ad.png)

**6.Test Results：**

Download code to micro:bit, keep USB cable connected, dial POWER switch to ON
end. The distance value will be displayed on monitor.

([How to quick download?](##_7.3.快速下载))

![](media/2cd74c16ab3623f6752d3f5e59deea2e.png)

The monitor shows the distance between the obstacle and ultrasonic sensor(as
shown below). When the distance is less than 10cm, the passive buzzer of smart
car emits sound.

![](media/422adea3e04563f038f7f28cd40efb2d.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of Micro:bit is 115200 through
the test). Click “OK” and “Connect”.

CoolTerm serial monitor displays the distance value as follows:

![](media/c88ce484a935653373de5cdf72c727ed.png)

#### 18.2: Ultrasonic Avoidance Car

![](media/d5679e190f6e37eb349fea6244ba7647.jpeg)

**1. Description：**

We’ve learned the knowledge of obstacle avoidance sensor. In this project, we
will integrate ultrasonic sensor, and car expansion board to make an ultrasonic
avoidance car.

Its principle is to detect the distance between the car and obstacle by
ultrasonic sensor and control the motion of smart car.

**2. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

5.  Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
    Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3.Flow Chart**

![](media/e978e48abc4c3e712e6a22b0a79bb3dd.png)

**4.Test Code：**

| Type     | Route                                                                                             | File Name                             |
|----------|---------------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.12: Ultrasonic Follow Smart Car/8.12.2：Ultrasonic Avoidance Car | microbit-Ultrasonic Avoidance Car.hex |

Or you could edit code step by step in the editing area.

1.  Enter“Basic” →“show icon ♥”

Place it into“on start”and click the triangle button to
select“![](media/b9b97ec13c745120243516b57a2f2fbc.png)” pattern.

![](media/4e8ed8afa7457e273982b6f884567de7.png)

![](media/def79dade5bfec78105bae425e7dc98f.png)

1.  Click“TurtleBit”to move“LED brightness 0”into“on start”block

Change 0 into 200

![](media/308b9f04f29da45ec8e74b4ee03e6cfe.png)

1.  Tap“Variables”→“Make a Variable...”

Put“distance”in the search bar

Click“OK”to set up variable“distance”

Place it under“LED brightness 2000”block

![](media/b45bf0e3b9f2f27746d8aa30403ff0ab.png)

1.  Go to“Logic”to move“if true then...else”under “set...ultrasonic”block

Drag“=”block into true box

Click“Variables”to move variable“distance”into left box of“=”block

Change“=”into“＞”, 0 into 15.

![](media/34986351ab119f015480a07c600319f8.png)

1.  Tap“TurtleBit”to move“car Run_forward speed: 0%”block under “if...then”
    block

Change 0 into 80

Drag“set left_side RGBled red”and place it under“car...80%” block

Copy it once and change red into green

Set code string as follows

![](media/bfb27d411cefe10817b199f7e9766c52.png)

1.  Click“TurtleBit”to drag“LeftSide motor run forward speed: 0%”block into else
    block

Chang“forward”into back,0 into 60

Copy“LeftSide motor run back speed: 60%”again

Set the code string as follows:

![](media/dffe79d4d14756a90e2190d7ccbbfd79.png)

(7) Duplicate ![](media/cb2420d1bbf1d072d199b58aa6634aea.png)once and leave it
under else block

Click green to select blue

![](media/52badd3755b14fd68790b1dd8a354e32.png)

Complete Code

![](media/1b69303877b6288828674d51a630deae.png)

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/131915defb2da6ac5eca5476cc025df2.png)

1.  **Test Results：**

Download code to micro:bit, dial to ON end, and dial POWER to ON end. When the
obstacle distance is greater than 15cm, turtle car goes forward and 2 RGB lights
show green color; on the contrary, smart car turns left and 2 RGB lights show
blue color.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

#### 18.3: Ultrasonic Follow Smart Car

![](media/53f9661749bafa8a24dbb577f3955dc3.jpeg)

**1. Description：**

In previous lesson, we’ve learned the basic principle of line tracking sensor.
Next, we will combine ultrasonic sensor with car shield to make an ultrasonic
follow car.

The ultrasonic sensor detects the obstacle distance and control the motion
status of car.

**2. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

5.  Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
    Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3. Flow Chart**

![](media/98769134e6653214adb4c7402386ba26.png)

**4. Test Code：**

| Type     | Route                                                                                               | File Name                                |
|----------|-----------------------------------------------------------------------------------------------------|------------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.18 Ultrasonic Follow Smart Car/8.18.3：Ultrasonic Follow Smart Car | microbit-Ultrasonic Follow Smart Car.hex |

Or you could edit code step by step in the editing area.

1.  Enter“Basic” →“show icon ♥”

Place it into“on start”and click the triangle button to
select“![](media/b9b97ec13c745120243516b57a2f2fbc.png)” pattern.

![](media/4e8ed8afa7457e273982b6f884567de7.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  a. Enter “Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB
    (GRB format)”

b. Place it into“on start”block，

c. 4 pcs WS2812 RGB lights are controlled by P8 of micro:bit board . So we set
to P8 and 4 leads

![](media/6771e7c2ead111df79a0b54f56a59369.png)

(3)Tap“Neopixel”→“more”→“strip set brightness 255”

Leave it under the block “set....(RGB format)

To reduce the brightness of WS2812 RGB lights, change 255 into 100.

![](media/d5e353f086a582ae5a9c6c8da931de50.png)

(4) Click“Neopixel”to find“strip clear”

Keep it into“on start”block.

![](media/9aaa9262d9352f71ee72816331769bec.png)

(5) Go to“Variables”→“Make a Variable...”→“New variable name：” dialog box，

Input distance and click“OK”to produce variable“distance”，

Drag out“set distance to 0”into“on start”

![](media/dd47474b05855ae3789a45d28cefbec6.png)

(6) Click“Variables”to move“set distance to 0”into forever block

Click“TurtleBit”to drag block“Ultrasonic”into 0 box.

![](media/b45bf0e3b9f2f27746d8aa30403ff0ab.png)

(7) Enter“Logic”to move out“if true then”into“forever”,

Then place“and”block into true box.

![](media/adda3c734eea6a4c601d4e04fcab9b97.png)

(8) Click“Logic”to move out“=”into left box of“and”block

Move out variable“distance”into left box of“=”block

Change“=”into“≥”and 0 into 10.

Replicate“distance≥10”once and leave it into right box of“and”block.

Then we set distance ≤30

![](media/2c92a98125904b86eea6d695cdaf5b9a.png)

1.  Click“TurtleBit”→“car Run_Forward speed: 0 %”

Leave it under“if...30 then”block. Then change 0 into 80.

Go to“Neopixel” →“strip show color red”

Place it under“car Run_Forward speed: 80 %”block.

![](media/405da862183ab9a58f755b4f8258a92f.png)

1.  Duplicate code string ![](media/338e7a80c93845b661f4ecc48c843ab8.png)once
    and keep it into“forever”，

Delete block“distance≥10”and“and”block，

Change 30 into 6, Run_Forward into Run_Back , 80 into 60 and red into yellow.

![](media/6e42a4ac138012d13f28b8b70998a10c.png)

1.  Copy code string ![](media/e8fc03059674bf36f3805875aea8f82b.png)once and
    place it into“forever”，

Delete block“distance≤6”and“car RunBack speed: 60 %”

Go to“Logic”to drag out block“or”into true box，

Move block“and”into left box of“or”block，

Replicate block“distance≤6”once and place it into left box of“and”block，

Change“≤”into“\>”，and duplicate block “distance≥10”once and move into right box
of“and”，

Change“≥”into“\<”，and copy block“distance≤30”once and drag into right box
of“or”，

Change“≤”into“\>”，and move block“car stop”from“TurtleBit”

Keep“car stop”block under“if...then”block

Alter yellow into white.

![](media/94b67edf14eddee30996b1be3028d77b.png)

Complete Code:

![](media/b9b97ec13c745120243516b57a2f2fbc.png)”图案。

....................③将strip设为引脚P5初始化灯带4颗LED（模式RGB（GRB顺序））

....................④设置4个WS2812 RGB亮度（PWM）为100

....................⑤Turn off all RGB on strip

....................⑥将变量distance设为0

....................⑦The program under the block“forever”runs cyclically.

....................⑧将变量distance设为超声波传感器读取的距离值。

....................⑨当10cm≤distance≤30cm成立时，执行then下的程序

....................⑩小车以80%速度前进

....................⑪strip上4个WS2812 RGB都亮红色灯

....................⑫当distance≤6cm成立时，执行then下的程序

....................⑬小车以60%速度后退

....................⑭strip上4个WS2812RGB都亮黄色灯

....................⑮当6cm\<distance\<10cm或distance\>30cm成立时，执行then下的程序

....................⑯小车停止

....................⑰strip上4个WS2812RGB都亮白色灯

....................①“on start”: command block runs once to start program.

....................②Micro:bit
shows“![](media/b9b97ec13c745120243516b57a2f2fbc.png)”图案。

....................③将strip设为引脚P5初始化灯带4颗LED（模式RGB（GRB顺序））

....................④设置4个WS2812 RGB亮度（PWM）为100

....................⑤Turn off all RGB on strip

....................⑥将变量distance设为0

....................⑦The program under the block“forever”runs cyclically.

....................⑧将变量distance设为超声波传感器读取的距离值。

....................⑨当10cm≤distance≤30cm成立时，执行then下的程序

....................⑩小车以80%速度前进

....................⑪strip上4个WS2812 RGB都亮红色灯

....................⑫当distance≤6cm成立时，执行then下的程序

....................⑬小车以60%速度后退

....................⑭strip上4个WS2812RGB都亮黄色灯

....................⑮当6cm\<distance\<10cm或distance\>30cm成立时，执行then下的程序

....................⑯小车停止

....................⑰strip上4个WS2812RGB都亮白色灯

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/a7ba8b274b7d5d1001efe024d47eda8a.png)

**5. Test Results：**

Download code to micro:bit, dial POWER switch to ON end on shield, smart can
could follow the obstacle to move and WS2812 RGB lights show different color

Note: the obstacle only moves in front of smart car, not turning

### 19: IR Remote Control Smart Car

#### 19.1: Decode IR Remote Control

![](media/5ea6aa02b44ccc40934a02e4856fb0f9.jpeg)

**1. Description：**

There is no doubt that infrared remote control is ubiquitous in daily life. It
is used to control various household appliances, such as TVs, stereos, video
recorders and satellite signal receivers. Infrared remote control is composed of
infrared transmitting and infrared receiving systems, that is, an infrared
remote control and infrared receiving module and a single-chip microcomputer
capable of decoding.​

![](media/9980b41f57feddc2e8a9c0346afaaea9.png)

The 38K infrared carrier signal emitted by remote controller is encoded by the
encoding chip in the remote controller. It is composed of a section of pilot
code, user code, user inverse code, data code, and data inverse code. The time
interval of the pulse is used to distinguish whether it is a 0 or 1 signal and
the encoding is made up of these 0, 1 signals.

The user code of the same remote control is unchanged. The data code can
distinguish the key.

When the remote control button is pressed, the remote control sends out an
infrared carrier signal. When the IR receiver receives the signal, the program
will decode the carrier signal and determines which key is pressed. The MCU
decodes the received 01 signal, thereby judging what key is pressed by the
remote control.  
Infrared receiver we use is an infrared receiver module. Mainly composed of an
infrared receiver head, it is a device that integrates reception, amplification,
and demodulation. Its internal IC has completed demodulation, and can achieve
from infrared reception to output and be compatible with TTL signals.
Additionally, it is suitable for infrared remote control and infrared data
transmission. The infrared receiving module made by the receiver has only three
pins, signal line, VCC and GND.

**2. Specifications：**

-   Operating Voltage: 3.3-5V（DC）

-   Interface: 3PIN

-   Output Signal: Digital signal

-   Receiving Angle: 90 degrees

-   Frequency: 38khz

-   Receiving Distance: about 5m

**3. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

5.  Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
    Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**4. Test Code：**

| Type     | Route                                                                                             | File Name                             |
|----------|---------------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.19：IR Remote Control Smart Car/8.19.1：Decode IR Remote Control | microbit-Decode IR Remote Control.hex |

1.  Click“Advanced”→“Serial”→“serial redirect to USB”

Place it into“on start”block.

![](media/73b63660eb8f378dea4930f354d04de6.png)

1.  Enter“IrRemote”→“connect IR receiver at P0”

Put it into“on start”block

IR receiving module is controlled by P11 of micro:bit board, so click P0 to
select P11.

![](media/4273f360eb608f653cc59c750887725b.png)

1.  Go to“Variables”→“Make a Variable...”→ “New variable name：” dialog box，

Enter“val”and click“OK”to create variable“val”

Then drag out“set val to 0”block into“forever”block.

![](media/ca51f70bf8729f83310f70471bf1b64a.png)

1.  Go to“Ir Remote”→“IR button”

Place it into 0 box

![](media/85bff59d45d6defe248bd5c82c4b7078.png)

1.  Click“Advanced”→“Serial”→“serial write value“x”=0”

Put it into“forever”block

Change“x”into“IR”

Enter“Variables”to move block“val”into 0 box behind“=”

![](media/736e85fd87be88896e185cc61373f69e.png)

1.  Drag out block“pause (ms) 100”from“Basic”and delay in 1000ms

Leave it into“forever”block![](media/407dccc26a2a9e0e07d0436591cd99bd.png)

Complete Program：

| ![](media/d74beb9b81db714e3ac5757959bb2f0d.png) |
|-------------------------------------------------|
|                                                 |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/caff2ea648f697b9a91cfc3b7df78a96.png)

Code explanation: when the buttons are not pressed, the serial monitor
constantly shows 0; when pressed, the corresponding key values are displayed.

**Notes：**

The remote control in this kit is not inclusive of batteries. We recommend you
to purchase them online.(battery type:CR2025).

Make sure IR remote is good before test. There is a tip for you to check it.

Open the cellphone camera , make IR remote control point at camera and press
button. The remote control is good if you see the purple flashing light in the
camera.

Download code to micro: bit board and don’t plug off USB cable
Click![](media/1f02508d0c79cd976c673a6a5daba648.png)

([How to quick download?](##_7.3.快速下载))

![](media/e7bf712e0c8bedc4b0423427848fa395.png)

Make IR remote control point at IR receiver and press the button, the serial
monitor will display the corresponding key values, as shown below：

![](media/c7a33a4cc9d6decbf9b653d91bcb5318.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate. Click“OK”and“Connect”.

CoolTerm serial monitor shows the key value as follows:

![](media/a2c59f8119f9b1659c2bb40833836430.jpeg)

The key value is displayed as for your reference:

![](media/a52aed8032b82cd11c95f34eea8a2a29.jpeg)

#### 19.2: IR Remote Control

![](media/3474b90a0fcfeb9a338642b0b74a6c4c.jpeg)

**1.Description：**

In this project, we combine IR remote control with car shield to make an IR
remote smart car. Its principle is to control the motion of car by sending key
signals from IR remote control to IR receiving module of car shield.

**2.Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

5.  Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
    Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

**3.Flow Chart**

![](media/9f003294a623573222be28912d3bcdc3.png)

**4.Test Code:**

| Type     | Route                                                                                      | File Name                       |
|----------|--------------------------------------------------------------------------------------------|---------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.19：IR Remote Control Smart Car/8.19.2：IR Remote Control | microbit-IR Remote Control .hex |

Or you could edit code step by step in the editing area.

1.  Enter“IrRemote”to get block“connect IR receiver at P0”

Put it into“on start”block

IR receiving module is controlled by P11 of micro:bit board, so click P0 to
select P11.

![](media/473fb0173e3d81229d3abb867b58dcf1.png)

1.  a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB
    (GRB format)”

b. Place it into“on start”block，

c. Signal end of WS2812 RGB is connected to P8 of micro:bit board . So we set to
P8.

d. The robot has 4 pcs WS2812 RGB lights, therefore, change 24 into 4.

![](media/afef37709aaf695d3617f87bc92fd1ff.png)

1.  Go to“Variables”→“Make a Variable...”→“New variable name：”dialog box.

Enter“val”and click“OK”to produce variable“val”

Move“set val to 0”under“set strip...RGB(RGB format)” block

Then create variable“val2”in same way

Drag“set val2 to 0”into“on start”

Edit the code as follows:

![](media/bb9a60d846f91b0ec964a04d471325fc.png)

1.  Copy“set val2 to 0”once and move it into“forever”block.

Click the triangle button to select“val”

Go to“IrRemote”to drag block“IR button”into 0 box.

![](media/cb2d715c478a5e5a45c5bd290d934bb0.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Enter“Logic”→“if true then”and place it into“forever”

Drag block“=”block into“true”box

Go to“Variables”and move“val”block into left box of“=”.

Then click“=”to set“≠”

![](media/bd0c5a825a3ec489771cd94f66bf4eeb.png)

1.  Duplicate“set val2 to 0”block again and leave it under the block
    “if...val...then”block.

Then drag out variable“val”into 0 box.

![](media/c7113c934b0ab15ada6402db27fd2a12.png)

1.  Go to“Logic”to drag block“if. true..then...else”under block“set val2 to
    val”block.

Then tap“![](media/a7c5c78217692a965e679b2439ab2f3a.png)”four times and
delete“![](media/0fcc5d6332012fed7361a075bd60751f.png)”behind“else”

Move“=”block into“true”box.

![](media/472e74c957d8646cf1d8d0f691f00f24.png)

1.  Go to“Variables”to move block“val2”into left box of“=”

Change 0 into 70.

![](media/b56abcb30b725bdd5d9d638d6af51dad.png)

1.  Enter“TurtleBit”→“car Run_Forward speed: 0%”

Leave it under the second block“if...val2..then”block and change 0 into 90.

Go to“Neopixel”to move block“strip show color red”under block“car Run_Forward
speed: 90%”

Change red into green.

![](media/c1b373da440a670bd9f59d65fc41e249.png)

1.  Replicate code“val2=70”once and leave it into box behind“else if...then”.

Change 70 into 68

![](media/554e9375f1451defc9725a6cba7e998d.png)

1.  Click“TurtleBit” to drag“LeftSide motor run Forward speed: 0%” block under
    the first“else if ....then”block. And alter 0 into 60

Duplicate“LeftSide motor run Forward speed: 60%”once and alter LeftSide into
RightSide and 60 into 85.

Drag“strip show color red”block under the block“RightSide motor run Forward
speed: 85%”

Change red into blue.

![](media/d6b1c24d47331832ab0fd0efc47a618e.png)

1.  Replicate“val2=68”block and code string
    ![](media/bf33c631d141bf6d5fcd6e1645ff8bba.png)

Then edit the code string as follows:

![](media/c55acc2ae013f805eb4ce43b1dae7327.png)

1.  Copy“val2=67”again and keep it into the third box behind“else
    if....then”block

Change 67 into 21.

Replicate code string ![](media/1c2956540199f841c9aae2bde87b70ce.png)and place
it under the third“else if....then” block.

Change Run_Forward into RunBack and green into purple

![](media/83bc2500a2c3db4099456026e0bb49de.png)

1.  Then replicate“val2=21”once and“strip show color purple”block again

Change 21 into 64 and purple into red

Click“TurtleBit”to move out block“car stop”

Edit the code string as follows:

![](media/d7ad8f86c80ff0db11de26c02c2f6529.png)

Complete Code

| ![](media/975702c0be15ca4209a6e78b9b511bc9.png)  |
|--------------------------------------------------------------------------------------------------|
|                                                                                                  |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/e3cc53e658eb161bac767c6133ffe57a.png)

**5.Test Results：**

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Download code to micro:bit board, and dial POWER to ON end.

Make IR remote control point at micro:bit and press the button to control smart
car to move.

![](media/d55474f3fdf94e5d35de424c0135f554.png)button makes smart car move
forward，![](media/5c8a65498c17f35878adf79ba446a7c8.png)stands for turning
left，![](media/41116032870ebaa49d6e78fe2445da36.png)implies rightward turning,
![](media/369433f6b13252c1df8c30b3f71028d2.png)indicates moving
backward，![](media/a8ef4b174911d528e2dc232c2f862b7d.png) stops car，and 4pcs
WS2812RGB light up the corresponding color.

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

Note: the distance between IR remote control and IR receiving head of smart car
are supposed less than 5m, during the test.

### 20: Bluetooth Multi-purpose Smart Car

#### 20.1: Read Bluetooth Data

![](media/55b2424d88ba1ba8a711c49418ca8dc6.png)

**1. Description：**

In this lesson, we will control smart car to perform different functions by
Bluetooth of micro:bit board. We provide you with an App.

Let’s know its interface and function of every icon first

**2. Experimental Preparation：**

(1) Insert micro:bit board into slot of V2 shield.

(2) Place batteries into battery holder.

(3) Dial power switch to ON end

(4) Connect micro:bit to computer by USB cable and open online Makecode editor.

(5) Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

As the Bluetooth and extension radio can’t work together, therefore, their
extension libraries are not compatible.

Therefore, remove extension(s) and add Bluetooth please if you see the following
prompt box pop up.

![](media/aee56e76bad3421a20cea6018ccd5e2c.png)

**3. Test Code：**

| Type     | Route                                                                                              | File Name                        |
|----------|----------------------------------------------------------------------------------------------------|----------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.20：Bluetooth Multi-purpose Smart Car/8.20.1：Read Bluetooth Data | microbit-Read Bluetooth Data.hex |

Or you could edit code step by step in the editing area.

1.  Enter“Advanced” →“Serial” → “serial redirect to USB”

Place it into“on start”

![](media/73b63660eb8f378dea4930f354d04de6.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Bluetooth”→“on bluetooth connected”

Go to“Basic”to move“show icon”block into“on bluetooth connected” block.

![](media/501b8068bafd00adcf138a2b828835d9.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Click“Variables”→“Make a Variable...”→“New variable name：”dialog box.

Input“connected”and click“OK”to create variable“connected”.

Drag“set connected to 0”under block “show icon” and change 0 into 1.

![](media/bc9514b04f4aae40dc295eeac3fb21ce.png)

1.  Go to“Loops”to move block“while true do...”into“on bluetooth
    connected”block.

Enter“Logic”to drag out “=”block.

Click“Variables” to drag “connected” into left box of “=” block and change 0
into 1.

![](media/665a62b4895ca45f82d3ebc88e885bce.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1.  Then we generate variable“rec_data”in same way.

Then drag out“set rec_data to 0”and place it into block“while connected=1
do...”block.

Click“Bluetooth”→“more”→“bluetooth uart read until new line( )”

Keep it into 0 box and click triangle button to select \##.

![](media/e993122756294214c561f660c3df07ea.png)

1.  Go to“Advanced”→“Serial”→“serial write string”

Move it below“set rec_data...until\##”block

And combine variable“rec_data”with“serial write string”block.

![](media/6effc725f7d85e4a72afbcee102cc478.png)

1.  Click“Advanced” →“Serial” →“serial write line” and edit code string as
    follows:

![](media/5d66f2053f858d7a3f2e0af55bcc0f0f.png)

1.  Click“Bluetooth”to drag out“on bluetooth disconnected”.

1.  Go to“Bluetooth”→“on bluetooth disconnected”

Copy“show icon”block and keep it into block“on bluetooth disconnected”

Click triangle button to
select“![](media/25e0341e063286ff7828c15f09ae0ade.png)”pattern.

![](media/689000dc16e8fb32f0d9918445aae4c1.png)

Complete Program

| ![](media/25e0341e063286ff7828c15f09ae0ade.png)”pattern.  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/1d6bb93636c2954f3c4bfc413ba53a49.png)

1.  **Test Results：**

If you drag blocks step by step, you need to set as follows after finishing test
code.

Click
![](media/09767d5efdc8f05fdb331b5ae6d352b5.png)

However, you could skip this step if you directly import test code.

After setting, download code to micro:bit board, don’t plug off USB cable([How
to download?](##A01) [How to quick download?](##_7.3.快速下载))

Next to download App.

For IOS system

a. Open App Store

![](media/27924fdb3d67692df7c63d8d0fb72287.png)

b. Search keyes Bit Car and
click“![](media/962a57f92b78eea1f0e3e81463497a9c.png)”icon to download keyes Bit
Car

![](media/bb0985bc4d079475e1175b4b16d10b0e.png)

c. After the download, tap“OK”when a dialog box appears up.

![](media/6c97d9ffcde0d66cb36a017a413ce0a3.png)

![](media/a5c05f7b5844e11a8ea7a4b96df244de.png)

d. Enable Bluetooth of cellphone or iPad.

Click“connect”button to search Bluetooth.

Then select“BCC micro:bit”to connect Bluetooth.

For Android system

Scan the QR code and enter website to download keyes_Bit_Car.apk

![](media/8fb53bd64d7d181ae9d24113419ac600.png)
![](media/e476860c0f534b0d9675649f02ec4d3b.png)
![](media/7566b3df9a230bc3f69993ad2d41fb85.png)

Then click“Always allow”and tap“install”

![](media/638d0a4ae5f55ca39bff4f20a3bd14a6.png)
![](media/1b0ad4f8146ca600fd2670f1266b44ef.png)

e. Tap“Open”or click“keyes Bit Car”icon to enter app.

A dialog box appears, then click“Allow”to turn on Bluetooth.

You also enable Bluetooth firstly.

![](media/c818fd71d6872374fbe177f082207fac.png)
![](media/3dab73f0e830bb5c0348af86110f3e50.png)

Click“CONNECT”to search and link with Bluetooth.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate. Click“OK”and“Connect”.

Point at micro:bit board and press the icons on APP, the corresponding
characters are shown on CoolTerm monitor.

![](media/3692e0ea2df357e30b51c6c83b0412f0.png)

![](media/6c1919fed6577bcf80a3564ee01e0207.png)

Through the test, we get the function of every icon, as shown below:

![](media/8773155fbc44d64b3228035100854f1f.png)

![](media/4f704871fba18f330fe51eb6c9f4bf39.png)

![](media/b6aa28e94c427ff69976422722234c54.png)

![](media/5b942e52b28749e7d4ac904627442500.png)

#### 20.2: Multi-purpose Smart Car

![](media/eaa852aacab745232fd78350910cd74c.jpeg)

**1. Description：**

In this lesson, we will control the smart car to perform multipurpose function.

**2. Experimental Preparation：**

1.  Insert micro:bit board into slot of V2 shield.

2.  Place batteries into battery holder.

3.  Dial power switch to ON end

4.  Connect micro:bit to computer by USB cable and open online Makecode editor.

5.  Import Hex profile [**(How to import?)** ](##_7.6.导入代码), or click“New
    Project”and drag blocks step by step(add turtle-bit extension library first)

[**(How to add turtle-bit extension?)**](##M11)

As the Bluetooth and extension radio can’t work together, therefore, their
extension libraries are not compatible.

Therefore, remove extension(s) and add Bluetooth please if you see the following
prompt box pop up.

![](media/aee56e76bad3421a20cea6018ccd5e2c.png)

**3. Test Code：**

| Type     | Route                                                                                                   | File Name                             |
|----------|---------------------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file | ../Makecode Tutorial/Test Code/8.20：Bluetooth Multi-purpose Smart Car /8.20.2：Multi-purpose Smart Car |  microbit-Multi-purpose Smart Car.hex |

Complete Code

![](media/388ca47a4f3a313e2c27a2d3d252d278.png)

![](media/e3ead7c6a6a7875bc4032183df8387c9.png)

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/397921e0f7bd80b6e108a0fecf44b8d9.png)

![](media/bf0168256421037f9053d7f0626d9b91.png)

![](media/dd0a762b831c30e22cde6ca041fb80df.png)

![](media/34c3742affae13a2ca8ad42da2a36077.png)

![](media/4500fe10720eaac6f590228e14617fea.png)

![](media/2e12fca4da3e85a69b096b1a7ba7d8a5.png)

![](media/7b5325d4be31fbbd64b935fbb2a78d92.png)

**4. Test Results：**

We will control micro:bit smart car to move via app.

Enter Makecode online editor→Projecting
Settings→![](media/bef5b73422672f316f211a959bcdfa60.png), enable “No
Pairing....”(you could skip this step if you import test code directly)

Download code and turn on the switch at the back of micro:bit car. Then control
smart car via “keyes Bit Car”app

([How to download?](##A01) [How to quick download?](##_7.3.快速下载))

