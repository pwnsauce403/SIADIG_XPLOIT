# SIADIG_XPLOIT
CSRF Vulnerability at Sistem Informasi Arsip Digital (SIADIG)

Exploit?

*Add Petugas*
- /admin/petugas_aksi.php
- /admin/petugas_update.php
jika redir kemnungkinan vuln, tinggal login saja 
dan ganti hak akses menjadi petugas / pengurus / guru (setiap web beda beda)

*Add Arsip*
- /petugas/arsip_aksi.php


cara akses shell dari csrf add arsip
www.yourtarget.sch.id/arsip/
or
www.yourtarget.sch.id/[path]/arsip
tambahkan /arsip dibagian belakang url target

jika redir ke login page atau minta lu buat login dulu kemungkinan
web tersebut vuln.

Dork?
- "Sistem Informasi Arsip Digital" + "LOGIN USER LOGIN ADMIN / PETUGAS" site:id
- "Manajemen file arsip dengan mudah dan cepat." + "LOGIN USER LOGIN ADMIN / PETUGAS" site:id
- "Sistem Informasi Arsip Digital" + "Login Admin" site:id
- "Dashboard V.2" + "Kiaalap - Kiaalap Admin Template"
- "LOGIN USER LOGIN ADMIN / PETUGAS" site:id
- "Sistem Informasi Arsip Digital" intext:LOGIN ADMIN site:sch.id
(more? kembangin lagi sendiri, use your brain)
