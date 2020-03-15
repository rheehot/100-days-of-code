# 100 Days Of Code Flutter - Log

### Day 6: Minggu 16 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: 
- masih Belajar tentang adaptive dan responsive layout, 
- belajar tentang adaptive untuk Ios dan Android seperti widget Switch.adaptive, CupertinoPageScaffold , CupertinoIcons

**Thoughts:**  belum melihat hasil nya karena belum punya Mac :) , 

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. Kursus Udemy  [learn-flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content) Materi ke 129

### Day 5: Sabtu 15 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: 
- masih Belajar tentang adaptive dan responsive layout, 
- mengecek orientation menggunakan Mediaquery of context orientation, 
- untuk mengetahui ukuran padding bawah menggunakan MediaQuery.of(context).viewInsets.bottom
- pengganti itenari ( kondisi ? ... : ...) bisa menggunakan if (kondisi) tanpa tanda kurung
- contoh = 
```dart

    final isLandskape =
        MediaQuery.of(context).orientation == Orientation.landscape;
        
        .....
            if (!isLandskape)
              Container(
                  height: (MediaQuery.of(context).size.height -
                          appBar.preferredSize.height -
                          MediaQuery.of(context).padding.top) *
                      0.3,
                  child: Chart(_recentTransaction)),
            if (!isLandskape) txListWidget,
            ....
```



**Thoughts:**  ternyata banyak cara untuk membuat responsive dan adaptive, if else juga bermacam2 bentuknya

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. Kursus Udemy  [learn-flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content) Materi ke 125

### Day 4: Jumat 14 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: masih Belajar tentang adaptive dan responsive layout, menggunakan layout builder, didalam nya bisa menggunakan contrains ( mempunyai property maxheigh n min height)

**Thoughts:**  ini bisa jadi pilihan yang lain , selain mediaquery of context

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. Kursus Udemy  [learn-flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content) Materi ke 122


### Day 3: kamis 13 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: Belajar tentang adaptive dan responsive layout, use mediaquery of context, appBar bisa dibuat sebagai variabel (objek) yang didalamnya ada prefred size, termasuk tinggi dariappBar itu sendiri, padding, statusbar,

**Thoughts:**  Mantap ini bisa responsive tergantung dari device mau handphone, tablet, maupun buat web nantinya

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. Kursus Udemy  [learn-flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content) Materi ke 119



### Day 2: Rabu 12 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: Belajar tentang Widget DateTimePicker dan function dari List ( removeWhere ) yang digunakan untuk menghapus dan membutuhkan sebuah 'id', DatePicker banyak format yang bisa dipake, dan untuk menampilkan harus memakai format

**Thoughts:**  Hari ini ngebut beberapa video , tapi tampaknya ga bagus belajar dengan terburu-buru,malah pusing,  slow aja yang penting masuk, dan berprogress tiap hari nya,

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. [Kursus Udemy](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content)


### Day 1: Selasa 11 Maret, 2020

**Goal**: Complete  [flutter-dart-to-build-ios-android-apps](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps) from Udemy


**Today's Progress**: Belajar tentang Flexible dan fittedbox

**Thoughts:** widget fittedBox ini keren, bisa mengecilkan content dengan parentnya, 

**Links to work:** 
1. [Expenses App](https://github.com/triyono777/expenses_app.git)
2. [Kursus Udemy](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/learn/lecture/14951102#content)

