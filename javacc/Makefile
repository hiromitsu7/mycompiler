CLASSES = Adder.class AdderTokenManager.class SimpleCharStream.class TokenMgrError.class AdderConstants.class ParseException.class Token.class
JAVAS = Adder.java AdderTokenManager.java SimpleCharStream.java TokenMgrError.java AdderConstants.java ParseException.java Token.java

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): Adder.jj
	javacc Adder.jj

clean:
	rm -f *.java *.class
