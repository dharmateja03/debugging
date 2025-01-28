# debugging
Common debugging tips
## If a lib is installed but your vs code is not recognizing it check for interpreter 
import sys
print(sys.executable)
gives current interpreter 
pip3 show lib_name shows locatin where lib was isntalled
