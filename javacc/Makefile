CLASSES = Calculator.class CalculatorTokenManager.class SimpleCharStream.class TokenMgrError.classCalculatorConstants.class ParseException.class Token.class
JAVAS = Calculator.java CalculatorTokenManager.java SimpleCharStream.java TokenMgrError.java CalculatorConstants.java ParseException.java Token.java

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): Calculator.jj
	javacc Calculator.jj

clean:
	rm -f *.java *.class
