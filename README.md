# Use-Me
A cleaner and smarter waste management system using IoT sensors using AI &amp; ML.



## How to configure web app
**1.** Clone git repo

```shell
$ git clone "https://github.com/madhav2180/Use-Me.git"
```

**2.** Create virtual env

```shell
$ pip install virtualenv
```
```shell
$  python -m venv env
```
```shell
$  ./env/Scripts/activate
```
**3.** Import Modules

```shell
$ pip install keras
```
```shell
$ pip install pillow
```
```shell
$ pip install numpy
```
```shell
$ pip install tensorflow
```
```shell
$ pip install opencv-python     
```
**4.** Execute prediction model
```shell
$ python ./main.py      
```
**5.** Run stremlit app
```shell
$ streamlit run .\imgpredict.py    
```
## How to configure mobile app
**1.** Before running your project,make sure to run the following commands:


1.flutter pub get
2.flutter packages pub run build_runner build --delete-conflicting-outputs

This creates the generated code necessary for the project to run.

