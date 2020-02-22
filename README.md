# Smart-Classroom 智慧课堂
__Update：__ 
2019.5.1

__Result:__
Project detail is here:https://www.bilibili.com/video/av52331060/  
项目详细介绍看此视频：https://www.bilibili.com/video/av52331060/  
__Project:__
This project is to combine the Internet of Things, computer vision and web technology to establish a smart classroom system. As a webside member, responsible for website live broadcast function development and front-end development. The languages used are js, CSS, HTML and third-party libraries. In a week, the web-side live broadcast function development was quickly completed, tested and deployed. The team won the “First Prize of China Internet of Things Competition” and “Alibaba Cloud Innovation Award” (only one amount).

项目为结合物联网、机器视觉以及web技术构建智慧课堂系统。作为web端成员，负责web端直播功能开发和前端开发。作为视觉组成员，使用openCV完成对笔迹的识别。在一周时间内快速完成web端直博功能开发并进行测试部署，最终团队获得“中国物联网大赛一等奖”和“阿里云创新奖”（仅一名额）。

__Environment__: matlab1016b

# Introduction 简介
With the rapid development of Internet of things technology, new educational technology means are emerging, and the teaching mode is changing. It is gradually changing from the teacher's propaganda to the interaction between teaching and learning, from the teacher's propaganda to the interaction between teaching and learning. There are many problems in traditional education and teaching that are hard to solve for a long time. In order to create an intelligent, efficient and intelligent classroom teaching environment and promote the personalized growth and intelligent development of students, this project adopts the Internet of things technology to develop a set of Internet of things intelligent classroom system based on o2o mode.

This system includes interactive intelligent projection system and global cloud teaching system. Among them, the interactive intelligent projection system is mainly composed of computer, wireless electronic pen, camera, projector and projection cloth; the global cloud teaching system is mainly composed of tablet, Web terminal, database and terminal.

In the interactive intelligent projection system, teachers can write on the projection cloth by using wireless electronic pen, or operate ppt directly, or even control the computer wirelessly. In order to realize the functions of wireless electronic brush and wireless control computer, this work combines machine vision and image recognition technology, Bluetooth communication technology, Windows API technology and other technologies, and independently produces the wireless electronic pen mainly developed by Arduino nano development board and the Bluetooth module radio pen equipped with cc2540 chip, and develops the recognition algorithm of wireless electronic pen based on OpenCV.

Global cloud teaching system provides students with network cloud courses, real-time interactive communication platform and multimedia cloud notes. Among them, online cloud courses can be provided to students in the form of live broadcast or recorded broadcast; the real-time interactive communication platform is mainly to create a learning oriented chat environment for teachers and students to enhance the interaction between students and teachers and students; multimedia cloud notes is a new form of notes that integrates video, audio, text notes, and students can use the handwritten board and other ways quickly Efficiently create multimedia cloud notes, and share notes through the Internet. In order to achieve the above functions, this work makes use of real-time information communication technology and other technologies, and independently makes a handwritten board mainly composed of beaglebone black development board and lcd07 touch screen, and builds alicloud server based on Apache network environment.

This work is easy to operate, with complete functions, intelligence and low cost. No matter for teachers or students, this work can greatly make their teaching or education easier. Under the background of the Internet of things era, the innovation of teaching mode has great market application and promotion value.

Key words: intelligent classroom interactive intelligent projection system global cloud teaching system machine vision Bluetooth communication cc2540 network cloud course real-time interactive communication platform multimedia cloud notes beaglebone black

随着物联网技术的快速发展，新的教育技术手段不断涌现，教学模式也在不断发生变化，逐渐从教师的宣讲向教与学的互动方面转变，从教师的宣讲向教与学的互动方面转变。传统教育教学中长期存在和难以解决的诸多问题，为打造智能高效、富有智慧的课堂教学环境，促进学生个性化成长和智慧发展，本项目采用物联网技术，开发了一套基于O2O模式的物联网智能课堂系统。

本系统包括交互式智能投影系统和Global云教学系统两个系统。其中，交互式智能投影系统主要由电脑、无线电子笔、摄像头、投影仪、投影布组成；Global云教学系统主要由手写板、Web端、数据库、终端组成。

在交互式智能投影系统中，老师可通过利用无线电子笔，在投影布上进行板书，或者对PPT进行直接操作、甚至是对电脑进行无线操控等。为实现无线电子画笔和无线操控电脑的功能，本作品结合了机器视觉和图像识别技术、蓝牙通讯技术、Windows api技术等技术，自主制作了主要由Arduino Nano开发板和搭载CC2540芯片的蓝牙模块无线电子笔，研发了基于opencv的无线电子笔的识别算法等。

Global云教学系统为学生提供了网络云课程、实时互动交流平台和多媒体云笔记等。其中，网络云课程可通过直播或者录播的形式提供给学生使用；实时互动交流平台主要为老师和学生营造一个以学习为目的的聊天环境，以增强学生间和师生间的互动能力；多媒体云笔记是一种集视频、音频、文字备注的新格式笔记，学生可通过手写板等方式快捷高效的制作多媒体云笔记，并可通过互联网实现笔记的共享。为实现以上功能，本作品利用了实时信息通讯技术等技术，自主制作了主要是由BeagleBone Black开发板和LCD07触控屏组成的手写板，搭建了基于Apache网络环境的阿里云服务器等。

本作品操作方便，功能齐全智能且成本较低。无论是对老师还是对学生，本作品都能够极大地使他们的教学或者接受教育变得更加轻松，在物联网的时代背景下的进行了教学模式的创新，具有较大的市场应用和推广价值。

关键词：智能课堂  交互式智能投影系统  Global云教学系统  机器视觉  蓝牙通讯  CC2540  网络云课程  实时互动交流平台  多媒体云笔记  BeagleBone Black 


# Project Purpose
The basic idea of this project is to add more hardware and software elements to the traditional multimedia equipment with projector and computer as the core to build an intelligent classroom system. Hardware add devices such as camera, tablet and wireless pen. In this way, teachers can express their teaching contents in the classroom as much as possible, and students can accept the teaching contents as much as possible; in the aspect of software, the classroom is connected with the Internet, so as to add another online classroom on the basis of the original school classroom, and present the content of the school classroom offline again, so that students can really be in the classroom Review the knowledge that you missed or didn't understand in class. The purpose of this project is to build a multi resource and multi-element intelligent classroom system that integrates offline classroom teacher's teaching content and recreates online classroom content.

This project first adds a camera above the projector. When the teacher uses the wireless electronic pen for blackboard writing against the projection cloth in class, the camera can capture the teacher's writing track, and after a series of processing, the projector can project the teacher's handwriting in real time. At this point, there is no ink on the projection cloth. The wireless pen is like a real pen writing on the projection cloth and leaving traces. At the same time, the courseware with handwriting will be sent to each student's tablet to take notes.

Students can use the tablet on the desk to set the time node where they think it is important at any time, and finally generate a multi-element note with video, voice and text notes. At the same time, teachers use the tablet to ask students questions at any time. Students only need to answer on the tablet to show the answer process on the projection screen. This function can greatly facilitate teachers to acquire students' knowledge.

With the functions of video recording and live broadcasting, the teacher's classroom content can be recorded and uploaded to the corresponding web end to form a live video form for students to use. At the same time, the live video can also be saved. After class, the video playback end can be reproduced for students to watch. Chat room is designed to make students better communicate and learn after class. Teachers can also learn about students' learning and their evaluation of the classroom in the chat room.

本项目的基本思路是在以投影仪和电脑为核心的传统多媒体设备增添更加多的软硬件元素，打造一个智能课堂系统。硬件添加如摄像头、手写板和无线电子笔等设备。如此使得老师能够在课堂上尽可能地表达自己的教学内容和让学生能够最大限度地去接受老师授课的内容；软件方面则是将课堂与互联网联通，使得在原本的学校课堂的基础上增添多一个线上课堂，将学校课堂的内容再次呈现在线下，使得学生能够真正地能够在课堂下复习到自己上课遗漏或者不解的知识点。本项目旨在打造一个集线下课堂老师授课内容，线上重现上课内容的多资源多元素的智能课堂系统。

本项目首先在投影仪上方添加一个摄像头。老师在课上对着投影布使用无线电子笔进行板书时，摄像头能够捕捉获取到老师的书写轨迹，并经过一系列处理让投影仪实时地投影出老师的笔迹。此时，投影布上并没有墨水。无线电子笔就好像一支真实的笔在投影布上书写同时留下痕迹。同时，带有笔迹的课件会相应地被发送至每位学生的手写板当中供他们做笔记。

学生可使用课桌上的手写板随时将他认为重要的地方设置时间节点，最后在生成一个具备视频、语音、文字备注的多元素笔记。同时老师利用手写板随时提问学生，学生只需在手写板上作答即可将解答过程呈投影屏上，该功能能够极大地方便教师获取学生对知识的掌握情况。

利用录屏和直播的功能，能够将老师课堂的内容录下来并上传到相应的web端上形成一个直播视频形式供学生们使用，同时直播的视频会也可以保存，课下可再现视频播放端，供学生们观看。聊天室是为了能够让学生更加好地在课后交流学习而打造的，老师也能够在聊天室中了解到学生的学习情况和他们对课堂的评价情况。


# Project Result
After several months of hard work, the team has completed many of the functions originally envisaged in the project, which are described as follows:

Offline part:

(1) Completed the development and manufacture of wireless electronic pen, completed the remote wireless control function of wireless electronic pen;

(2) Completed the related development tasks of the project in cooperation with machine vision and image processing technology;

(3) Completed the configuration and development of the students' handwriting board. Students are able to make new notes smoothly on the tablet.

Online part:

(1) Completed the development of the network course platform, so that teachers and students can log in and use the platform freely;

(2) Completed the development of real-time interactive communication platform. It successfully enables teachers to use the real-time interactive communication platform to start the live broadcast. Teachers and students can use real-time interactive communication platform to communicate happily;

(3) Completed all the local functions of notes. As the biggest feature of the project, the project successfully completed all the local functions of notes. Students can use notebooks to make notes in a new format.

在经过几个月的努力，本团队完成了很多项目中原先设想的功能，下面依次简述：  
线下部分：  
（1）完成了无线电子笔的开发和制造，完成了无线电子笔远程无线操控的功能；  
（2）完成了项目中配合机器视觉和图像处理技术的相关开发任务；  
（3）完成了学生手写板的配置和研发。学生能够流畅地在手写板上制作新格笔记。  
线上部分：  
（1）完成了网络课程平台的开发，使得师生能够自由地登录进入和使用该平台；  
（2）完成了实时互动交流平台的开发。成功地使得老师能够利用实时互动交流平台开启直播。师生之间能够愉快地利用实时互动交流平台进行交流；  
（3）完成了笔记本地全部功能。作为本次项目最大地特色，本项目顺利地完成了笔记本地全部功能。学生能够利用笔记本做出新格式地笔记。  

Detail Result is in here:https://www.bilibili.com/video/av52331060/  
详细的项目结果在此：https://www.bilibili.com/video/av52331060/

# Contact
Feel to contact me. My email is richardfeynman180778@gmail.com.

