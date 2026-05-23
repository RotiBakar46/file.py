#!c\python\python

# Name file: open.py

def main():
    print ("\033[1;34m")
    f = open( "data.txt", "w+")
    print ("===========================================================")
    print ("\033[1;35m[1].\033[1;37mbelajar.py+kmr308\t:", f.name )
    print ("\033[1;35m[2].\033[1;37mtertutup?\t        :", f.closed )
    print ("\033[1;35m[3].\033[1;37mmode akses\t        :", f.mode )    
    print ("\033[1;32m=================================================")
    
if  __name__ == "__main__":
