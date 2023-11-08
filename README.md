# Node.js
### async fonksiyonlar promise dödürüyor bu promise denilen aslında async fonksiyonun döndürdüğü bir nesne bunu then ile işlersin ya da catch ile hata döndürüyor ise mesaj verdirirsin.
### await de aslında async fonksiyonun değerini bekler misin diyor kısaca. çünkü biliyorsun async bir işlemin bitmesini beklemiyor ayrı bir işlem daha yapabiliyor. 

### npm (Node Package Manager): Node.js paketlerini yönetmek için kullanılan resmi paket yöneticisidir. npm, paketleri projenize yüklemenizi, güncellemenizi ve kaldırmanızı sağlar. Ayrıca, projenizin bağımlılıklarını yönetmek, paketler arasında geçiş yapmak, paket sürümlerini güncellemek ve paketlerin sağladığı komutları kullanmak için kullanılır. Projede kullanılacak bağımlılıkları package.json dosyasında belirtmeniz ve npm install komutunu kullanmanız gerekir.

npx (Node Package Execute): npx, özellikle tek seferlik veya yaygın olmayan komutları çalıştırmak için kullanılır. Bu komut, yerel olarak yüklü olmayan paketleri veya tek seferlik komutları çalıştırmak için kullanışlıdır. Örneğin, bir npm paketini yüklemek zorunda kalmadan, hızlı bir şekilde bir araç veya komut çalıştırmak istediğinizde npx kullanabilirsiniz. Bu, tekrar kullanılmayan veya nadiren kullanılan araçlar için gereksiz paket yüklemelerinden kaçınmanıza yardımcı olur.

Kısacası, npm genel paket yöneticisi iken, npx daha geçici ve hızlı kullanımlar için tasarlanmıştır. npx ayrıca, belirli bir sürümü yüklemek yerine her zaman en son sürümü kullanmanıza olanak tanır.
