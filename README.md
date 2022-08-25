# Python-Ubuntu

### Python
__Python3​__

Python adalah Python merupakan bahasa pemrograman tingkat tinggi yang diracik oleh Guido van Rossum. Python banyak digunakan untuk membuat berbagai macam program, seperti: program CLI, Program GUI (desktop), Aplikasi Mobile, Web, IoT, Game, Program untuk Hacking.

1. Pertama-tama kita harus install terlebih dahulu Pyhton3. Untuk instalasi ikuti beberapa perintah di bawah ini.

        sudo apt update; sudo apt upgrade

2. Python3 sudah ada secara default, untuk melakukan pengecekan jalankan perintah berikut.

        python3 -v
        
image1

3. Sekarang kita install package manager dari python3. Kalian dapat menggunakan perintah berikut ini.

        sudo apt install python3-pip

image1

        pip install flask

image1

__PIP__ adalah sebuah package management system yang biasa digunakan untuk mengatur dan menginstall __package yang berisi modul-modul Python__. PIP digunakan untuk menginstall __Flask__ karena Flask ditulis dan dikembangkan dengan bahasa dan modul-modul pemrograman __Python__. Dengan menggunakan PIP, semua hal yang dibutuhkan untuk instalasi Flask akan diunduh dan dipasang dalam satu perintah.

4. Sekarang kita akan membuat aplikasi sederhana menggunakan __Python3__.

5. Kalian buat terlebih dahulu file dengan nama index.py. Lalu masukan script dibawah ini.

        nano index.py

__index.py__

        from flask import Flask
        app = Flask(__name__)
        @app.route("/")
        def helloworld():
          return "Hello World"
        if __name__ == "__main__":
          app.run()

6. Jika sudah sekarang jalankan aplikasi dengan menggunakan perintah berikut ini.

        python3 index.py

image1

image1

7. Sekarang coba akses web browser kalian setelah itu kalian coba akses dengan localhost:5000



