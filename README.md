# JAVA VIRTUAL PET🐼

Dalam game ini, pemain akan memerankan sebagai seekor panda jantan yang ingin memiliki teman hidup, seorang panda betina yang bernama Lancy. Namun, untuk memenangkan hati Lancy, pemain harus melalui serangkaian tantangan yang menguji kesabaran, kecerdasan, dan kepekaan terhadap kebutuhan Lancy. Final state berada di saat menyatakan perasaan yang dimana pemain dituntut bisa mengerti suasana hati Lancy yang jika mood atau keadaan Lancy sedang baik maka ketika pemain menyatakan perasaan dia akan menerimanya, sebaliknya jika mood atau keadaan Lancy sedang tidak baik dia akan menolak.

![image alt](https://github.com/AhmdMaulidan/virtual-pet-java/blob/65ce98d5c0bb4a104e8f70f9d4da8cc822eb89df/image_pet.png)

# 📘 Diagram Transisi

Diagram ini menjelaskan transisi dari berbagai kondisi berdasarkan aksi yang dilakukan, seperti mengajak main, makan, istirahat, atau menyatakan perasaan.

## 🧠 Tabel Transisi

| **Transisi** | **Ajak Main** | **Ajak Makan** | **Ajak Istirahat** | **Nyatakan Perasaan** |
|--------------|---------------|----------------|---------------------|------------------------|
| **Lapar**    | Sakit         | Bosan          | Sakit               | Ditolak                |
| **Bosan**    | Happy         | Bosan          | Bosan               | Ditolak                |
| **Sakit**    | Sakit         | Sakit          | Happy               | Ditolak                |
| **Happy**    | Happy         | Happy          | Happy               | Diterima               |
| **Ditolak**  | Ditolak       | Ditolak        | Ditolak             | Ditolak                |
| **Diterima** | Diterima      | Diterima       | Diterima            | Diterima               |

## 📊Diagram Formal 

1.	Ajak Main
2.	Ajak Makan
3.	Ajak Istirahat
4.	Nyatakan Perasaan

![image alt](https://github.com/AhmdMaulidan/virtual-pet-java/blob/0393f0b78dde27551bc07ef622e7dbb4119de156/state.png)

## 💡 Penjelasan

- **Transisi**: Kondisi awal sebelum aksi dilakukan.
- **Aksi**: Tindakan yang dilakukan terhadap kondisi tersebut.
- **Hasil**: Kondisi hasil setelah aksi dilakukan.

Diagram ini berguna untuk memodelkan perubahan kondisi emosional atau status seseorang berdasarkan interaksi sosial yang diterima.

---

program ini di buat untuk memenuhi tugas mata kuliah teori komputasi

> Created with ❤️ for demonstrasi logika transisi kondisi.
