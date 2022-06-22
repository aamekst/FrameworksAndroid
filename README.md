# Frameworks Android

## **Flutter**

 * O Flutter permite que você crie aplicativos para dispositivos móveis, web, desktop e dispositivos incorporados, tudo a partir de uma única base de código.
 * É uma estrutura de código aberto do Google para criar aplicativos multiplataforma bonitos e compilados nativamente a partir de uma única base de código.
 * É desenvolvido pelo Dart, uma linguagem otimizada para aplicativos rápidos em qualquer plataforma, ou seja, pode ser usado em aplicações moveis, web, IOS, android e desktop.
 * Pode ser instalado no VS CODE e Android Studio.
 * Em vez de escrever um código diferente para cada sistema operacional, ele usa a mesma base de código para criar um aplicativo móvel multiplataforma.
 * O código compila para código de máquina ARM ou Intel, como JavaScript, para obter um desempenho melhor e mais rápido.
 * Os codigos podem ser felxiveis, produtivos e rápidos.

## Exemplo de codigo

    import 'package:flutter/material.dart';
    void main() {
      runApp(MyApp());
    }
    class MyApp extends StatelessWidget { 
      @override
      Widget build(BuildContext context) {
        return MaterialApp
          home: Scaffold(
            appBar: AppBar(
              // A prop. AppBar usa um widget Text widget para a sua prop. title
              title: Text("Explorando Widgets"),
            ),
            body: myWidget(),
          ),
        );
      }
    Widget myWidget() {
      return Text(
        "Alana - Mobile",
      );
    }
