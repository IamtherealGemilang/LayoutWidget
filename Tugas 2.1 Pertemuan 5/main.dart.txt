import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Tugas 2.1 Pertemuan 5',
      home: Scaffold(
        backgroundColor: Colors.teal,
        body: Container(
            // decoration: BoxDecoration(color: Colors.red),
            // margin: EdgeInsets.only(top: 30, bottom: 30),
            child: Row(
              children: <Widget>[
                Column(
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: [
                    Container(
                      decoration: BoxDecoration(color: Colors.red),
                      height: 650,
                      width: 100,
                      margin: EdgeInsets.only(top: 50, bottom: 50),
                    )
                  ],
                ),
                Column(
                  crossAxisAlignment: CrossAxisAlignment.center,
                  mainAxisAlignment: MainAxisAlignment.center,
                  children: [
                    Container(
                      decoration: BoxDecoration(color: Colors.yellow),
                      height: 100,
                      width: 100,
                      margin: EdgeInsets.only(left:46.35, right: 46.35),
                    ),
                    Container(
                      decoration: BoxDecoration(color: Colors.green),
                      height: 100,
                      width: 100,
                      margin: EdgeInsets.only(left:46.35, right: 46.35),
                    )
                  ],
                ),
                Column(
                  children: [
                    Container(
                      decoration: BoxDecoration(color: Colors.blueAccent),
                      height: 650,
                      width: 100,
                      margin: EdgeInsets.only(top: 50, bottom: 50),
                    )
                  ],
                )
              ],
            )),
      ),
    );
  }
}