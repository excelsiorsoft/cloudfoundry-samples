# Basic CF App

Some local configurations:

**~/.profile file**:

~~~bash
export PS1="$"
alias idea="open -a /Applications/IntelliJ\ IDEA\ CE.app"
alias ll='ls -lG'
~~~



Need to uncomment JPA-related things in pom.xml to prevent errors:
![](./imgs/img-1.png)

Build it: 
	`$./mvnw clean package`


Now we can run: `ctrl+shift+r` -->  run in IntelliJ

![](./imgs/img-0.png)