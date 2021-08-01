CLASSES = Calcurator.class CalcuratorTokenManager.class SimpleCharStream.class TokenMgrError.class CalcuratorConstants.class ParseException.class Token.class
JAVAS = Calcurator.java CalcuratorTokenManager.java SimpleCharStream.java TokenMgrError.java CalcuratorConstants.java ParseException.java Token.java

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): Calculator.jj
	javacc Calculator.jj

clean:
	rm -f *.java *.class
