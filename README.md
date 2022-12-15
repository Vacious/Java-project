# Java-project
<p>
  <img src="https://user-images.githubusercontent.com/93658180/207932851-b389cd96-dfca-45b6-8b61-0aac94e948ca.jpg" width="200" height="300">
  <img src="https://user-images.githubusercontent.com/93658180/207932864-4250a81e-3a3f-4b00-9072-9449b3ed6ff1.jpg" width="200" height="300">
  <img src="https://user-images.githubusercontent.com/93658180/207932882-a20e3165-4cc0-4e28-bd5e-b3aabf24b7b3.jpg" width="200" height="300">
 <img src="https://user-images.githubusercontent.com/93658180/207932889-699bb365-bcff-4c8f-9c59-4f5fea71e419.jpg" width="200" height="300">
</p>
<br>
1. Locate your file directory in Command Prompt/Terminal
ie. cd C:\Users\user\java-project

2. Run 2 lines below seperately in Command Prompt/Terminal according to your platform.

<b>For Windows:</b>
javac -d src -cp .\jars\jfreechart-1.5.3.jar;.\jars\jdatepicker-1.3.4.jar templates/*.java *.java
java -cp .\src;.\jars\jfreechart-1.5.3.jar;.\jars\jdatepicker-1.3.4.jar Project

<b>For Mac:</b>
javac -d src -cp ./jars/jfreechart-1.5.3.jar:./jars/jdatepicker-1.3.4.jar templates/*.java *.java
java -cp ./src:./jars/jfreechart-1.5.3.jar:./jars/jdatepicker-1.3.4.jar Project



