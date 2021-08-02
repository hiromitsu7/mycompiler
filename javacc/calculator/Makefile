CLASSES = *.class
JAVAS = *.java
JJS = Calculator.jj

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): $(JJS)
	javacc Calculator.jj

clean:
	rm -f *.java *.class
