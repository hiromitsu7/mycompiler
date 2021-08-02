CLASSES = *.class
JAVAS = *.java
JJS = Calculator.jj CalculatorParser.jj Example1.jj
JJTS = CalculatorParser.jjt Example1.jjt

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): $(JJS)
	javacc Calculator.jj
	javacc CalculatorParser.jj
	javacc Example1.jj

$(JJS): $(JJTS)
	jjtree CalculatorParser.jjt
	jjtree Example1.jjt

clean:
	rm -f *.java *.class
	rm -f CalculatorParser.jj
	rm -f Example1.jj
