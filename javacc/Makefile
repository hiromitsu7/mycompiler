CLASSES = *.class
JAVAS = *.java

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): Calculator.jj
	javacc Calculator.jj

clean:
	rm -f *.java *.class
