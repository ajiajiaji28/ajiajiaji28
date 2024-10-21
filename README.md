def bahan_bahan():
    bahan = [
        "1 kg daging sapi",
        "2 liter air",
        "2 batang serai",
        "3 lembar daun jeruk",
        "4 siung bawang putih",
        "5 siung bawang merah",
        "1 ruas jahe",
        "1 ruas kunyit",
        "Garam secukupnya",
        "Merica secukupnya",
        "Bawang goreng untuk taburan",
        "Daun bawang untuk taburan",
        "Nasi putih"
    ]
    return bahan

def langkah_langkah():
    langkah = [
        "1. Rebus daging sapi dalam 2 liter air hingga empuk.",
        "2. Haluskan bawang putih, bawang merah, jahe, dan kunyit.",
        "3. Tumis bumbu halus hingga harum.",
        "4. Masukkan bumbu tumis ke dalam panci rebusan daging.",
        "5. Tambahkan serai dan daun jeruk, masak hingga semua bumbu meresap.",
        "6. Tambahkan garam dan merica sesuai selera.",
        "7. Sajikan soto dengan nasi putih, taburi bawang goreng dan daun bawang."
    ]
    return langkah

def buat_soto():
    print("Bahan-bahan untuk membuat soto:")
    for b in bahan_bahan():
        print(f"- {b}")

    print("\nLangkah-langkah membuat soto:")
    for l in langkah_langkah():
        print(l)

# Menjalankan program
if __name__ == "__main__":
    buat_soto()
