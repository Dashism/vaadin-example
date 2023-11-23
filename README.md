# vaadin-example

This project uses Vaadin, a web app development framework for Java that includes a large library of UI components. It helps you build reliable web apps and a great UX faster than before.

If you want to learn more about Vaadin, please visit its website: https://vaadin.com/ .

## Use the chat application

Open two terminals, one basic, the other in private mode.

Connect in the first terminal with :
- login : batman / password : password

Connect in the second terminal with :
- login : robin / password : password

## Creating a native executable

You can create a native executable using:
```shell script
./mvnw -Pnative -Pproduction -DskipTests native:compile
```