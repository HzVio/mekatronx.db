![Image](https://img.shields.io/npm/v/mekatronx.db?color=6F94DB)
![Image](https://img.shields.io/npm/dt/chaindev.db.svg?color=6F94DB&maxAge=3600) 
#
# Yüklemek İçin
```npm
npm i mekatronx.db
```

# Örnek Kullanım
```javascript
const { Database } = require('mekatronx.db');
const db = Database();

db.set('Veri', 'Değer');
db.push('Veri', 'Değer');
db.add('Veri', 5);
db.substr('Veri', 5);
db.fetch('Veri');
db.get('Veri');
db.has('Veri');
db.fetchAll();
db.all();
db.math('Veri', '*', 5');
db.delete('Veri');
db.deleteAll();
db.destroy();
```

# İletişim Bilgilerim
[Discord](https://discord.com/users/698149042387157032) 

