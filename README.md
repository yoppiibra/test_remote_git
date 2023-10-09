# test_remote_git

Langkah membuat git remote dari git local sampai upload di github
 ###### jika ada already origin main maka di remove dulu $git remote remove origin
1. git init
2. git remote
3. copas git remote origin
4. cek git remote -v
5. tambahkan file git add .
6. git commit -m 'pesan untuk git commit'
7. copas git branch -M main
8. git push -u origin main

# git fetch 
mengambil revisi tanpa menggabungkan atau merge terhadap repository local
1. buat revisi di github
2. git fetch main origin main
3. cek perubahan di origin maim $git log main origin/main
4. cek perbedaan di origin main $git diff main origin/main
5. gadungkan menggunakan merge $git merge main origin/main

# git pull
menggambil revisi langsung menggabungkan dengan git local 
### example jika ada yang menambahkan file baru maka
1. git pull origin main


# clone git atau copy git
1. mau di letakan di directory mana
   - cd ~/Documents
2. git clone <url git yang mau di clone atau copy> + .git
   -   git clone https://github.com/yoppiibra/test_remote_git.git
