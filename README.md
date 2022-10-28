# Menghitung luas keliling lingkaran menggunakan python
1. Pertama-tama, Buat File bernama luasKelilingLingkaran.py


2. Berikut Flowchart untuk menghitung luas dan keliling lingkaran
    
    ![Flowchart](https://user-images.githubusercontent.com/115931631/198547346-88bff752-e9bd-4165-9f73-2ad7257d8e83.png)
 
3. Lalu Masukan CODE berikut :
        
        # import module math
        import math

        # Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
        jariJari = input('Masukan jari-jari lingkaran :')

        """

        rumus luas & keliling lingkaran
        _____________________________________

        luas     = phi * r^2

        keliling = 2 * phi * r

        _____________________________________

        """

        # convert string to integer
        jariJari = int(jariJari)

        # hitung luas lingkaran
        luas = math.pi * (jariJari * jariJari)

        # hitung luas keliling
        keliling = 2 * math.pi * jariJari

        # output luas & keliling lingkaran
        # .2f => mengambil 2 angka setelah (,)
        print("Berikut Luas lingkaran =  ", format(luas, '.2f'))
        print("Berikut Keliling lingkaran = ", format(keliling, '.2f'))
        
4. Ketika dijalankan Inputkan Jari jari dan Berikut Hasil nya
![Hasil](https://user-images.githubusercontent.com/115931631/198548718-35461573-665a-4116-aefa-ca1e3d8d028e.png)

5. Selesai Begitulah cara menghitung luas dan keliling Lingkaran
# TERIMA KASIH
