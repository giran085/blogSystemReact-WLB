Guide cara setup project :
    1.Clone di github https://github.com/giran085/blogSystemReact-WLB.git
    2.Setelah itu masuk ke folder (my-app), "cd my-app" lalu lakukan "npm install"
    3.Masuk ke folder (graphql), "cd graphql" lakukan "npm install"
    4.Siapkan database, diberikan nama misal react_blog. saya buat menggunakan MySQL Workbench.
    5.Masuk ke file (.env)
    6.Isi data sesuai Mysql di localhost
    7.Data (.env) di Laptop saya seperti point nomor 8
    8.  MYSQL_HOST=localhost
        MYSQL_USER=root
        MYSQL_PASS=
        MYSQL_DB=react_blog
    5.Setalah itu jalankan "npm run run-migration" di folder (graphql).
    6.Cek di database apakah data telah masuk
    7.Setelah itu di folder (graphql) jalankan "node app"
    8.Setelah Server Ready
    9.Masuk ke cd my-app dan jalankan npm start
    10.Maka Server akan start dan project bisa dilihat