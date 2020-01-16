# nodejs-jwtauth
This apps node js login with jwt auth.

# login [konstanta data]
- buka http://localhost:4000/users/authenticate [POST]
- jika user tidak cocok: 'Username or password is incorrect'
- jika user cocok: mendapatkan token
- jika user berhasil user akan mendapatkan token utk melanjutkan proses point 2
# sapa kasir pintar
- buka http://localhost:4000/users [GET]
return 'kasir pintar'
