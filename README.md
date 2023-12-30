# fileLoop

def main():
    fileName = input("What is the name of the file? ")
    total = 0
    count = 0
    infile = open(fileName, "r")
    for line in infile:
        total += float(line)
        count += 1
    print("Average of the numbers is", total / count)

main()
