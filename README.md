# Home
import 'package:flutter/material.dart';

void main() {
  runApp(TapGameApp());
}

class TapGameApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Juego Tap Rápido',
      debugShowCheckedModeBanner: false,
      home: TapGameScreen(),
    );
  }
}

class TapGameScreen extends StatefulWidget {
  @override
  _TapGameScreenState createState() => _TapGameScreenState();
}

class _TapGameScreenState extends State<TapGameScreen> {
  int score = 0;
  int timeLeft = 10;
  bool is
