# OpenCV_Project_Generator

<p align="justify"> 
<i>OpenCV_Project_Generator</i> is a template project (including a "CMakeLists" file) which will let you to automatically create a C++ project including <a href="http://opencv.org/">OpenCV</a> (they must be already installed on your machine) without having to manually set all configuration parameters.
This project is "cross platform" thanks to CMake and will prevent you to waste a lot of time whenever you want to create a new project which requires OpenCV library. 
</p>

## Requirements

<p align="justify">To correctly run the <i>OpenCV_Project_Generator</i> following libraries and utility are needed:</p>

<ul>
	<li> <a href="https://cmake.org/download/">CMake</a> 3.0.0 or higher; </li>
	<li> <a href="http://opencv.org/downloads.html">OpenCV</a> (test with Opencv 3.0 and later versions); </li>
	<li> One of your favourite IDE/compiler (tested with Visual Studio 2013/2015/2017); </li>
</ul>

## Installation ...

<ol>
	<li><p align="justify">Clone the GitHub repository (HTTPS clone URL: https://github.com/prittt/OpenCV_Project_Generator.git) or simply download the full master branch zip file and extract it ("MyProject" folder in the following of this README.md). The project contains the following folders/files: </p> </li>
	<ul>
		<li> <p align="justify"><i>bin</i>: where to put the project generated by CMake (suggested)</p> </li>
		<li> <p align="justify"><i>doc</i>: where to put project's documentation (empty)</p> </li>	
		<li> <p align="justify"><i>include</i>: where to put header (.h, .hpp, ..) files (empty)</p> </li>
		<li> <p align="justify"><i>src</i>: where to put source (.c, .cc, .cpp, ..) files. At the beginning it contains an example "main.cpp" file to test the entire project and if OpenCV are correctly included by the project</p> </li>
		<li> <p align="justify"><i>tools</i>: where to put scripts files (empty)</p> </li>
		<li> <p align="justify"><i>.gitignore and .git</i>: git file (useless for your project)</p> </li>
		<li> <p align="justify"><i>CMakeLists.txt</i>: file that CMake will use to create the project</p> </li>
	</ul>
### ... using CMake GUI:

	<li> <p align="justify">Run CMake specifying as <i>source code path</i> "MyProject" path (mandatory) and as <i>where to build binaries</i> "MyProject/bin" path (suggested). If you are using CMake GUI see image below.  Note that CMake should automatically find OpenCV path (if installed), download YACCLAB Dataset and create a project for the selected IDE/compiler.</p> </li>

<img src="https://github.com/prittt/OpenCV_Project_Generator/tree/master/data/readme_imgs/" alt="step_1" height="260" width="415">

## ... using CMake from command line:

</ol>


