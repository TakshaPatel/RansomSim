# RansomSim
A simple sandboxed ransomware program made to teach students the dangers of ransomware.  
The use of this program is strictly for educational purposes.      
A hands-on approach to learning how ransomware works    

### Installation
Prerequisites: JRE & JDK must be installed for the program to run  
```
git clone https://github.com/TakshaPatel/RansomSim/
cd RansomSim
chmod +x run.sh
./run.sh
```
Note: If you are on Windows, chmod is not installed; directly run after cd'ing into RansomSim:
```
clear
javac -d ./build ./src/*.java
java -cp ./build Main
```
