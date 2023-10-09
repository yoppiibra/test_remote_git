# test_remote_git

Langkah membuat git remote dari git local samai upload di github
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
