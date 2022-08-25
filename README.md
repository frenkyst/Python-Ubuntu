# Python-Ubuntu

### Python
__Python3​__

Python adalah Python merupakan bahasa pemrograman tingkat tinggi yang diracik oleh Guido van Rossum. Python banyak digunakan untuk membuat berbagai macam program, seperti: program CLI, Program GUI (desktop), Aplikasi Mobile, Web, IoT, Game, Program untuk Hacking.

1. Pertama-tama kita harus install terlebih dahulu Pyhton3. Untuk instalasi ikuti beberapa perintah di bawah ini.

        sudo apt update; sudo apt upgrade

![image](https://user-images.githubusercontent.com/40049149/186701181-18eeca23-aac8-4d5f-9dd0-808b891d92a2.png)

2. Python3 sudah ada secara default, untuk melakukan pengecekan jalankan perintah berikut.

        python3 -V
        
![image](https://user-images.githubusercontent.com/40049149/186702427-e514ad1e-a339-47f6-a13f-10a3efee8397.png)

3. Sekarang kita install package manager dari python3. Kalian dapat menggunakan perintah berikut ini.

        sudo apt install python3-pip

![image](https://user-images.githubusercontent.com/40049149/186701300-67fcff14-1d6b-4e28-b1f0-bc4ac7de87e2.png)

        pip install flask

![image](https://user-images.githubusercontent.com/40049149/186702546-957d6194-736e-45db-9a06-8fd5010b308c.png)

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



