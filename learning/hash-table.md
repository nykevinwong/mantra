HashTable
- hash函式決定將某筆資料要存在表上或陣列上對應的位置
- 可用陣列或鍊表實作
- 同一hash函式可能對不同筆資料產生同一對應位置，這情況叫碰撞沖突(hash collisiion

陣列 HashTable 解決碰撞沖突的方法.

Open Addressing 開方式定址 (
- Liner Probing  -> index + 1, index+2,..index+n
- Quadartic Probling -> index+)^2 + index+2^2 +...index+n^n
- Double Hashing  

Seperate Chainnin
用鍊表實作 HashTable 來解決碰撞沖突.
