# UTS-bpd-aulia
Membuat Load Balancing dengan Podman + Nginx + Flask

1. Persiapan Tools <br>
   instal: <br>
   Podman <br>
   Python <br>
   Nginx image dari Docker Hub <br>
   cek podman <br>
   <img width="464" height="78" alt="image" src="https://github.com/user-attachments/assets/d24784fd-7daf-4d4b-97e6-db4bbb61fa90" /> <br>
<br>
2. Membuat Aplikasi Flask <br>
   struktur folder<br>
   <img width="219" height="176" alt="image" src="https://github.com/user-attachments/assets/f9424bc3-8d91-44c2-a50d-f29996399ba6" /> <br>

3. Membuat File Aplikasi<br>
   app.py<br>
   <img width="549" height="366" alt="image" src="https://github.com/user-attachments/assets/eb8969f4-e3ef-40cd-a40e-6615f33daffc" /> <br>

   requirements.txt <br>
   <img width="658" height="97" alt="image" src="https://github.com/user-attachments/assets/2fbe0cde-ec38-4c84-ac4e-607221172b83" /> <br>

4. Membuat Dockerfile <br>
   <img width="826" height="382" alt="image" src="https://github.com/user-attachments/assets/9d9a8d6a-ee63-46f8-ad4a-93dc00d12a2f" /> <br>
<br>
5. Build Image dengan Podman <br>
   Masuk ke folder project:
   <img width="626" height="53" alt="image" src="https://github.com/user-attachments/assets/dfdd3cea-81ca-465c-8abd-8f8046e8f003" /><br>
<br>
   Build image:
   <img width="917" height="1002" alt="image" src="https://github.com/user-attachments/assets/1c5cd13c-0bb8-406d-bd05-0e124c58c7fb" /> <br>

6. Menjalankan Beberapa Container<br>
    Container 1 <br>
    <img width="930" height="78" alt="image" src="https://github.com/user-attachments/assets/bcca43ea-1d1b-470f-89a1-48d7faa70abb" /><br>

    Container 2 <br>
    <img width="922" height="76" alt="image" src="https://github.com/user-attachments/assets/697c0d3f-dc3f-441b-a412-e73f657928b1" /> <br>

    Container 3 <br>
    <img width="925" height="69" alt="image" src="https://github.com/user-attachments/assets/53c5201f-abc8-401e-be05-11862983bc78" /> <br>

7. Membuat Pod <br>
Agar container bisa saling berkomunikasi:
<img width="935" height="98" alt="image" src="https://github.com/user-attachments/assets/4b634264-9bb8-4392-b221-a678a77107d5" />
<br>
   Masukkan container ke pod
    <img width="939" height="240" alt="image" src="https://github.com/user-attachments/assets/f7620a8e-3ad1-41d9-9b92-7b5d6080d2fb" /> <br>

8. Membuat Konfigurasi Nginx <br>
    <img width="616" height="501" alt="image" src="https://github.com/user-attachments/assets/6d461de7-7aa0-428f-8387-ff3155113c36" /> <br>

9. Menjalankan Nginx Container <br>
   <img width="943" height="124" alt="image" src="https://github.com/user-attachments/assets/722805e1-820d-4dac-bd2a-b803343fd2a4" /> <br>

10. Pengujian <br>
   http://localhost:8081
    <img width="959" height="159" alt="image" src="https://github.com/user-attachments/assets/ae778ddc-fd6e-4e53-89f0-645813809acc" /> <br>

