# Saengphet Portfolio — ຄູ່ມືຕິດຕັ້ງ

## 1. ອັບໂຫຼດເວັບໄຊຕ໌
1. ເປີດ repository `saengphet-portfolio-assets` ໃນ GitHub.
2. ກົດ **Add file → Upload files**.
3. ອັບໂຫຼດໄຟລ໌ ແລະ folders ທັງໝົດຈາກ ZIP (ຮັກສາ `assets` ແລະ `data`).
4. ກົດ **Commit changes**.
5. ເຂົ້າ **Settings → Pages**; ເລືອກ **Deploy from a branch**, branch `main`, folder `/ (root)`, ແລ້ວ Save.
6. URL ເວັບຄາດໝາຍ: `https://saeng3011-lgtm.github.io/saengphet-portfolio-assets/`.

## 2. ເພີ່ມຮູບ
ອັບໂຫຼດຮູບເຂົ້າ repository ໃນ folder ເຊັ່ນ `uploads`. ເປີດໄຟລ໌ຮູບໃນ GitHub, ເປີດ Raw ແລະຄັດລອກ URL ໄປໃສ່ຊ່ອງ Image URL ໃນ Admin.

## 3. ເພີ່ມວິດີໂອ
ອັບໂຫຼດໃນ YouTube Studio, ເລືອກ Public ຫຼື Unlisted, ແລ້ວຄັດລອກ URL ມາວາງໃນ Video URL. ວິດີໂອຈະສະແດງໃນ Portfolio ຜ່ານ YouTube embed.

## 4. ເພີ່ມ/ລຶບຜົນງານ
ເປີດ `admin.html` ຜ່ານເວັບໄຊຕ໌. ກອກຟອມ, ກົດເພີ່ມ, ແລ້ວດາວໂຫຼດ `portfolio.json`. ໃນ GitHub ເປີດ `data/portfolio.json`, ກົດ Edit, ແທນຂໍ້ມູນເກົ່າ ແລະ Commit changes.

## ຂໍ້ຈຳກັດສຳຄັນ
- ນີ້ແມ່ນ workflow ຟຣີ: Admin ສ້າງ JSON ໃຫ້ ແຕ່ບໍ່ commit ເຂົ້າ GitHub ອັດຕະໂນມັດ.
- ໜ້າ Admin ບໍ່ມີ login. ຢ່າໃສ່ GitHub password ຫຼື Personal Access Token ໃນເວັບ.
- GitHub ບໍ່ເໝາະສຳລັບໄຟລ໌ວິດີໂອຂະໜາດໃຫຍ່. ໃຊ້ YouTube ສຳລັບວິດີໂອ.
- ຢ່າເປີດ HTML ດ້ວຍ file:// ເພາະ browser ອາດບລັອກການອ່ານ JSON; ໃຊ້ GitHub Pages ຫຼື VS Code Live Server.
- Custom domain ຕ້ອງມີ domain ທີ່ທ່ານເປັນເຈົ້າຂອງ.
