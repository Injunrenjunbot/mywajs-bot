[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

# MYWAJS BASE (ESM)

> **NB:** Versi cjs nanti di up di branch cjs. PROJECT INI AKTIF. AKAN TERUS DIKEMBANGKAN

> Note : fitur akan terus dikembangkan. untuk membuat cmd silahkan lihat paling bawah examplenya

# instalasi
```
git clone https://github.com/amiruldev20/wwebjs-base
cd mywajs-bot
npm i
npm start
```

# informasi
```
versi gratis beberapa fitur memakai api dari
1. xfarr.com
2. xzn.wtf
3. lolhuman
jika ingin versi scrape anda dapat membeli script premium
```

# example cmd
```
opsi yang ada ✅ berarti wajib di tambahkan. yang tidak ada centang berarti tidak masalah jika tidak ada

boolean = true atau false

export default {
    name: 'injun', //✅ nama command
    cmd: ['tunggu', 'sabar'], //✅ command (bisa satu atau dua)
    tags: 'play', //✅ tags menu
    desc: 'ini deks', // deskripsi menu
    run: async({mywa, m}) => {
        m.reply('halo') // contoh saja
    },
    isOwner: boolean, /082255178208/ opsi bagian ini dan dibawah bisa ditambahkan atau tidak
    isBotAdm: boolean, /082255178208/ bot admin
    isAdmin: boolean, /on/ admin gc
    isGroup: boolean, /on/ group only
    isPrivate: boolean, /on/ pc only
    isPremium: boolean, /off/ premium
    isVIP: boolean, /on/ vip
}
```
