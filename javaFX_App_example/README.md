## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## REF:
### 在VSCode內設定JavaFX:
+ https://home.gamer.com.tw/creationDetail.php?sn=4766681
+ https://www.youtube.com/watch?v=I4J5_IWDeEo

+ 編譯或執行
```
first cd into src/ folder

To Compile:
javac --module-path "c:/Program Files/JavaFX/javafx-sdk-17.0.1/lib/" --add-modules javafx.controls App.java

To Run:
java --module-path "c:/Program Files/JavaFX/javafx-sdk-17.0.1/lib/" --add-modules javafx.controls App
```

### 其他關於JavaFX的參考:
+ https://openjfx.io/
+ https://github.com/openjfx/samples/blob/master/HelloFX/CLI/hellofx/HelloFX.java

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
