## Modul 5
### JMeter GUI Results
- `/all-student` View Results in Table:
  ![All Student Request View Results in Table](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-view-results-in-table.png)
- `/all-student` Summary Report:
  ![All Student Request Summary Report](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-summary-report.png)
- `/all-student-name` View Results in Table:
  ![All Student Name Request View Results in Table](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-name-view-results-in-table.png)
- `/all-student-name` Summary Report:
  ![All Student Name Request Summary Report](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-name-summary-report.png)
- `/highest-gpa` View Results in Table:
  ![All Student Request View Results in Table](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/highest-gpa-view-results-in-table.png)
- `/highest-gpa` Summary Report:
  ![All Student Request Summary Report](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/highest-gpa-summary-report.png)

### JMeter Command Line Results
- `/all-student` JTL Log File:
  ![All Student JTL File](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-log-file.png)
- `/all-student-name` JTL Log File:
  ![All Student Name JTL File](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/all-student-name-log-file.png)
- `/highest-gpa` JTL Log File:
  ![Highest GPA JTL File](https://github.com/DawnFall19/exercise-profiling/blob/main/Module%205%20Images/highest-gpa-log-file.png)

### Conclusion about JMeter Measurements
Ketika membandingkan hasil pengukuran JMeter sebelum dan sesudah terjadinya proses REFACTOR, dapat disimpulkan bahwa terdapat perubahan yang sangat signifikan karena proses REFACTOR yang berhasil meningkatkan efisiensi dan menurunkan kompleksitas dari fungsi-fungsi yang ada.

### Refleksi
1. JMeter mensimulasikan beban dunia nyata dengan menghasilkan permintaan secara bersamaan untuk mengevaluasi kinerja sistem secara keseluruhan, sedangkan IntelliJ Profiler fokus pada mekanisme internal aplikasi dengan melakukan analisa tentang eksekusi kode, penggunaan memori, dan konsumsi CPU.
2. Dengan adanya proses profiling, saya dapat menganalisa setiap fungsi dan operasi untuk mengetahui bagian yang perlu dipercepat dan dicari alternatifnya agar program dapat berjalan dengan efisien.
3. Ya, karena dengan adanya IntelliJ Profiler, saya dapat melihat bagian kode yang kurang efisien dan dapat segera memperbaikinya.
4. Tantangan tersulitnya adalah kurangnya konsistensi antar setiap tes. Ketika melakukan tes pada kode yang sama sebanyak beberapa kali, setiap tesnya pasti memiliki hasil yang berbeda-beda. Hal ini menyebabkan kebingungan jika REFACTOR yang dilakukan tidak mengurangi kompleksitas kode secara signifikan. Cara saya mengatasinya adalah memastikan REFACTOR yang saya lakukan cukup signifikan dalam mengurangi kompleksitas kode, dan jika tidak signifikan, saya akan mencari referensi yang dapat membuktikan bahwa REFACTOR yang saya lakukan lebih efisien.
5. Mendapat banyak data dan analisa terkait masing-masing bagian dari kode melalui angka, persentase, grafik, dan lain-lain.
6. Melakukan tes tidak hanya sekali, namun beberapa kali, dan membandingkan setiap hasil tes dan mengambil kesimpulan mayoritas.
7. Strateginya adalah melihat setiap fungsi tentang apakah ada perulangan yang tidak diperlukan, apakah fungsi itu sudah terbawa melalui _library_ atau pernah diimplementasikan sehingga dapat langsung digunakan, apakah ada data yang tidak diperlukan, dan apakah terdapat algoritma atau observasi yang dapat saya ambil untuk mendapatkan solusi dengan lebih efisien.