CLASSES = *.class
JAVAS = *.java
JJS = CalculatorParser.jj
JJTS = CalculatorParser.jjt

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): $(JJS)
	javacc CalculatorParser.jj

$(JJS): $(JJTS)
	jjtree CalculatorParser.jjt

clean:
	rm -f *.java *.class
	rm -f CalculatorParser.jj
