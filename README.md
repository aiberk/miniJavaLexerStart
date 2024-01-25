# miniJavaLexer

## Progress

added javacc.jar to the directory
added cal.jj to the directory
compiled the cal.jj file using the following command

```bash
java -classpath javacc.jar javacc cal.jj
```

compile cal with

```bash
javac cal.java
```

## Running project

```bash
java cal test.txt
```

Should out put:

`LPAREN: (
NUMBER: 9
ADD_OP: +
NUMBER: 2
RPAREN: )
MULT_OP: \*
NUMBER: 38
LPAREN: (
NUMBER: 90
ADD_OP: +
NUMBER: 4
RPAREN: )`

## Development

edit cal.jj by adding more tokens and rules
