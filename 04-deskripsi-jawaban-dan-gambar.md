Perbedaan Docker dan VMWare terdapat pada arsitektur virual dari kedua VM tersebut,
**Docker** : melakukan isolasi di level OS, sehingga kita tidak perlu menginstall keseluruhan OS jika hanya ingin menggunakan satu service di OS tertentu dan resource yang digunakan docker lebih ringan dibandingkan dengan VMware.
**VMware** : melakukan isolasi di level hardware abstraction layer, sehingga jika kita menggunakan vmware harus menginstall keseluruhan sistem operasi.

Kita gunakan Docker ketika kita ingin menggunakan beberapa service dari distro linux yang berbeda. 
Kita gunakan VMware ketika hanya menggunakan 1 sistem operasi saja.

