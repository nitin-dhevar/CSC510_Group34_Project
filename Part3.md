__Difficulties faced in the process of selecting and running projects and brainstorming on how that pain could have been avoided.__

Selecting and running the prior projects worked on by our seniors, after a significant time gap was in fact challenging and interesting. There were several difficulties faced by our team during the project selection and execution process and we will try to incorporate a few practices in our project2 to avoid the pain. 

For most of the projects, even after executing all the steps as documented we still got the issues due to version mismatches, incompatibility, deprecated software functions etc. Some of the major challenges we have faced during the execution of the projects in the order of complexity are: 

1)	__Dependency Issues__: The software code written by our seniors was developed around a year prior. So in this time gap, software dependencies and environment configuration has changed drastically. There were newer versions of some libraries which were not compatible with older versions of other libraries that we are trying to install. We have faced these issues while executing 3 projects out of the 5 projects assigned to us. These outdated dependencies resulted in errors during the installation process.

2)	__Deprecated Technologies__: It was quite challenging for us to find the compatible versions or replacements for the deprecated technologies. Replacing the deprecated libraries required us to understand where and how it was used, learn how to use the newer version of the library and implement them. This was a time consuming and tedious process.

3)	__Compatibility with different Operating Systems__: There was one less commonly faced issue which we have encountered running one of our projects. The documentation was clear and detailed but the steps for executing the project were only relevant to the Linux/Unix based Operating System. The commands such as chmod and shell script files were specific to the Linux/ Unix OS and no documentation for executing the project in the Windows based environment was available. So it required us to learn the alternative commands for the Windows environment and modify the shell scripts so that it runs on the Windows platform.

4)	__Obsolete and Incomplete Documentation__: In some cases we found that the project documentation has become outdated or incomplete 
E.g. 1 Obsolete Documentation - incorrect or outdated git clone command - Result: we cloned wrong repository or outdated repository
E.g. 2 Incomplete Documentation - Some of the python projects required C++ build tools support to run but it was not mentioned in the documentation
 
The steps required to execute the project were not detailed and it just provided a high-level overview of the process in some cases. This made it difficult to understand the setup process and run the project effectively. The lack of up-to-date and complete documentation was one of the significant problems faced by our team. 

The availability of a clear, detailed, complete and interactive documentation would have alleviated most of the problems encountered by us while running the project.

And finally some of the errors and issues, which we had no idea of :), 
Example Context: We have used the clone path exactly as specified in documentation and got this issue but  later managed to resolve them by trying other methods of downloading.
 

__Some general practices we are looking to incorporate in Project2:__

These are some general practices which we will be incorporating for our upcoming projects in order to improve our code quality as well as to tackle the aforementioned issues. 
1)	Much detailed and elaborate documentation by including common misconceptions and screenshots of some issues faced by us in order to address the newbie developers.
2)	Maintain a clear, detailed and consistent README.md document i.e. Documentation.
3)	Including the environment files such as requirements.txt, environment.yml along with the information about important practices to follow during the installation process clearly in the documentation.
4)	Including Well Defined and Detailed comments throughout the project’s source code to help others understand the purpose of the functions and methods used in the project.
5)	One Image can describe a thousand words - So we will try to make the documentation more interactive with the usage of images/ screenshots. Usage of Hyperlinks to refer to external links wherever required.
6)	Using libraries which have a strong community support.


