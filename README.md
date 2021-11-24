IN = open(sys.argv[1], 'r')

ID_Seq={}           # initializing the ID_seq dictionary

for Line in IN:
    ID = Line.strip('\n')
    Seq = IN.readline()
    Seq = Seq.strip('\n')
	ID_Seq[ID]=Seq      # building the ID_seq dictionary
#WORK ON DICTIONARY OUTSIDE OF LIST

for thing in sorted(ID_Seq.keys()):
    print(thing)
    print(ID_Seq[thing])


Harley Quinn is cool tooo


i like coffee
