# WebService

<!DOCTYPE pesan [
<!ELEMENT pesan (to,from,heading,body)>
<!ELEMENT to (#PCDATA)>
<!ELEMENT from (#PCDATA)>
<!ELEMENT heading (#PCDATA)>
<!ELEMENT body (#PCDATA)>

Definisi:

!DOCTYPE pesan   => mendefinisikan bahwa elemen root(induk elemen) dari dokumen ini adalah pesan
!ELEMENT pesan   => mendefinisikan bahwa elemen pesan harus mengandung empat elemen: "to,from,heading,body"
!ELEMENT to      => mendefinisikan elemen to menjadi tipe "#PCDATA"
!ELEMENT from    => mendefinisikan elemen from menjadi tipe "#PCDATA"
!ELEMENT heading => mendefinisikan elemen heading menjadi tipe "#PCDATA"
!ELEMENT body    => mendefinisikan elemen body menjadi tipe "#PCDATA"

Diatas adalah contoh DTD
DTD adalah Document Type Definition.
DTD mendefinisikan struktur elemen dan atribut dari dokumen XML.
DTD digunakan untuk memverifikasi bahwa data XML valid.

dibawah ini adalah empat elemen yang sudah didefinisikan tipenya dari script dtd diatas : 

<pesan>
<to>Fulan</to>
<from>Agung</from>
<heading>Reminder</heading>
<body>jangan lupa berolahraga hari ini</body>
</pesan>

