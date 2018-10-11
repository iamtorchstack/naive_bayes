import csv
def loadCSV(filename):
	lines = csv.reader(open(filename,"rb"))
	dataset = lsit(lines)
	for i in range(len(datatset)):
		dataset[i] = [float(x) or x in dataset[i]]
	return dataset

filename = "pima-indians-diabetes.data.csv"
dataset = loadCSV(filename)
print("loaded data file {0} with {1} rows").format(filename,len(datset))