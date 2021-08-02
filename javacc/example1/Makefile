CLASSES = *.class
JAVAS = *.java
JJS = Example1.jj
JJTS = Example1.jjt

$(CLASSES): $(JAVAS)
	javac *.java

$(JAVAS): $(JJS)
	javacc Example1.jj

$(JJS): $(JJTS)
	jjtree Example1.jjt

clean:
	rm -f *.java *.class
	rm -f Example1.jj
