# first_flutter_app_2

A new Flutter project.

# Praktikum 1: Get the starting app

1. Pada praktikum kali ini menambahkan package english_words dengan syntax seperti berikut:

```flutter pub add english_words```

![Screenshoot flutter_fundamental_3](images/p21_6.png)

2. Hasil dari running dengan package english_words

![Screenshoot flutter_fundamental_3](images/p21_1.png)

# Praktikum 2: Add icons to the list

1. Menambahkan _saved untuk menampung kata-kata yang terdapat dalam package english_words pada class _RandomWordsState

```final _saved = <WordPair>{};```

![Screenshoot flutter_fundamental_3](images/p21_7.png)

2. Menambahkan alreadySaved untuk menampung kata-kata yang tidak ditampung pada favorite words

```final alreadySaved = _saved.contains(_suggestions[index]); // NEW```

![Screenshoot flutter_fundamental_3](images/p21_8.png)

3. Menambahkan widget ListTile dan didalam widget ListTile ditambahkan widget Icons untuk menampilkan icon favorite

![Screenshoot flutter_fundamental_3](images/p21_2.png)

# Praktikum 3: Add interactivity

1. Menambahkan properties onTap yang nantinya akan menambahkan interaksi pengguna dengan hanya 'ketuk satu kali'

![Screenshoot flutter_fundamental_3](images/p21_9.png)

- Pada praktikum ini menambahkan condition if else. Ketika pengguna melakukan interaksi dengan mengetuk tombol icon maka icon akan berubah menjadi merah. Jika tidak maka icon akan mengubah menjadi bentuk default icon.

![Screenshoot flutter_fundamental_3](images/p21_3.png)

# Praktikum 4: Navigate to a new screen