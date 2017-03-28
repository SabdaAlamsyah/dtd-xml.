# dtd-xml.


Perbedaan XML dan HTML
   XML dirancang untuk mendeskripsikan data dan untuk fokus pada apa data. HTML dirancang untuk  menampilkan data dan untuk fokus pada bagaimana data terlihat.

  HTML adalah tentang menampilkan informasi, sedangkan XML adalah tentang mendeskripsikan informasi.
 
Perbedaan paling signifikan antara HTML dan XML adalah bahwa HTML memiliki unsur-unsur yang telah ditetapkan dan atribut yang perilakunya baik ditentukan, sementara XML tidak. Sebaliknya, penulis dokumen dapat membuat kata-kata sendiri XML yang khusus untuk aplikasi mereka atau kebutuhan bisnis. Kosa kata XML untuk saat ini ada sejumlah besar industri dan aplikasi dari pengajuan keuangan. 

Perbedaan lain antara HTML dan XML adalah bahwa XML memperkenalkan konsep ness biasa. Aturan ness teratur XML menghapus beberapa ambiguitas yang melekat dalam pengolahan bahasa markup seperti HTML dengan menegakkan aturan seperti mewajibkan bahwa semua nilai atribut harus dalam tanda kutip.
contoh DTD tentang daftar film :


< ! ELEMENT daftarfilm (datafilm+) >
<!ELEMENT datafilm (judul, pemain, sutradara, jenisfilm+, produser*) >
<!ELEMENT judul (#PCDATA) >
<!ELEMENT pemain (#PCDATA) >
<!ELEMENT sutradara (#PCDATA) >
<!ELEMENT jenisfilm (#PCDATA) >
<!ELEMENT produser (#PCDATA) >
<ATTLIST judul durasi CDATA # IMPLIED>
<!ENTITY tahun “2011”>
