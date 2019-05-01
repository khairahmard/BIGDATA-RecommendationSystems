# Recomendation System with ALS

`engine.py` : untuk inisialisasi spark, untuk menjalankan webserver, untuk memanggil app.py dan engine.py, dan setting dataset location <br>
`app.py` : untuk menghubungkan server.py dengan engine.py dan sebagai tempat routing <br> 
`server.py` : untuk tempat inisialisasi fungsi

## REST API:
### TOP RATINGS
`[GET] /<int:user_id>/ratings/top/<int:count>`
![Gambar](../img/Screenshot_1.jpg)

### MOVIE RECOMMEND
`[GET] /movies/<int:movie_id>/recommend/<int:count>`
![Gambar](../img/Screenshot_2.jpg)

### MOVIE RATINGS
`[GET] /<int:user_id>/ratings/<int:movie_id>`
![Gambar](../img/Screenshot_3.jpg)
